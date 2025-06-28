## 1. docker-compose.yaml
Avand instalat dockerul, lansam file'ul docker-compose.yaml pentru a ridica instanta de RabbitMQ (in caz ca containerul inca nu e pornit)

## 2. rulam aplicatia
_src/main/java/org/example/springamqplistener/ConsumerApplication.java_
>Pe localhost:5672 putem gasi randul numit rabbit-queue si observa, cum au disparut din coada mesajele citite
