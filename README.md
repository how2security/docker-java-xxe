
# docker-java-xxe
## Installation Instructions

```
git clone https://github.com/how2security/docker-java-xxe.git
cd docker-java-xxe
docker build -t docker-java-xxe .
docker run -e MANAGER_USER=admin -e MANAGER_PASSWORD=1234 -v /local/path/to/docker-java-xxe/app/xxe-example:/app -p 8080:8080 docker-java-xxe
Access http://localhost:8080/rest/books
```
