# docker-dokuwiki
Dokuwiki - Docker Compose



Custom volumes configuration :
    volumes:
      - ./data:/config/dokuwiki/data
      - ./conf:/config/dokuwiki/conf  

Instead of :
    volumes:
      - ./config:/config
      
      
