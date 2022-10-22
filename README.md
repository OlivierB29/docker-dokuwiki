# docker-dokuwiki
Dokuwiki - Docker Compose



Custom volumes configuration :

    volumes:
      - ./data:/config/dokuwiki/data
      - ./conf:/config/dokuwiki/conf  

Instead of :

    volumes:
      - ./config:/config
      
      
Pros : All the code is updated, since volumes don't have any runtime

Cons : An update requires to reinstall plugins
