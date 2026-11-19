<p align="center">
  <img src="assets/banner.png" width="100%" alt="Douglas Melere, Desenvolvedor Full Stack e CTO. Construo o sistema inteiro: a API, o painel, o app de celular e o agente de IA que atende no WhatsApp.">
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/douglas-melere-22840b2a4/"><img src="assets/btn-linkedin.png" height="46" alt="LinkedIn"></a>
  <a href="mailto:douglasmelere@gmail.com"><img src="assets/btn-email.png" height="46" alt="E-mail"></a>
  <a href="https://instagram.com/douglasmelere"><img src="assets/btn-instagram.png" height="46" alt="Instagram"></a>
</p>

Sou CTO do Grupo Pag (PagLuz, PAGENERGY e PagNews) e escrevo o código da plataforma que opera o grupo. Também dou aula no SENAI Luzerna e desenvolvo sistemas, apps e automações com IA para outras empresas.

<p align="center">
  <img src="assets/numeros.png" width="100%" alt="6 produtos no ar. 3 apps na Google Play. Cerca de 4.100 commits desde dezembro de 2022, contando repositórios privados. Bronze na WorldSkills SC 2026, em Cyber Segurança.">
</p>

## Em produção

A maior parte do que eu construo roda em repositório privado. Por isso os links abaixo levam ao produto, não ao código.

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://pagluz.com.br"><img src="assets/shot-plataforma.webp" width="100%" alt="Página inicial do site da PagLuz"></a>
      <h3>Plataforma Grupo Pag</h3>
      <p>O sistema que opera uma empresa de energia por assinatura, do primeiro contato no WhatsApp à fatura e à comissão.</p>
      <p>Tirei a operação das planilhas e dos fluxos no n8n: uma API modular em NestJS (51 módulos, cerca de 580 arquivos de teste), o painel que opera todas as empresas do grupo, uma central de WhatsApp com agente de IA e um motor de automações.</p>
      <p><code>NestJS</code> <code>Prisma</code> <code>PostgreSQL</code> <code>Redis/BullMQ</code> <code>React</code> <code>Docker</code></p>
      <p><sub>Na imagem, o site público. O painel tem dados de clientes e não aparece aqui.</sub></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://play.google.com/store/apps/details?id=br.com.pagluz.app"><img src="assets/shot-apps-pagluz.webp" width="100%" alt="Arte do app PagLuz na Google Play: suas faturas de energia, economia e consumo em um só lugar"></a>
      <h3>Apps PagLuz</h3>
      <p>O cliente acompanha faturas, economia e consumo e paga por Pix. O representante cadastra clientes na rua fotografando a conta de luz e gera a proposta em PDF.</p>
      <p>Dois apps em React com Capacitor, na web e na Google Play. O app do cliente fala só com um BFF dentro da API, então o token que enxerga todos os clientes nunca vai para o celular.</p>
      <p><code>React</code> <code>Capacitor</code> <code>TypeScript</code> <code>PWA</code></p>
      <p><a href="https://meu.pagluz.com.br">App na web</a> · <a href="https://play.google.com/store/apps/details?id=br.com.pagluz.app">Cliente na Play</a> · <a href="https://play.google.com/store/apps/details?id=br.com.pagluz.representante">Representantes na Play</a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://pagnews.com.br"><img src="assets/shot-pagnews.webp" width="100%" alt="Página inicial do PagNews"></a>
      <h3>PagNews</h3>
      <p>Notícias do seu setor filtradas por IA, por e-mail, na web e no app Android.</p>
      <p>Respondo pelo desenvolvimento técnico (o produto tem sócios). O pipeline coleta as matérias, remove as duplicadas, classifica cada uma com LLM e calcula quanto ela importa para cada assinante. Uma etiqueta só vai para produção se passar num teste contra um conjunto de referência.</p>
      <p><code>NestJS</code> <code>PostgreSQL</code> <code>React</code> <code>Capacitor</code> <code>LLM</code> <code>Stripe</code></p>
      <p><a href="https://pagnews.com.br">pagnews.com.br</a> · <a href="https://play.google.com/store/apps/details?id=br.com.pagluz.news">Google Play</a></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://galenocrm.com.br"><img src="assets/shot-galeno.webp" width="100%" alt="Página inicial do Galeno CRM"></a>
      <h3>Galeno CRM</h3>
      <p>Um CRM para empresas que vendem pelo WhatsApp: os números da equipe numa fila só e agentes de IA que atendem, consultam a agenda e passam a conversa para uma pessoa.</p>
      <p>Criei sozinho e mantenho o produto. A Trovão Brasil já usa o sistema com a própria marca, no plano white-label.</p>
      <p><code>Fastify</code> <code>WebSocket</code> <code>BullMQ</code> <code>PostgreSQL + pgvector</code> <code>React</code></p>
      <p><a href="https://galenocrm.com.br">galenocrm.com.br</a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://encontros.drevertonfiebig.com.br"><img src="assets/shot-encontros.webp" width="100%" alt="Página dos encontros online do Dr. Everton Fiebig"></a>
      <h3>Encontros com o Dr. Everton Fiebig</h3>
      <p>Inscrição e pagamento dos encontros online de um médico, feitos para um público que usa quase só o celular.</p>
      <p>A equipe dele publica cada encontro pelo painel, sem código e sem deploy, e acompanha inscritos e pagamentos.</p>
      <p><code>vinext</code> <code>React</code> <code>PostgreSQL</code> <code>Prisma</code> <code>Docker</code></p>
      <p><a href="https://encontros.drevertonfiebig.com.br">encontros.drevertonfiebig.com.br</a></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://pagenergy.com.br"><img src="assets/shot-sites.webp" width="100%" alt="Página inicial do site da PAGENERGY"></a>
      <h3>Sites PagLuz e PAGENERGY</h3>
      <p>Os sites do grupo em vinext: páginas reais e indexáveis, servidas por Node no Coolify.</p>
      <p>Converti o site da PagLuz de um HTML de arquivo único para o App Router sem mudar o visual. No da PAGENERGY, troquei uma SPA com rotas por hash por páginas com blog, SEO por página e sitemap.</p>
      <p><code>vinext</code> <code>React</code> <code>TypeScript</code> <code>SEO</code> <code>Docker</code></p>
      <p><a href="https://pagluz.com.br">pagluz.com.br</a> · <a href="https://pagenergy.com.br">pagenergy.com.br</a></p>
    </td>
  </tr>
