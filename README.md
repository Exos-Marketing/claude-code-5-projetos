# 5 projetos do GitHub que transformam o Claude Code numa operação inteira

O modelo é o mesmo para todo mundo. A diferença está nas ferramentas que você dá para ele.

Lista mantida pela [Exos Marketing](https://www.instagram.com/exosmkt/). Os projetos são dos autores indicados em cada item; aqui só reunimos os links oficiais e como começar.

## Como instalar qualquer um deles

Abra o **Claude Code** no computador e cole, trocando o link:

```
Instala e configura este projeto para eu usar aqui no Claude Code, seguindo o README oficial: [link do projeto]
```

O Claude Code lê o README, instala o que precisa e te avisa se faltar alguma coisa (conta, chave ou permissão).

---

## 1. HyperFrames, da HeyGen: o Claude Code vira editor de vídeo

https://github.com/heygen-com/hyperframes

Você descreve o vídeo em linguagem natural ("pega esse vídeo, coloca a legenda, cria uma abertura e renderiza") e ele monta e renderiza em MP4 no seu computador. Tem plugin para o Claude Code.

## 2. Google Workspace CLI: o Claude Code conversando com Gmail, Drive e Agenda

https://github.com/googleworkspace/cli

Projeto open source no GitHub do Google Workspace. Exemplo: "olha meus e-mails de hoje e separa tudo que precisa de resposta".

Atenção: não é um produto oficialmente suportado pelo Google, ainda está em desenvolvimento ativo e pede que você crie credenciais no Google Cloud (o Claude Code te guia).

## 3. Apify: milhares de scrapers prontos

https://github.com/apify/apify-mcp-server (ou a versão hospedada: https://mcp.apify.com)

A loja da Apify tem mais de 87 mil ferramentas prontas de coleta de dados. Exemplo: "encontra 100 academias no Instagram desta cidade e separa quem não tem site".

Atenção: precisa de conta na Apify, e rodar as ferramentas consome créditos.

## 4. Agent Skills, do Addy Osmani: processo de engenharia para agentes

https://github.com/addyosmani/agent-skills

Mais de 20 skills de engenharia. Em vez de "cria meu aplicativo", o agente segue um processo: entende, quebra em tarefas, executa uma por vez e verifica.

## 5. Playwright CLI, da Microsoft: prova em vez de narração

https://github.com/microsoft/playwright-cli

O agente abre um navegador de verdade, clica, preenche e te mostra o que aconteceu. Assim "funcionou perfeitamente" vira coisa testada.

Instalação direta: `npm install -g @playwright/cli`

---

Links e informações conferidos em 15/10/2026. Cada projeto tem a própria licença; consulte o repositório de cada um.
