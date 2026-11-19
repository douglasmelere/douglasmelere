# Douglas Melere

**CTO do Grupo Pag · Desenvolvedor Full Stack · Professor no SENAI Luzerna**

Construo o sistema inteiro: a API, o painel, o app de celular e o agente de IA que atende no WhatsApp.

Sou CTO do Grupo Pag (PagLuz, PAGENERGY e PagNews) e escrevo o código da plataforma que opera o grupo. Também dou aula no SENAI Luzerna e desenvolvo sistemas, apps e automações com IA para outras empresas.

[LinkedIn](https://www.linkedin.com/in/douglas-melere-22840b2a4/) · [E-mail](mailto:douglasmelere@gmail.com) · [Instagram](https://instagram.com/douglasmelere)

| 6 | 3 | ≈4.100 | Bronze |
| :---: | :---: | :---: | :---: |
| produtos no ar | apps na Google Play | commits desde dez/2022, contando repositórios privados | WorldSkills SC 2026, Cyber Segurança |

## Em produção

A maior parte do que eu construo roda em repositório privado. Por isso os links abaixo levam ao produto, não ao código.

### Plataforma Grupo Pag

O sistema que opera uma empresa de energia por assinatura, do primeiro contato no WhatsApp à fatura e à comissão.

A operação da PagLuz rodava em planilhas, formulários e fluxos no n8n. Projetei, desenvolvi e coloquei em produção uma plataforma própria: uma API modular em NestJS que virou a fonte única dos dados (51 módulos e cerca de 580 arquivos de teste), o painel que opera todas as empresas do grupo no mesmo lugar, uma central de WhatsApp com agente de IA e um motor de automações.

`NestJS` `Prisma` `PostgreSQL` `Redis/BullMQ` `React` `Docker` `GitHub Actions`

[pagluz.com.br](https://pagluz.com.br) · [pagenergy.com.br](https://pagenergy.com.br)

### Apps PagLuz

O cliente acompanha faturas, economia e consumo e paga por Pix. O representante cadastra clientes na rua fotografando a conta de luz, gera a proposta em PDF e acompanha a comissão.

São dois apps em React com Capacitor, publicados na web e na Google Play. O app do cliente fala só com um BFF dentro da API do grupo, então o token que enxerga todos os clientes nunca vai para o celular.

`React` `Capacitor` `TypeScript` `PWA`

[App do cliente na web](https://meu.pagluz.com.br) · [PagLuz na Google Play](https://play.google.com/store/apps/details?id=br.com.pagluz.app) · [PagLuz Representantes na Google Play](https://play.google.com/store/apps/details?id=br.com.pagluz.representante)

### PagNews

Notícias do seu setor filtradas por IA, por e-mail, na web e no app Android.

Respondo pelo desenvolvimento técnico (o produto tem sócios). O pipeline coleta as matérias, extrai o texto, remove as duplicadas, classifica cada uma por setor e tema com LLM e calcula quanto ela importa para o perfil de cada assinante. Uma etiqueta só vai para produção se passar num teste contra um conjunto de referência: melhor vazio do que errado.

`NestJS` `PostgreSQL` `React` `Capacitor` `LLM` `Stripe`

[pagnews.com.br](https://pagnews.com.br) · [PagNews na Google Play](https://play.google.com/store/apps/details?id=br.com.pagluz.news)

### Galeno CRM

Um CRM para empresas que vendem pelo WhatsApp. Junta os números da equipe numa fila só, e os agentes de IA atendem, consultam a agenda e passam a conversa para uma pessoa quando precisam.

Criei sozinho e mantenho o produto. A Trovão Brasil já usa o sistema com a própria marca, no plano white-label.

`Fastify` `WebSocket` `BullMQ` `PostgreSQL + pgvector` `React`

[galenocrm.com.br](https://galenocrm.com.br)

### Encontros com o Dr. Everton Fiebig

Inscrição e pagamento dos encontros online de um médico, feitos para um público que usa quase só o celular. A equipe dele publica cada encontro pelo painel, sem código e sem deploy, e acompanha inscritos e pagamentos.

[encontros.drevertonfiebig.com.br](https://encontros.drevertonfiebig.com.br)

## Código aberto

| Projeto | O que é | Tecnologias |
| --- | --- | --- |
| [Reserva de Notebooks](https://github.com/douglasmelere/reserva-notebooks) | Reserva e gestão de notebooks, maletas e carrinhos para uma instituição de ensino, com inventário, ocorrências e relatórios. Feito para o SENAI/SC. | React, TypeScript, PostgreSQL, Prisma, Vitest, Playwright |
| [Quiz de Requisitos](https://github.com/douglasmelere/quiz-requisitos) | Quiz em equipes para ensinar requisitos de software, com telão, placar ao vivo e persistência das partidas. | Node.js, SSE, Docker, sem dependências |
| [Kart Kids](https://github.com/douglasmelere/kart-kids) | Jogo de corrida 2D multiplayer com salas públicas e privadas, bots e ranking persistente. | Phaser, Socket.IO, Node.js, SQLite |
| [Handbook Offline](https://github.com/douglasmelere/handbook-offline) | Manual de campo de segurança para estudo e CTF: infraestrutura, defesa, ataque e forense numa página só. | HTML, Docker |

## Ensino

Sou professor no SENAI Luzerna (Especialista de Ensino II), nas unidades de Modelagem de Sistemas, Desenvolvimento de APIs, Codificação para Back-End e Versionamento e Colaboração. Sou [educador credenciado AWS Academy](https://www.credly.com/badges/136efb49-947f-4b7c-9d11-afb31a52a608/public_url).

Também oriento projetos de alunos, como o LibraIA, um tradutor de Libras para português falado que roda no navegador.

## Tecnologias

- **Back-end:** TypeScript, Node.js, NestJS, Fastify, PostgreSQL, Prisma, Redis e BullMQ.
- **Front-end e mobile:** React, Vite, Tailwind CSS e Capacitor.
- **IA:** agentes com LLM no WhatsApp, classificação de conteúdo e busca com pgvector.
- **Entrega:** Docker, Coolify, GitHub Actions e observabilidade.

## Formação

Formação em Análise e Desenvolvimento de Sistemas e Técnico em Informática para Internet. Em estudo: inteligência artificial e ciência de dados.

## Contato

Para projetos, oportunidades ou colaboração, fale comigo pelo [LinkedIn](https://www.linkedin.com/in/douglas-melere-22840b2a4/) ou pelo [e-mail](mailto:douglasmelere@gmail.com).
