Uruchomienie aplikacji<br>
docker build --build-arg VERSION=1.2.3 -f Dockerfile_lab5 -t nginx_proxy:v1 .  <br>
docker run -d -p 8080:80 --name lab5 nginx_proxy:v1  <br>

![image](https://github.com/uladdzerzh/TCH-lab5/assets/61791586/1f8654db-a1c1-4a38-9923-6388268a6aaa)
