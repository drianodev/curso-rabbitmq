# Curso RabbitMQ - Microserviço em Java Spring Boot com RabbitMQ

Este repositório faz parte de um curso que ensina a criar um microserviço em Java Spring Boot com RabbitMQ. O projeto é responsável por receber requisições e gerar mensagens para outros microsserviços, que atuam como consumidores dessas mensagens.

## Componentes do Projeto

1. **Produtor em Java com Spring:**
   - Desenvolvido um produtor em Java usando o framework Spring Boot.

2. **Consumidor em Java com Spring:**
   - Implementado um consumidor em Java com Spring Boot.

3. **Consumidor em Node.js:**
   - Criado outro consumidor em Node.js para diversificar as tecnologias utilizadas.

## Configuração do Prefetch Count do RabbitMQ

Adicionada configuração do Prefetch Count no RabbitMQ para otimizar o processamento das mensagens.

## Submódulos

Este repositório utiliza submódulos para organizar os diferentes componentes do projeto:

- [consumidor-estoque](https://github.com/drianodev/consumidor-estoque)
- [consumidor-preco](https://github.com/drianodev/consumidor-preco)
- [librabbitmq](https://github.com/drianodev/librabbitmq)
- [estoquepreco-api](https://github.com/drianodev/estoquepreco-api)

Certifique-se de inicializar e atualizar os submódulos ao clonar o repositório:
```bash
git clone --recursive https://github.com/drianodev/curso-rabbitmq.git
```

## Vídeos do Curso

Confira a implementação deste projeto assistindo aos vídeos do curso disponíveis [aqui](https://www.youtube.com/playlist?list=PL1OeYyl9zqzHDN67rto7KMtezTLmk1N-K).
