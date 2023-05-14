# official_web
达智特官网

## 部署服务
    ```
    docker build -t official_web .
    docker run -it -p 80:80 -p 443:443 official_web
    ```