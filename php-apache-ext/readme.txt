1. Dockerfile을 이용해 php-apache-ext 라는 이미지 생성
docker build -t php-apache-ext [폴더명]

2. docker run -d -p 80:80 --name [Container Name] -v $(pwd):/var/www/html php-apache-ext