</table>

## Código aberto

| Projeto | O que é | Tecnologias |
| --- | --- | --- |
| [Reserva de Notebooks](https://github.com/douglasmelere/reserva-notebooks) | Reserva e gestão de notebooks, maletas e carrinhos para uma instituição de ensino, com inventário, ocorrências e relatórios. Feito para o SENAI/SC. | React, TypeScript, PostgreSQL, Prisma, Vitest, Playwright |
| [Quiz de Requisitos](https://github.com/douglasmelere/quiz-requisitos) | Quiz em equipes para ensinar requisitos de software, com telão, placar ao vivo e persistência das partidas. | Node.js, SSE, Docker, sem dependências |
| [Kart Kids](https://github.com/douglasmelere/kart-kids) | Jogo de corrida 2D multiplayer com salas públicas e privadas, bots e ranking persistente. | Phaser, Socket.IO, Node.js, SQLite |
| [Handbook Offline](https://github.com/douglasmelere/handbook-offline) | Manual de campo de segurança para estudo e CTF: infraestrutura, defesa, ataque e forense numa página só. | HTML, Docker |

## Ensino

<a href="https://www.credly.com/badges/136efb49-947f-4b7c-9d11-afb31a52a608/public_url"><img src="assets/aws-academy-educator.png" width="120" align="right" alt="Selo AWS Academy Educator"></a>

Sou professor no SENAI Luzerna (Especialista de Ensino II), nas unidades de Modelagem de Sistemas, Desenvolvimento de APIs, Codificação para Back-End e Versionamento e Colaboração. Sou [educador credenciado AWS Academy](https://www.credly.com/badges/136efb49-947f-4b7c-9d11-afb31a52a608/public_url).

Também oriento projetos de alunos, como o LibraIA, um tradutor de Libras para português falado que roda no navegador.

## Tecnologias

<p>
  <img src="assets/stack.svg" width="680" alt="TypeScript, JavaScript, Node.js, NestJS, Prisma, PostgreSQL, Redis, React, Vite, Tailwind CSS, Docker, GitHub Actions, Linux e Python">
</p>

- **Back-end:** TypeScript, Node.js, NestJS, Fastify, PostgreSQL, Prisma, Redis e BullMQ.
- **Front-end e mobile:** React, Vite, Tailwind CSS e Capacitor.
- **IA:** agentes com LLM no WhatsApp, classificação de conteúdo e busca com pgvector.
- **Entrega:** Docker, Coolify, GitHub Actions e observabilidade.

## Formação

Formação em Análise e Desenvolvimento de Sistemas e Técnico em Informática para Internet. Em estudo: inteligência artificial e ciência de dados.

## Contato

Para projetos, oportunidades ou colaboração, fale comigo pelo [LinkedIn](https://www.linkedin.com/in/douglas-melere-22840b2a4/) ou pelo [e-mail](mailto:douglasmelere@gmail.com).
