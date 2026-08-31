# 🔎 Análise de Arquitetura Web – YouTube

## 📌 Sobre o projeto

Este projeto apresenta uma análise prática da arquitetura cliente-servidor de uma aplicação web, utilizando o YouTube como objeto de investigação.

A análise foi realizada por meio das ferramentas de desenvolvedor do navegador (DevTools), com foco na aba **Network**, permitindo observar o tráfego de dados entre o navegador e os servidores da aplicação.

## 🎯 Objetivos

- Identificar requisições HTTP relevantes;
- Analisar métodos HTTP utilizados pela aplicação;
- Observar endpoints e códigos de status;
- Analisar Headers, Payload e Response;
- Compreender o papel das APIs na comunicação cliente-servidor;
- Identificar estruturas de dados JSON;
- Documentar o fluxo de comunicação entre Front-end e Back-end.

## 🛠️ Tecnologias e ferramentas

- 🌐 Navegador Web
- 🛠️ Chrome DevTools
- 📡 HTTP / HTTPS
- 🔌 APIs
- 📦 JSON
- 🖥️ Arquitetura Cliente-Servidor
- 🐙 GitHub

## 🔬 Metodologia

A investigação foi realizada utilizando a aba **Network** das ferramentas de desenvolvedor.

Durante a análise foram observadas diferentes requisições geradas pela aplicação, considerando:

- Endpoint;
- Método HTTP;
- Código de status;
- Request Headers;
- Response Headers;
- Payload;
- Response;
- Comunicação entre cliente e servidor.

## 📊 Evidências da análise

As evidências coletadas durante a investigação estão disponíveis na pasta [`prints`](./prints/).

### 01 – Pesquisa – Headers

![Pesquisa Headers](./prints/01%20-%20Pesquisa%20-%20Headers.jpg)

### 02 – Pesquisa – Payload

![Pesquisa Payload](./prints/02%20-%20Pesquisa%20-%20Payload.jpg)

### 03 – Pesquisa – Response JSON

![Pesquisa Response JSON](./prints/03%20-%20Pesquisa%20-%20Response%20JSON.jpg)

### 04 – Reprodução de vídeo – Headers

![Reprodução de vídeo](./prints/04%20-%20Reprodução%20de%20vídeo%20-%20Headers.jpg)

### 05 – Playback – Headers

![Playback Headers](./prints/05%20-%20Playback%20-%20Headers.jpg)

### 06 – Watchtime – Headers

![Watchtime Headers](./prints/06%20-%20Watchtime%20-%20Headers.jpg)

### 07 – Generate 204 – Headers

![Generate 204](./prints/07%20-%20Generate%20204%20-%20Headers.jpg)

## 🏗️ Arquitetura analisada

O fluxo observado segue o modelo tradicional de comunicação cliente-servidor:

**Usuário → Front-end → API/Servidor → Processamento → Resposta HTTP → Front-end**

Durante a investigação foram identificadas requisições utilizando diferentes métodos HTTP e códigos de status, demonstrando como uma aplicação web moderna realiza comunicação constante com seus servidores.

## 📚 Aprendizados

A experiência permitiu desenvolver conhecimentos práticos sobre:

- Arquitetura cliente-servidor;
- Comunicação HTTP;
- APIs;
- JSON;
- Headers;
- Payloads;
- Status Codes;
- Análise de tráfego de rede;
- Uso das ferramentas DevTools;
- Documentação técnica.

## 👨‍💻 Autor

**João Moreira**

Projeto desenvolvido como parte de uma experiência prática de análise de arquitetura web.
