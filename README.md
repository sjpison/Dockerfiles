# Dockerfiles

테스트나 개발 환경을 만들기 위한 Dockerfile 을 모아두는 곳입니다.

## Common

Docker Toolbox를 사용하는 경우 Dockerfile 은 User의 Home 디렉토리 내부에서 실행해야 합니다.

사용을 원하는 Dockerfile의 상위 디렉토리에서
<pre>
docker build -t [Image name] [Directory Name]
</pre>
으로 실행합니다.


## php-apache-ext

php7.1.12, Apache2

Extensions : GD, MySQLi, zip, mbstring, PDO, PDO_MySQL

.htaccess

