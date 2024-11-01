# Repositório de Talks

Este repositório é uma coleção de talks que eu ministrei sobre diversos tópicos técnicos, organizados por data. Cada talk é armazenada como um submódulo Git, para que você possa clonar e explorar facilmente o conteúdo de cada talk.

### Submódulos

Este repositório contém os seguintes submódulos, listados em ordem cronológica:

1. **[WebSockets e AWS API Gateway WebSocket](https://github.com/prandogabriel/tech-talk-ws-and-aws-api-gateway-ws)** (Agosto de 2021): Este talk aborda o protocolo WebSocket e como ele pode ser usado com AWS API Gateway para construir aplicações em tempo real.
    - Caminho: `tech-talk-ws-and-aws-api-gateway-ws`
   
2. **[Elastic Stack](https://github.com/prandogabriel/tech-talk-elastic-stack)** (Novembro de 2021): Este talk é sobre o Elastic Stack (anteriormente conhecido como ELK Stack), incluindo Elasticsearch, Logstash e Kibana, e como eles podem ser usados para pesquisar, analisar e visualizar dados em tempo real.
    - Caminho: `tech-talk-elastic-stack`

3. **[AWS Step Functions](https://github.com/prandogabriel/tech-talk-aws-step-functions)** (Janeiro de 2022): Um talk focando nas AWS Step Functions e como elas podem ser usadas para coordenar aplicações distribuídas e microservices.
    - Caminho: `tech-talk-aws-step-functions`
   
4. **[Performance de Sistema de Gerenciamento de Banco de Dados (SGBD)](https://github.com/prandogabriel/tech-talk-sgbd-performance)** (Junho de 2022): Neste talk, discutimos técnicas de otimização de desempenho para sistemas de gerenciamento de bancos de dados.
    - Caminho: `tech-talk-sgbd-performance`
   
5. **[Computação Serverless](https://github.com/prandogabriel/talk-serverless)** (Julho de 2022): Um talk que mergulha no mundo da computação serverless, suas vantagens e como ela pode ser usada para construir aplicações escaláveis.
    - Caminho: `talk-serverless`
   
6. **[Introdução ao MQTT](https://github.com/prandogabriel/talk-introduction-to-mqtt)** (Novembro de 2022): Este talk oferece uma introdução ao MQTT, um protocolo de mensagens leve para pequenos sensores e dispositivos móveis.
    - Caminho: `talk-introduction-to-mqtt`
   
7. **[Performance e Escalabilidade em bancos SQL](https://github.com/prandogabriel/talk-postgres-performance)** (Agosto de 2023): Este talk técnicas de otimização de desempenho em bancos SQL mais voltado ao PostgresSQL e seus tipos de index.
    - Caminho: `talk-postgres-performance`
   
8. **[Workshop - Introdução a aplicações serverless na AWS](https://github.com/prandogabriel/workshop-serverless-aws)** (Junho de 2024): Workshop oferecido durante a semana acadêmica de eng. comp e ADS da UTFPR-PB.
    - Caminho: `workshop-serverless-aws`
   
9. **[Evitando lock-ins, construindo sua própria layer de observabilidade com AWS Lambda telemetry API](https://github.com/prandogabriel/talk-observability-building-it-yourself)** (Agosto de 2024): Talk apresentada no DevOpsDays Curitiba 2024.
    - Caminho: `talk-observability-building-it-yourself`

10. **[Desenvolvendo soluções com IA de forma rápida na GCP com Serverless](https://github.com/prandogabriel/talk-gcp-serverless-with-ai)** (Setembro de 2024): Talk apresentada no DevFest 2024 - Pato Branco.
    - Caminho: `talk-gcp-serverless-with-ai`

11. **[Desmistificando Websockets com AWS Lambda e API Gateway](https://github.com/prandogabriel/talk-websocket-with-lambda-and-api-gw)** (Outubro de 2024): Talk apresentada no Recrutatech 2024 - Curitiba.
    - Caminho: `talk-websocket-with-lambda-and-api-gw`

12. **[Construindo sua própria layer de observabilidade com AWS Lambda telemetry API](https://github.com/prandogabriel/talks/blob/main/assets/serverless-observability/talk-building-observability-layer.pdf)** (Outubro de 2024): Talk apresentada no Serverless Days SP 2024 - São Paulo.
    - Caminho: `assets/serverless-observability`

### Como Clonar este Repositório

Para clonar este repositório junto com seus submódulos, você pode usar o seguinte comando Git:

```sh
git clone --recurse-submodules https://github.com/prandogabriel/talks.git
```

Se você já clonou o repositório, mas não incluiu os submódulos, você pode carregar os submódulos usando os seguintes comandos:

```sh
git submodule init
git submodule update
git submodule -q foreach git pull -q origin main
```

### Contribuindo

Este repositório destina-se a ser uma coleção das minhas talks. Se você tiver alguma dúvida ou feedback sobre os talks, sinta-se à vontade para abrir um issue.

### Licença

Cada submódulo/talk pode ter sua própria licença. Por favor, verifique os repositórios individuais para mais informações.

---

Obrigado por tirar um tempo para explorar minhas talks!

Se você achou o conteúdo interessante e gostaria de me convidar para falar sobre algum tópico técnico, por favor, entre em contato comigo através do [LinkedIn](https://www.linkedin.com/in/prandogabriel/) ou envie um e-mail para gprando55@gmail.com. Estou sempre animado para compartilhar conhecimento e conectar-me com outros profissionais!

- [Gabriel Prando](https://www.linkedin.com/in/prandogabriel/)

---