# docker-html-server
Simple docker starter for hosting html files using ningx


**File structure**

```
project-directory
│   docker-compose.yaml 
│
└───www
│   │   index.html -- file content here
```
  \
  
  **Docker Compose Up**

```
docker-compose up -d
```
  \
now go to the following address in the browser and see that file work:
http://localhost:8080

## How to stop NINGX

```
docker-compose stop
```
