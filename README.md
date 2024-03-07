# Projeto NLW Expert (Node.js)
  O projeto foi desenvolvido durante o evento Next Level Week (NLW) Expert da Rocketseat, na trilha de Node.js. É um sistema de votação em tempo real no qual o usuário tem a capacidade de criar enquetes e votações. Os demais usuários têm a possibilidade de emitir seus votos com a limitação de um voto por máquina enquanto o sistema gera um ranking entre as opções disponíveis.

## Diagrama do sistema
![Captura de tela de 2024-02-27 09-38-07](https://github.com/fabiomirandafig/NLW-expert-nodejs/assets/55500845/2240aa32-d5b7-4fca-98a2-5ee19c33aaef)

## Features
<ul>
<li> Visualização dos resultados de votação em tempo real; </li>
<li> Implementação de WebSocket com Fastify para garantir uma comunicação instantânea em tempo real entre cliente e servidor; </li>
<li> Utilização do padrão de projeto Observer para notificar os clientes sobre atualizações nos resultados de votação; </li>
<li> Armazenamento seguro dos dados utilizando PostgreSQL e Prisma; </li>
<li> Validação de dados utilizando Zod; </li>
</ul>

## Tecnologias:
<ul>
<li> Docker </li>
<li> PostgreSQL </li>
<li> Redis </li>
<li> Fastify </li>
<li> WebSocket </li>
<li> Prisma </li>
<li> Zod </li>
<li> Node.js </li>
<li> TypeScript </li>
</ul>

## Instalação e execução do projeto:
<ul>
<li> Clone o repositório; </li>
<li> Instalar dependências(npm install); </li>
<li> Configure o PostgreSQL e Redis (docker compose up -d); </li>
<li> Copie o arquivo .env.example (cp .env.example .env); </li>
<li> Execute a aplicação (npm run dev); </li>
<li> Teste a aplicação fazendo requisições para o endereço http://localhost:3333; </li>
</ul>
