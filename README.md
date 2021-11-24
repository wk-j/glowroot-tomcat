# Glowroot

- Tomcat 8.5.34

```
wget  https://downloads.apache.org/tomcat/tomcat-8/v8.5.57/bin/apache-tomcat-8.5.57.zip
unzip glowroot-0.13.6-dist.zip
docker-compose up
```

# admin.json

```json
  "web": {
    "port": 4000,
    "bindAddress": "0.0.0.0"
  },
```

# Test

- http://localhost:8080
- http://localhost:4000