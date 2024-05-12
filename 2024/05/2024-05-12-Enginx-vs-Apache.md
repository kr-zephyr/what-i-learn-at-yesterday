# Enginx vs Apache

refereced by [NGINX VS APACHE](https://medium.com/@ralphbetta/nginx-vs-apache-e66a3bd869f9)  

- 기본적으로 NGINX의 아키텍쳐는 Event-Driven 방식으로 비동기 처리를 지원한다.
- 아파치는 Process-Driven 방식으로 요청에 대해 처리가 완료될 때까지 동기로 동작한다.
- NGINX가 아파치에 비해 가볍지만 아파치와 같은 Modular 특성은 가지지 못한다.
- NGINX는 static 처리에 강점을 가지고, 아파치는 dynamic 처리에 강점을 가진다.
- 위와 같은 특성으로 NGINX는 좀 더 적은 resource를 사용하며, 속도가 빠르다.
- 아파치는 Modular 특성을 가짐으로 인해 좀 더 설정이 복잡하고 많은 resource를 사용하며, Traffic이 몰릴 경우 더 많은 resource를 요구한다.