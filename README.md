# API

Back-end de aplicativo de entrega de comida (também conhecido como Ifood, QueroDelivery) desenvolvido com TypeScript, Drizzle e ElysiaJS.

> 🔥 Este projeto tem como objetivo manter o tempo de execução independente, o que significa que ele deve funcionar em Bun, Node, Cloudflare Workers ou qualquer tempo de execução compatível com Web Standard API.

## Rodando

Este projeto depende do Docker para configurar o banco de dados. Com o Docker instalado, clone o projeto, instale dependências, configure os contêineres do Docker e execute o aplicativo.

> Você também deve executar migrações para criar tabelas de banco de dados e executar a semente para preencher o banco de dados com dados falsos.

```sh
bun i
docker compose up -d
bun migrate
bun seed
bun dev
```

## Características

> O resumo dos recursos está listado abaixo. Todos os recursos contêm testes E2E.

- Registra um novo restaurante;
- É possível fazer login como gerente de restaurante;
- Pode se registrar como um novo cliente;
- Cria um pedido para o restaurante;
- Gerencia o menu do restaurante;
- Gerencia as avaliações dos restaurantes;
- É capaz de deixar uma avaliação;
- Gerencia os pedidos do restaurante;
- Atualiza o perfil público do restaurante;
- É capaz de abrir/fechar o restaurante;
- Lista as métricas do restaurante.
