# Module 9 - Subscriber

## Apa itu AMQP?

AMQP adalah singkatan dari Advanced Message Queuing Protocol. AMQP adalah protokol yang digunakan untuk mengirim pesan antar aplikasi melalui message broker.

Pada tutorial ini, AMQP digunakan agar publisher bisa mengirim event ke RabbitMQ, lalu subscriber bisa menerima dan memproses event tersebut.

## Apa arti `guest:guest@localhost:5672`?

`guest` yang pertama adalah username untuk masuk ke RabbitMQ.

`guest` yang kedua adalah password untuk masuk ke RabbitMQ.

`localhost` berarti RabbitMQ berjalan di komputer kita sendiri.

`5672` adalah port yang digunakan RabbitMQ untuk komunikasi AMQP.
'@ > readme.md