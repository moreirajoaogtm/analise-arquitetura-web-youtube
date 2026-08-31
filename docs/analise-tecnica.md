# 📚 Análise Técnica da Arquitetura Web – YouTube

## 1. Introdução

Este documento apresenta uma análise técnica da comunicação entre o navegador e os servidores de uma aplicação web, utilizando o YouTube como objeto de estudo.

A investigação foi realizada utilizando as ferramentas de desenvolvedor do navegador (DevTools), principalmente a aba **Network**, permitindo observar as requisições HTTP realizadas durante diferentes ações do usuário.

---

## 2. Objetivo da análise

A análise teve como objetivo compreender, na prática, como ocorre a comunicação entre uma aplicação web e seus servidores.

Foram observados:

- Requisições HTTP;
- Métodos HTTP;
- URLs e endpoints;
- Request Headers;
- Response Headers;
- Payload;
- Response;
- Códigos de status HTTP;
- Estruturas de dados em JSON;
- Comunicação entre cliente e servidor.

---

## 3. Arquitetura cliente-servidor

A aplicação analisada utiliza o modelo tradicional de arquitetura cliente-servidor.

De forma simplificada, o fluxo observado pode ser representado da seguinte maneira:

**Usuário → Front-end → Requisição HTTP → API/Servidor → Processamento → Resposta HTTP → Front-end**

### Cliente (Front-end)

O navegador atua como cliente da aplicação.

Ele recebe as ações realizadas pelo usuário e envia requisições aos servidores responsáveis pelo processamento das funcionalidades solicitadas.

### Servidor (Back-end)

O servidor recebe as requisições enviadas pelo cliente, processa os dados necessários e retorna uma resposta.

Essa resposta pode conter informações estruturadas, como dados em JSON, além de códigos de status HTTP e cabeçalhos de resposta.

---

## 4. Requisições HTTP

Durante a investigação, foram observadas diferentes requisições realizadas pelo navegador.

As requisições possuem informações importantes para a comunicação entre cliente e servidor, como:

- Método HTTP;
- URL;
- Endpoint;
- Request Headers;
- Parâmetros;
- Payload;
- Cookies;
- Informações de contexto da requisição.

A aba **Network** do DevTools permitiu visualizar essas informações durante a utilização da aplicação.

---

## 5. Métodos HTTP

Durante a análise foram identificadas requisições utilizando diferentes métodos HTTP.

Entre os principais métodos observados ou relacionados ao funcionamento da aplicação estão:

### GET

Utilizado principalmente para solicitar informações ou recursos ao servidor.

### POST

Utilizado para enviar informações ao servidor para processamento.

Na análise realizada, foram observadas requisições POST associadas a funcionalidades da aplicação.

---

## 6. Request Headers

Os **Request Headers** representam informações enviadas pelo cliente durante uma requisição HTTP.

Entre as informações que podem ser encontradas estão:

- Tipo de conteúdo;
- Origem da requisição;
- User-Agent;
- Cookies;
- Informações de autenticação;
- Preferências de comunicação;
- Identificação do navegador.

A análise dos Request Headers permite compreender melhor o contexto em que determinada requisição foi realizada.

---

## 7. Response Headers

Os **Response Headers** são informações enviadas pelo servidor juntamente com a resposta HTTP.

Eles podem indicar informações relacionadas a:

- Tipo de conteúdo retornado;
- Políticas de cache;
- Segurança;
- Controle de origem;
- Cookies;
- Configurações da resposta.

Esses dados ajudam a compreender como o servidor está respondendo às solicitações realizadas pelo cliente.

---

## 8. Payload

O **Payload** corresponde aos dados enviados no corpo de determinadas requisições HTTP.

Em aplicações modernas, é comum encontrar dados estruturados no formato **JSON**.

Durante a investigação, foi possível observar dados relacionados às ações realizadas pelo usuário e enviados para processamento no servidor.

---

## 9. Response

A **Response** representa os dados retornados pelo servidor após o processamento de uma requisição.

Dependendo da funcionalidade analisada, a resposta pode conter:

- Dados estruturados;
- Informações sobre recursos;
- Metadados;
- Identificadores;
- Status da operação;
- Dados em formato JSON.

A análise da resposta permite compreender quais informações o servidor devolve ao cliente.

---

## 10. Códigos de status HTTP

Os códigos de status HTTP indicam o resultado do processamento de uma requisição.

Durante a análise foram observados códigos relacionados ao funcionamento normal da aplicação.

Alguns exemplos importantes são:

| Código | Significado |
|---|---|
| 200 | Requisição processada com sucesso |
| 204 | Requisição processada sem conteúdo na resposta |
| 400 | Requisição inválida |
| 401 | Não autorizado |
| 403 | Acesso proibido |
| 404 | Recurso não encontrado |
| 500 | Erro interno do servidor |

Os códigos observados nas evidências foram utilizados para compreender o comportamento das diferentes requisições analisadas.

---

## 11. JSON e troca de informações

O formato **JSON (JavaScript Object Notation)** é utilizado para representar dados estruturados e facilitar a comunicação entre diferentes componentes de uma aplicação.

Na análise realizada, foram observadas estruturas JSON em requisições e respostas.

Esse formato permite organizar informações utilizando estruturas compostas por propriedades e valores.

---

## 12. Comunicação entre Front-end e servidor

A análise demonstrou que o navegador funciona como um cliente que realiza solicitações aos serviços da aplicação.

O fluxo básico observado é:

1. O usuário realiza uma ação;
2. O Front-end identifica a ação;
3. O navegador envia uma requisição HTTP;
4. O servidor recebe a requisição;
5. O servidor realiza o processamento necessário;
6. O servidor retorna uma resposta;
7. O Front-end interpreta a resposta;
8. A interface apresenta o resultado ao usuário.

Esse processo ocorre continuamente durante a utilização de aplicações web modernas.

---

## 13. Evidências utilizadas

As evidências coletadas durante a investigação estão disponíveis na pasta [`prints`](../prints/).

Foram analisadas diferentes situações:

- Pesquisa de conteúdo;
- Reprodução de vídeo;
- Playback;
- Watchtime;
- Generate 204.

As imagens servem como evidências visuais das informações observadas na aba **Network** do DevTools.

---

## 14. Conclusão

A análise permitiu compreender, de forma prática, como uma aplicação web utiliza a arquitetura cliente-servidor para realizar a comunicação entre o navegador e seus serviços.

Por meio do DevTools foi possível observar requisições HTTP, métodos, headers, payloads, respostas, códigos de status e estruturas JSON.

A investigação também demonstrou a importância da aba **Network** para analisar o comportamento de aplicações web e compreender o fluxo de comunicação entre cliente e servidor.

---

## 15. Conhecimentos desenvolvidos

A realização deste projeto contribuiu para o desenvolvimento dos seguintes conhecimentos:

- Arquitetura cliente-servidor;
- Comunicação HTTP;
- Métodos HTTP;
- Request Headers;
- Response Headers;
- Payload;
- Response;
- JSON;
- Códigos de status HTTP;
- Análise de requisições utilizando DevTools;
- Observação do fluxo de comunicação entre Front-end e Back-end.
