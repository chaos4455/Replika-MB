# Replika AI Message Broker - High-Performance Async Broker & Analytics v0.3.1.2 (FastAPI/Python)

<p align="center">
  <img src="https://img.shields.io/badge/Author-Elias_Andrade_|_Replika_AI_Solutions-blue?style=for-the-badge&logo=Python&logoColor=white" alt="Author Elias Andrade | Replika AI Solutions">
  <img src="https://img.shields.io/badge/Version-0.3.1.2--fastapi--torch-green?style=for-the-badge" alt="Version 0.3.1.2">
  <img src="https://img.shields.io/badge/Status-Functional_Showcase_&_POC-brightgreen?style=for-the-badge" alt="Status: Functional Showcase & POC">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue?style=flat-square&logo=python&logoColor=white" alt="Python 3.10+">
  <img src="https://img.shields.io/badge/Framework-FastAPI-green?style=flat-square&logo=fastapi&logoColor=white" alt="Framework FastAPI">
  <img src="https://img.shields.io/badge/Async-AsyncIO-purple?style=flat-square" alt="AsyncIO">
  <img src="https://img.shields.io/badge/Database-SQLite_|_Tortoise_ORM-orange?style=flat-square" alt="Database SQLite | Tortoise ORM">
  <img src="https://img.shields.io/badge/Security-JWT_|_SlowAPI_|_SSL-red?style=flat-square" alt="Security JWT | SlowAPI | SSL">
  <img src="https://img.shields.io/badge/Architecture-Microservice_|_Dockerized-lightblue?style=flat-square&logo=docker" alt="Architecture Microservice | Dockerized">
  <img src="https://img.shields.io/badge/License-Proprietary_|_Replika_AI_Solutions-lightgrey?style=flat-square" alt="License: Proprietary | Replika AI Solutions">
</p>

<p align="center">
  <a href="https://wa.me/5511913353137" target="_blank"><img src="https://img.shields.io/badge/WhatsApp-Contact_Elias-brightgreen?style=flat-square&logo=whatsapp&logoColor=white" alt="WhatsApp Contact"></a>
  <!-- Add LinkedIn/GitHub Profile Badges if desired -->
</p>


## 👨‍💻 Sobre o Autor

Eu sou **Elias Andrade**, um apaixonado por tecnologia e resolução de problemas, atuando como Arquiteto de Soluções e Desenvolvedor Full Stack na **Replika AI Solutions**. Tenho vasta experiência em desenvolvimento Python, arquitetura de sistemas, cloud, DevOps, MLOps e na aplicação de Inteligência Artificial para criar soluções de negócio inovadoras. Este projeto é um reflexo dessa paixão e expertise.

**Vamos conectar e discutir como a tecnologia pode impulsionar o seu negócio?**

*   **WhatsApp:** [+55 11 9 1335 3137](https://wa.me/5511913353137)

---

**Maringá, Paraná, Brasil 🇧🇷 | 03 de Abril de 2025, 12:20 horas**

## 👋 Olá! Eu sou Elias Andrade, Arquiteto de Soluções e Desenvolvedor na Replika AI Solutions

Este repositório contém o código-fonte e a documentação do **Replika AI Message Broker**, um projeto autoral que desenvolvi não apenas como uma ferramenta interna estratégica para nossa software house, mas também como um **showcase robusto das minhas capacidades e da nossa filosofia de engenharia** aqui na Replika AI.

## 🎯 Motivação e Propósito: Acelerando a Inovação em IA/ML

No dinâmico mundo da Inteligência Artificial e Machine Learning, a velocidade de prototipagem, deployment e iteração é crucial. Ferramentas de mercado como RabbitMQ ou Kafka são poderosas, mas muitas vezes trazem uma complexidade ou um conjunto de funcionalidades que vão além do necessário para muitos dos nossos fluxos de trabalho iniciais ou específicos, ou não oferecem o nível de controle e otimização que desejo.

Percebi a necessidade de uma solução de mensageria:

1.  **Leve e Performática:** Focada em alto throughput e baixa latência para comunicação entre microserviços, especialmente em pipelines de IA/ML.
2.  **Asynchronous by Design:** Construída sobre o ecossistema `asyncio` do Python e a velocidade do FastAPI.
3.  **Simples de Usar e Integrar:** Com uma API clara e direta para publicação e consumo de mensagens.
4.  **Observabilidade Integrada:** Com um dashboard de analytics em tempo real para monitorar a saúde e performance do broker.
5.  **Segura e Controlada:** Implementando autenticação JWT e rate limiting.
6.  **Totalmente Customizável:** Sendo proprietário, temos controle total para adaptar e otimizar para nossos casos de uso específicos.

Este projeto nasceu dessa necessidade, servindo como um **acelerador para os projetos da Replika AI Solutions** e, igualmente importante, como uma **demonstração tangível de expertise técnica**.


# 🏛️ Arquitetura e Documentação Técnica: Replika AI Message Broker v1 🚀

**Autor:** Elias Andrade
**Empresa:** Replika AI Solutions
**Data:** 03 de Abril de 2025, 12:20 horas
**Status:** Funcional (Showcase & POC) / v0.3.1.4 (Conforme última API)

<p align="center">
  <img src="https://img.shields.io/badge/Built%20by-Elias%20Andrade%20%7C%20Replika%20AI-9cf?style=for-the-badge&logo=python" alt="Built by Elias Andrade | Replika AI Solutions">
  <img src="https://img.shields.io/badge/Architecture-Microservice%20%7C%20Async%20%7C%20API--Driven-orange?style=for-the-badge" alt="Architecture: Microservice | Async | API-Driven">
  <img src="https://img.shields.io/badge/Primary%20Tech-FastAPI%20%7C%20Tortoise%20ORM%20%7C%20SQLite-blueviolet?style=for-the-badge&logo=fastapi" alt="Tech: FastAPI | Tortoise ORM | SQLite">
</p>


---

## 📊 Dashboard de Métricas em Tempo Real: O Painel de Controle do Replika AI Message Broker 🩺

**Desenvolvido por:** Elias Andrade | Replika AI Solutions
**Foco:** Observabilidade e Monitoramento da API do Message Broker
**Status:** Funcional (Showcase & POC)

<p align="center">
  <img src="https://img.shields.io/badge/Component-Analytics_Dashboard-blue?style=for-the-badge&logo=grafana" alt="Component: Analytics Dashboard">
  <img src="https://img.shields.io/badge/Monitors-Replika_AI_Message_Broker-orange?style=for-the-badge" alt="Monitors: Replika AI Message Broker">
  <img src="https://img.shields.io/badge/Data-Real--Time-brightgreen?style=for-the-badge" alt="Data: Real-Time">
  <img src="https://img.shields.io/badge/Tech-Flask_|_Chart.js_|_API-black?style=for-the-badge&logo=flask" alt="Tech: Flask | Chart.js | API">
</p>

---

Olá novamente! Elias Andrade aqui. 👨‍💻 Além de construir o *core* do **Replika AI Message Broker**, uma parte crucial do desenvolvimento foi criar uma ferramenta de **observabilidade sob medida**: o **Dashboard de Métricas em Tempo Real**.

As imagens que você vê demonstram essa interface vital. **Não se trata de uma ferramenta genérica como Grafana ou Zabbix adaptada**, mas sim um painel **desenhado especificamente para fornecer insights profundos sobre a performance e o estado interno do *nosso* Message Broker**.

### 🤔 Por que um Dashboard Customizado?

Enquanto ferramentas genéricas são poderosas, elas muitas vezes exigem configuração complexa para extrair as métricas *realmente* relevantes para um sistema específico como um message broker. Nosso dashboard foi construído com um propósito claro:

1.  **Visibilidade Instantânea:** Oferecer um "raio-x" em tempo real da saúde do broker.
2.  **Métricas Chave Relevantes:** Focar nos indicadores que importam para um sistema de mensageria e sua API (mensagens pendentes, processadas, falhas, vazão de requisições, uso de recursos).
3.  **Diagnóstico Facilitado:** Ajudar a identificar rapidamente gargalos, picos de carga, erros e tendências de uso.
4.  **Demonstração de Capacidade:** Mostrar como integramos monitoramento eficaz diretamente em nossas soluções.

### ✨ Funcionalidades em Destaque (Visível nas Imagens)

O dashboard agrega informações críticas de forma visualmente intuitiva:

1.  **KPI Cards de Alto Impacto:** 🟧🟦🟥🟩🟪🟣<0xF0><0x9F><0xA7><0xBD>⬜️
    *   Visão rápida do estado atual com contadores grandes e cores semânticas.
    *   **Métricas Exibidas:** `PENDING MSGS` (carga atual na fila), `PROCESSING MSGS` (em processamento), `FAILED MSGS` (erros), `PROCESSED MSGS` (sucessos), `TOTAL REQS` (carga na API), `PROCESS CPU %` (uso de CPU do broker), `PROCESS MEM (MB)` (uso de memória), `UPTIME` (tempo de atividade).
    *   **Design:** Cards coloridos para identificação rápida do tipo de métrica e seu estado implícito (e.g., vermelho para falhas, laranja para pendências). Alguns layouts mostram versões simplificadas focando em métricas específicas.

2.  **Gráficos de Tendência Temporal:** 📈📉
    *   Visualização da evolução das métricas ao longo dos últimos N pontos de coleta (configurável).
    *   `Requests / Interval`: Mostra a taxa de requisições à API, ajudando a identificar picos de uso.
    *   `Message Status`: Acompanha a dinâmica das filas (pendentes vs processadas/falhadas), crucial para identificar gargalos ou problemas de processamento.
    *   `Performance (CPU/Mem)`: Gráfico com duplo eixo Y, correlacionando o uso de CPU (%) e Memória (MB) do processo do broker ao longo do tempo. Essencial para capacity planning e detecção de leaks ou sobrecarga.

3.  **Gráficos de Distribuição:** 📊🍩
    *   `Requests by Route`: Gráfico de barras (geralmente horizontal para melhor leitura dos nomes das rotas) mostrando quais endpoints da API são mais acessados. Útil para entender padrões de uso e otimizar rotas críticas.
    *   `Requests by Status Code`: Gráfico de rosca/pizza mostrando a distribuição dos códigos de status HTTP retornados pela API (2xx, 4xx, 5xx). Facilita a identificação rápida de taxas de erro.

4.  **Interface Clara e Responsiva:** ✨
    *   Tema escuro para conforto visual em ambientes NOC/Dev.
    *   Layout organizado em cards e seções de gráficos.
    *   Indicador "Live" ou status de erro/atualização na barra superior.
    *   (Implícito) Projetado para ser responsivo em diferentes tamanhos de tela.

### 🛠️ Como Funciona? (Arquitetura Simplificada)

Este dashboard é, na verdade, uma **aplicação web separada** (implementada em `webdashv2-clean.py` usando Flask, mas poderia ser FastAPI também) que atua como um **cliente da API principal do Message Broker**.

1.  **Coleta Agendada:** Uma thread em background faz login na API do Broker e busca periodicamente os dados do endpoint `/stats`.
2.  **Processamento e Armazenamento:** Os dados recebidos (estatísticas atuais e históricos) são processados e armazenados em memória (usando `deque` para históricos).
3.  **Servindo Dados para o Frontend:** Um endpoint na aplicação Flask (`/api/dashboard_data`) expõe esses dados processados em formato JSON.
4.  **Renderização no Frontend:** O HTML/JavaScript no navegador do usuário busca os dados desse endpoint (`/api/dashboard_data`) em intervalos regulares e atualiza os valores nos cards e os gráficos usando **Chart.js**.

### ✅ Importância e Utilidade

Um dashboard dedicado como este é **fundamental** para:

*   **Monitoramento Operacional (DevOps/SRE):** Acompanhar a saúde e performance do broker em produção.
*   **Debugging e Troubleshooting:** Identificar rapidamente a causa de problemas (ex: fila crescendo muito -> verificar consumidores; alto CPU -> investigar carga ou código).
*   **Análise de Performance:** Entender como o broker se comporta sob diferentes cargas e otimizar configurações ou recursos.
*   **Capacity Planning:** Prever necessidades futuras de recursos com base nas tendências de uso.
*   **Validação de Testes:** Monitorar o broker durante testes de carga (`geramensagem-v*-loop.py`) para validar performance e estabilidade.

### 🔧 Customização e Integração

Embora este dashboard específico seja focado no Message Broker, a **tecnologia subjacente (o Módulo Controlador de Dashboard da Replika AI)** é flexível.

*   **Configurabilidade:** A definição de quais métricas buscar, como exibi-las (cards, gráficos), cores, títulos, etc., pode ser controlada via configuração (JSON/API no módulo core), permitindo adaptar ou criar novos dashboards para outras APIs ou sistemas.
*   **Integração:** O dashboard consome uma API REST (`/stats`). Qualquer sistema que exponha métricas via API pode ter um dashboard similar construído com nosso módulo.

Este dashboard é um exemplo concreto de como aplicamos nossa expertise para criar não apenas o serviço principal, mas também as ferramentas essenciais para sua operação, monitoramento e otimização.

<img width="1920" alt="chrome_cMwygmFz5b" src="https://github.com/user-attachments/assets/988c28df-37dc-4bae-b048-394b77d9d103" />

<img width="409" alt="Cursor_vMCA7EwiQF" src="https://github.com/user-attachments/assets/f0598ea5-ec50-46e4-97ef-b31b8163580b" />

<img width="1920" alt="chrome_QYArQzVDpQ" src="https://github.com/user-attachments/assets/316705ac-35b9-495e-bc70-eeec39cd6a36" />

<img width="1920" alt="chrome_wafYhIgNc0" src="https://github.com/user-attachments/assets/4e85b72f-984f-4ebc-8b7f-ac51c9414278" />

<img width="1920" alt="chrome_HwPADchH2w" src="https://github.com/user-attachments/assets/87d95bd6-94cc-4abe-82c3-00bc1eeaff8e" />

<img width="1126" alt="chrome_7zT0Ey6QGS" src="https://github.com/user-attachments/assets/927b9ae2-ecd2-4ef7-b31d-83e38192b565" />

<img width="480" alt="chrome_qKGGdxiHC5" src="https://github.com/user-attachments/assets/8731db11-789b-4897-b159-0850eb98d34c" />

<img width="255" alt="chrome_MxtZeVZXfB" src="https://github.com/user-attachments/assets/7cf2401e-0549-4738-abe6-2c2b476802d1" />

<img width="1878" alt="AsPowerBar_tV9V5PaTes" src="https://github.com/user-attachments/assets/1456f264-aba4-4382-83f9-74577b09983b" />

<img width="1920" alt="chrome_MMmCeIRYsZ" src="https://github.com/user-attachments/assets/fd2f6128-42af-431f-8db9-2b9934777b1e" />

<img width="712" alt="chrome_cjI4lNStdk" src="https://github.com/user-attachments/assets/7249d64c-a7e4-472a-ae33-f77cc938bc2d" />

<img width="487" alt="chrome_gN1LOJRMvG" src="https://github.com/user-attachments/assets/b4358978-30e8-497c-b3aa-1029b3d01e3b" />

---
**Elias Andrade**
**Replika AI Solutions**
*(Contato via WhatsApp: +55 11 9 1335 3137)*

---

## 🎯 1. Introdução e Motivação

Este documento detalha a arquitetura, as decisões de design e as capacidades do **Replika AI Message Broker**, um sistema proprietário desenvolvido internamente na Replika AI Solutions.

A principal motivação para a criação deste broker foi a necessidade de **acelerar e padronizar a prototipagem, o deployment e a integração de soluções de Inteligência Artificial (IA), Machine Learning (ML) e automação (RPA)** dentro da nossa software house.

Enquanto soluções de mercado como RabbitMQ e Kafka são extremamente poderosas, elas frequentemente introduzem uma complexidade operacional e um conjunto de funcionalidades que excedem as necessidades de muitos dos nossos fluxos de trabalho, especialmente em fases de POC ou para integrações específicas. Buscamos uma solução que oferecesse:

1.  ⚡ **Alta Performance e Baixa Latência:** Essencial para pipelines de IA/ML e comunicação inter-serviços ágil.
2.  🧩 **Simplicidade e Controle:** Uma API clara, fácil de integrar e com controle total sobre o comportamento e otimizações.
3.  📊 **Observabilidade Integrada:** Um dashboard em tempo real para monitoramento da saúde e performance, crucial para MLOps/IAOps.
4.  🔒 **Segurança:** Mecanismos robustos de autenticação e controle de acesso.
5.  🚀 **Agilidade no Deploy:** Facilidade de implantação como um microserviço containerizado (Docker).
6.  💡 **Showcase de Capacidade:** Demonstrar a expertise técnica da Replika AI Solutions em construir soluções complexas e performáticas.

Este Message Broker, portanto, não é apenas uma ferramenta, mas um **ativo estratégico e um demonstrativo de notório saber técnico** em arquitetura de software, desenvolvimento full-cycle e operações de sistemas inteligentes (IAOps, MLOps, DevOps, DataOps).

## 💡 2. Conceitos Fundamentais

O Replika AI Message Broker é um **serviço intermediário** que facilita a comunicação assíncrona entre diferentes aplicações (produtores e consumidores) através de filas nomeadas.

**Funcionalidades Core Implementadas (v0.3.1.4):**

*   ✅ **Gerenciamento de Filas:** API RESTful e GraphQL para criar, listar e deletar filas.
*   📨 **Publicação Assíncrona:** Produtores enviam mensagens para filas específicas via API (REST/GraphQL).
*   📥 **Consumo Atômico:** Consumidores recuperam a mensagem mais antiga de uma fila ('pending'), que é atomicamente marcada como 'processing' (usando `SELECT FOR UPDATE` em transação).
*   👍👎 **ACK/NACK Explícito:** Consumidores *devem* confirmar (`/ack`) o processamento bem-sucedido (status -> 'processed') ou negar (`/nack`) o processamento (status -> 'failed' ou 'pending' se `requeue=True`).
*   🔑 **Autenticação JWT:** Acesso seguro à API via tokens de acesso e refresh.
*   ⏱️ **Rate Limiting:** Proteção contra abuso via SlowAPI (configurável, com fallback in-memory).
*   📊 **Monitoramento Real-Time:** Dashboard web (`webdashv2-clean.py`) que consome o endpoint `/stats` da API principal para visualização de métricas vitais.
*   📄 **Logging Estruturado:** Logs detalhados em JSON (arquivo) e formato colorido (console).
*   🍓 **Interface GraphQL:** API alternativa para interações com filas e mensagens.
*   🛡️ **SSL/HTTPS:** Geração automática de certificado auto-assinado para comunicação segura em desenvolvimento.
*   💾 **Persistência SQLite:** Uso do Tortoise ORM com backend SQLite para armazenamento de filas e mensagens.

**Status Atual (v0.3.1.4):** O broker é funcional, permitindo publicação, consumo atômico e confirmação (ACK/NACK). O dashboard fornece monitoramento em tempo real. Scripts de teste de carga demonstram a capacidade de lidar com múltiplas requisições concorrentes. É um POC robusto e um showcase funcional.

## 🏗️ 3. Decisões Arquiteturais e Tecnológicas (O "Como" e o "Porquê")

A escolha da stack tecnológica e dos padrões arquiteturais foi guiada pelos requisitos de performance, simplicidade, controle e observabilidade.

### 3.1. Base Assíncrona com FastAPI 🚀

*   **Como:** O núcleo da API (`message-broker-v2-clean.py`) é construído sobre o **FastAPI**.
*   **Porquê:**
    *   **Performance Nativa `async/await`:** Ideal para aplicações I/O bound como um message broker, capaz de lidar com milhares de conexões concorrentes eficientemente usando `asyncio` e `uvicorn`. Essencial para alto throughput.
    *   **Velocidade:** Um dos frameworks Python mais rápidos disponíveis.
    *   **Validação de Dados (Pydantic):** Definição clara de schemas de entrada/saída com validação automática, reduzindo boilerplate e aumentando a robustez.
    *   **Documentação Automática:** Geração interativa de documentação API (Swagger UI, ReDoc) a partir do código, facilitando a integração.
    *   **Ecossistema Moderno:** Bem integrado com outras bibliotecas assíncronas.

    <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"> <img src="https://img.shields.io/badge/AsyncIO-8A2BE2?style=flat-square" alt="AsyncIO"> <img src="https://img.shields.io/badge/Pydantic-E9769B?style=flat-square" alt="Pydantic">

### 3.2. Acesso a Dados com Tortoise ORM e SQLite 🐢💾

*   **Como:** A persistência de filas e mensagens utiliza o **Tortoise ORM** com um backend **SQLite**.
*   **Porquê:**
    *   **Tortoise ORM (Async):** ORM assíncrono que se integra perfeitamente com o `asyncio` e FastAPI, evitando bloqueios durante operações de banco de dados. Oferece uma API inspirada no Django ORM, familiar para muitos desenvolvedores Python. Permite a definição clara de modelos e relações (`Queue`, `Message`).
    *   **SQLite (Simplicidade Inicial):** Para a v1/POC, SQLite oferece extrema simplicidade de setup (um único arquivo), sendo ideal para desenvolvimento, testes e cenários de baixo/médio volume ou onde a complexidade de um servidor DB externo não é desejada inicialmente. *Facilita o deploy como um microserviço autocontido*.
    *   **Transações:** O uso explícito de `async with in_transaction("default") as tx:` e `select_for_update()` na lógica de consumo garante a atomicidade e previne race conditions onde múltiplos consumidores poderiam pegar a mesma mensagem.

    <img src="https://img.shields.io/badge/Tortoise%20ORM-0C9D58?style=flat-square" alt="Tortoise ORM"> <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite">

    *(**Nota:** Para produção em larga escala, a migração para um DB assíncrono mais robusto como PostgreSQL (com `asyncpg`) seria um passo natural, suportado pelo Tortoise ORM).*

### 3.3. Autenticação com JWT (JSON Web Tokens) 🔑

*   **Como:** Implementado usando a biblioteca `python-jose`. Geração de `access_token` (curta duração) e `refresh_token` (longa duração) no endpoint `/login`. Validação via `Depends(get_current_user)` e `Depends(validate_refresh_token)` nos endpoints protegidos.
*   **Porquê:**
    *   **Padrão da Indústria:** Amplamente adotado para autenticação de APIs stateless.
    *   **Stateless:** O servidor não precisa armazenar o estado da sessão do token (apenas a chave secreta), facilitando a escalabilidade horizontal.
    *   **Segurança:** Assinatura digital garante a integridade e autenticidade do token.
    *   **Flexibilidade:** Permite expiração e uso de refresh tokens para gerenciar a vida útil da sessão.

    <img src="https://img.shields.io/badge/JWT-black?style=flat-square&logo=jsonwebtokens&logoColor=white" alt="JWT"> <img src="https://img.shields.io/badge/python--jose-D33F49?style=flat-square" alt="python-jose">

    *(**Alerta:** A implementação atual usa credenciais `admin`/`admin` hardcoded para login. **FUNDAMENTAL** substituir por um sistema seguro de hash de senhas (ex: `passlib`) e lookup de usuário em produção).*

### 3.4. Rate Limiting com SlowAPI ⏱️

*   **Como:** Utiliza a biblioteca `slowapi` integrada como um middleware FastAPI. Configurado com limites padrão e limites específicos mais altos para endpoints de alto tráfego (publish/consume/ack/nack). O backend padrão é in-memory (mas projetado para usar Redis se disponível).
*   **Porquê:**
    *   **Proteção contra Abuso/DoS:** Previne que clientes mal-intencionados ou com bugs sobrecarreguem a API com requisições excessivas.
    *   **Controle de Recursos:** Garante uso justo dos recursos do servidor entre diferentes clientes.
    *   **Integração Simples:** `slowapi` integra-se facilmente com FastAPI.

    <img src="https://img.shields.io/badge/Rate%20Limit-SlowAPI-blue?style=flat-square" alt="SlowAPI">

### 3.5. Abordagem de Microserviço e Dockerização 🐳

*   **Como:** O Broker API é projetado como um serviço independente (`message-broker-v2-clean.py`) que pode ser executado em seu próprio processo/container. O Dashboard (`webdashv2-clean.py`) é um *outro* serviço que consome a API do broker.
*   **Porquê:**
    *   **Desacoplamento:** Permite que o broker evolua independentemente de outros serviços que o utilizam.
    *   **Escalabilidade Independente:** Instâncias do broker podem ser escaladas horizontalmente conforme a demanda de mensageria aumenta, sem afetar outros componentes.
    *   **Facilidade de Deploy (Docker):** Embora o `Dockerfile` não esteja presente nos arquivos listados, a estrutura autocontida facilita a containerização, simplificando o deploy em diferentes ambientes (dev, staging, prod).

    <img src="https://img.shields.io/badge/Docker--Ready-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker Ready"> <img src="https://img.shields.io/badge/Microservice-purple?style=flat-square" alt="Microservice">

### 3.6. Observabilidade via Dashboard Real-Time 📊📈

*   **Como:** Um serviço web separado (`webdashv2-clean.py`), construído com **Flask** (poderia ser FastAPI também), periodicamente busca dados do endpoint `/stats` da API do Broker. Usa **Chart.js** para renderizar gráficos no frontend (HTML/CSS/JS).
*   **Porquê:**
    *   **Visibilidade Operacional:** Essencial para entender o que está acontecendo dentro do broker em tempo real (carga, filas pendentes, uso de recursos).
    *   **Diagnóstico Rápido:** Ajuda a identificar gargalos, picos de uso ou erros rapidamente.
    *   **Tomada de Decisão:** Informa decisões sobre escalabilidade, otimização ou manutenção.
    *   **Showcase:** Demonstra a capacidade de construir interfaces de monitoramento customizadas.

    <img src="https://img.shields.io/badge/Dashboard-Flask-black?style=flat-square&logo=flask&logoColor=white" alt="Flask"> <img src="https://img.shields.io/badge/Charting-Chart.js-FF6384?style=flat-square&logo=chartdotjs&logoColor=white" alt="Chart.js">

### 3.7. Flexibilidade com GraphQL (Strawberry) 🍓

*   **Como:** Implementado usando **Strawberry** e integrado ao FastAPI via `GraphQLRouter`. Define tipos GraphQL (`QueueGQL`, `MessageGQL`) e resolvers (`QueryGQL`, `MutationGQL`) que mapeiam para as operações do broker.
*   **Porquê:**
    *   **API Alternativa:** Oferece aos clientes uma forma diferente de interagir com o broker, permitindo que eles peçam *exatamente* os dados que precisam.
    *   **Experiência do Desenvolvedor:** Ferramentas como Apollo Sandbox (configurado) facilitam a exploração e o teste da API GraphQL.
    *   **Demonstração Técnica:** Mostra proficiência em múltiplas tecnologias de API.

    <img src="https://img.shields.io/badge/GraphQL-Strawberry-E10098?style=flat-square&logo=graphql&logoColor=white" alt="Strawberry GraphQL">

### 3.8. Comunicação Segura com SSL/TLS 🛡️

*   **Como:** O servidor Uvicorn é configurado para usar arquivos `cert.pem` e `key_nopass.pem`. Uma função `generate_self_signed_cert` está incluída para criar certificados auto-assinados para desenvolvimento local (`localhost`).
*   **Porquê:**
    *   **Confidencialidade e Integridade:** Criptografa a comunicação entre clientes e o broker via HTTPS, protegendo os dados em trânsito.
    *   **Requisito Básico:** Essencial para qualquer API que lide com autenticação ou dados potencialmente sensíveis.

    <img src="https://img.shields.io/badge/HTTPS-Enabled-brightgreen?style=flat-square" alt="HTTPS Enabled">

## 🔩 4. Componentes Principais do Sistema

1.  **`message-broker-v2-clean.py` (API Core):** ⚙️
    *   **Responsabilidade:** Ponto central de toda a lógica do broker. Recebe requisições, valida dados (Pydantic), interage com o DB (Tortoise), gerencia autenticação (JWT), aplica rate limiting (SlowAPI), define endpoints REST e GraphQL (Strawberry), e lida com logging.
    *   **Execução:** Rodado via `uvicorn` com suporte a HTTPS.

2.  **`webdashv2-clean.py` (Dashboard):** 📊
    *   **Responsabilidade:** Aplicação web independente (Flask) que atua como *cliente* da API do Broker. Faz login, busca periodicamente dados do `/stats` e renderiza uma interface HTML com gráficos (Chart.js) para visualização.
    *   **Execução:** Rodado via servidor de desenvolvimento Flask (ou WSGI como Waitress/Gunicorn).

3.  **`databases/message_broker_v3.db` (Banco de Dados):** 💾
    *   **Responsabilidade:** Arquivo SQLite que armazena o estado persistente das filas (`queues` table) e das mensagens (`messages` table), incluindo status e timestamps.

4.  **Scripts Utilitários e Clientes:** 🐍🛠️
    *   **`geramensagem*.py`:** Clientes de exemplo para publicar mensagens, incluindo testes de stress com threads.
    *   **`coletamensagem*.py`:** Clientes de exemplo para consumir mensagens e enviar ACKs.
    *   **`dbfix*.py`:** Scripts para aplicar alterações de schema no DB SQLite diretamente.
    *   **`docgen*.py`:** Scripts para geração automática de documentação.

## 🌊 5. Fluxo de Dados Conceitual

1.  **Autenticação:** 🔑 Cliente envia `username`+`password` para `/login`. API valida (atualmente hardcoded) e retorna `access_token` e `refresh_token`.
2.  **Publicação:** 📨 Cliente envia POST para `/queues/{queue_name}/messages` com `content` no corpo e `Authorization: Bearer <access_token>` no header.
3.  **Broker (Publicação):** API valida token, encontra/cria a Queue no DB (Tortoise), cria um novo registro `Message` com `status='pending'` e `queue_id` correto, salva no DB. Retorna `message_id`.
4.  **(Opcional) Notificação SSE:** Broker (via background task) publica evento "new_message" no canal Redis `sse:{queue_name}` (se Redis estiver configurado).
5.  **Consumo:** 📥 Cliente (worker) envia GET para `/queues/{queue_name}/messages/consume` com token de acesso.
6.  **Broker (Consumo):** API valida token, encontra a Queue, inicia uma **transação DB**, busca a mensagem 'pending' mais antiga (`ORDER BY created_at LIMIT 1`) **com `SELECT FOR UPDATE`**, marca seu `status='processing'` e `updated_at`, salva as alterações, **commita a transação**. Retorna os detalhes da mensagem (ID, content, etc.). Se nenhuma mensagem 'pending' for encontrada (ou estiverem lockadas), retorna `null` (200 OK).
7.  **Processamento:** ⚙️ Cliente worker recebe os detalhes da mensagem e processa o `content`.
8.  **Confirmação (ACK):** ✅ Se o processamento for bem-sucedido, cliente envia POST para `/messages/{message_id}/ack` com token.
9.  **Broker (ACK):** API valida token, encontra a mensagem *apenas se* `status='processing'`, atualiza `status='processed'` e `updated_at`. Publica evento SSE "message_processed". Retorna sucesso.
10. **Falha (NACK):** ❌ Se o processamento falhar, cliente envia POST para `/messages/{message_id}/nack` (com `requeue=True` ou `False`).
11. **Broker (NACK):** API valida token, encontra a mensagem *apenas se* `status='processing'`, atualiza `status='failed'` (ou 'pending' se `requeue=True`) e `updated_at`. Publica evento SSE "message_failed"/"message_requeued". Retorna sucesso.

## ⚡ 6. Considerações de Performance

*   **Async I/O:** O uso de `asyncio`, FastAPI, Tortoise ORM e `aiosqlite` (implícito pelo Tortoise para SQLite) garante que operações de rede e banco de dados não bloqueiem o event loop, permitindo alta concorrência.
*   **Throughput:** Projetado para alto throughput na publicação e consumo, limitado principalmente pela performance do backend DB (SQLite será um gargalo sob carga muito alta) e pelos recursos do servidor (CPU/RAM/Rede). Os scripts de teste de stress (`geramensagem-v*-loop.py`) com múltiplos workers demonstram a capacidade de lidar com carga concorrente.
*   **Consumo Atômico:** A lógica de transação com `SELECT FOR UPDATE` no consumo é crucial para a corretude, mas introduz um pequeno overhead e potencial de lock de curta duração no DB.
*   **Indexação:** Índices definidos nos modelos Tortoise (`Queue.name`, `Message.status`, `Message.created_at`, composto `Message.queue_id, status, created_at`) são vitais para a performance das queries de busca de filas e consumo de mensagens.

## 🛡️ 7. Considerações de Segurança

*   **Autenticação:** JWT fornece um mecanismo robusto, mas a segurança depende da proteção da `JWT_SECRET_KEY` e da implementação segura da validação de credenciais no `/login` (o ponto fraco atual).
*   **Autorização:** A implementação atual é simples (qualquer usuário autenticado pode fazer qualquer coisa). Um sistema de roles/permissões seria necessário para cenários mais complexos.
*   **Rate Limiting:** Protege contra DoS básicos e abuso. A configuração dos limites deve ser ajustada conforme o caso de uso.
*   **HTTPS/SSL:** Essencial para proteger dados em trânsito. O uso de certificados auto-assinados é **apenas para desenvolvimento**. Produção exige certificados válidos (e.g., Let's Encrypt).
*   **Validação de Input:** Pydantic (via FastAPI) e Strawberry (para GraphQL) fornecem validação robusta dos dados de entrada, prevenindo muitos tipos de ataques baseados em input malformado.
*   **Sanitização de Filename:** O endpoint `/logs/{filename}` usa `secure_filename` para mitigar riscos de directory traversal.

## ✨ 8. Vantagens para Replika AI Solutions

*   **Aceleração de Projetos IA/ML:** Fornece um mecanismo de comunicação desacoplado e padronizado, simplificando a construção de pipelines complexos.
*   **Ferramenta Interna Controlada:** Controle total sobre funcionalidades, otimizações e integrações futuras.
*   **Showcase Técnico:** Demonstra capacidade em arquitetura assíncrona, APIs modernas, ORMs, segurança e observabilidade.
*   **Base para Soluções Customizadas:** Pode ser adaptado ou estendido facilmente para necessidades específicas de clientes.
*   **Redução de Complexidade:** Alternativa mais simples (inicialmente) a brokers mais complexos para certos cenários.

## 🎯 9. Casos de Uso Potenciais

*   **Pipelines de Dados IA/ML:** Comunicação entre etapas de coleta, pré-processamento, treinamento, inferência e pós-processamento.
*   **Comunicação entre Microsserviços:** Hub central para troca de eventos e comandos.
*   **Processamento Assíncrono de Tarefas:** Filas para tarefas de longa duração (envio de emails, processamento de imagens/vídeos, geração de relatórios).
*   **Webhooks:** Fila para processar webhooks recebidos de serviços externos.
*   **Sistemas de Notificação:** Gerenciamento de notificações a serem enviadas a usuários ou sistemas.
*   **Integração de Aplicações Legadas:** Interface moderna para sistemas mais antigos publicarem/consumirem dados.

## 🧭 10. Status Atual e Evolução Futura

*   **Status:** O Message Broker V1 (v0.3.1.4 conforme API) é um **Proof of Concept (POC) funcional e um showcase tecnológico avançado**. As funcionalidades core de publicação, consumo atômico seguro (com lock e transação) e ACK/NACK estão implementadas e funcionais. A API REST, GraphQL e o Dashboard de monitoramento estão operacionais. Testes de stress demonstram capacidade de processamento concorrente.
*   **Próximos Passos e Melhorias Potenciais:**
    *   **Backend de Persistência Robusto:** Migrar de SQLite para PostgreSQL (com `asyncpg`) ou outro DB relacional/NoSQL assíncrono para escalabilidade em produção.
    *   **Backend Redis para Filas:** Implementar opção de usar Redis (além do DB relacional) para armazenamento de mensagens em memória, visando maior performance para filas voláteis.
    *   **Mecanismos de Consumo Avançados:**
        *   Suporte a **long polling** ou **WebSockets** para consumo mais eficiente (reduzir polling constante).
        *   Implementar **push (webhooks)** para consumidores registrados.
    *   **Retries e Dead-Letter Queues (DLQ):** Lógica para tentar reprocessar mensagens que falharam (NACK'd) e movê-las para uma DLQ após N tentativas.
    *   **Clustering e Alta Disponibilidade (HA):** Arquitetura para múltiplas instâncias do broker trabalharem juntas.
    *   **Segurança Aprimorada:** Implementar hash de senhas real, roles/permissões granulares.
    *   **Dashboard Mais Interativo:** Adicionar filtros, controles (ex: limpar fila) e mais opções de visualização.
    *   **SDKs Clientes:** Desenvolver bibliotecas cliente (Python, etc.) para facilitar a integração.
    *   **Documentação Aprimorada:** Expandir a documentação com mais exemplos e detalhes.


---

## ✨ Core Concept: O Que é o Replika AI Message Broker?

Em essência, este é um **microserviço de message broker** implementado em Python usando **FastAPI**. Ele permite que diferentes aplicações (produtores) enviem mensagens para filas nomeadas, e outras aplicações (consumidores) recebam essas mensagens de forma assíncrona.

Funcionalidades Chave:

*   ✅ **Publicação e Consumo Assíncronos:** Utiliza `async/await` do Python para operações não bloqueantes.
*   🚀 **Alto Throughput:** Projetado com técnicas de paralelismo (conceitual e via concorrência do FastAPI/Uvicorn) para lidar com um grande volume de mensagens.
*   🔐 **Autenticação via JWT:** Garante que apenas clientes autenticados possam interagir com o broker.
*   ⏱️ **Rate Limiting (SlowAPI):** Protege o broker contra abuso e garante uso justo dos recursos.
*   📊 **Dashboard de Analytics Real-Time:** Uma interface web integrada (construída com HTML/CSS/JS e servida pelo FastAPI/Jinja2) que exibe métricas vitais do broker em tempo real.
*   💾 **Persistência Simples (Opcional):** Configurado inicialmente com SQLite via Tortoise ORM para persistência básica de filas e metadados (facilmente extensível).
*   🧩 **API RESTful Clara:** Endpoints bem definidos para login, gerenciamento de filas (criação implícita), publicação e (futuramente) consumo de mensagens.
*   🐳 **Dockerizado:** Pronto para ser empacotado e distribuído como um container Docker para deploy facilitado.

## 🧠 Showcase de Expertise: Além do Código

Este projeto não é apenas sobre escrever um Message Broker. É uma demonstração prática e integrada das minhas competências como **Arquiteto de Soluções Python Full Stack e Full Cycle**, abrangendo diversas disciplinas essenciais no desenvolvimento de software moderno e operações de sistemas inteligentes:

*   **🐍 Desenvolvimento Backend Avançado (Python/FastAPI):** Demonstra proficiência em criar APIs performáticas, assíncronas, seguras e bem estruturadas. Uso de tipagem, Pydantic para validação, e boas práticas de desenvolvimento.
*   **🏗️ Arquitetura de Microserviços:** Concepção e implementação de um componente desacoplado e focado em uma única responsabilidade (mensageria).
*   **☁️ DevOps & Infraestrutura:** Design para containerização (Docker), preocupação com deploy, logging (visível nos screenshots), configuração e monitoramento básico (uptime).
*   **📊 DataOps & Observabilidade:** A criação do dashboard de analytics em tempo real é um pilar central, mostrando a importância de monitorar a saúde e performance de sistemas críticos. Coleta e visualização de métricas como vazão, latência (implícita), uso de recursos (CPU/Mem) e estado das filas.
*   **🔒 Segurança de Aplicações:** Implementação de mecanismos essenciais como autenticação (JWT) e controle de acesso (rate limiting), além do uso de SSL/TLS (certificados mencionados nos logs).
*   **🔄 MLOps/IAOps (Contexto Estratégico):** Embora o broker em si não execute modelos de ML/AI, ele é projetado como uma peça *fundamental* de infraestrutura para habilitar pipelines de MLOps/IAOps, facilitando a comunicação entre etapas de treinamento, inferência, coleta de dados e monitoramento de modelos em produção. Ele agiliza o *deployment* dessas soluções.
*   **🎨 Frontend (Dashboard):** Capacidade de criar interfaces de usuário funcionais e informativas usando tecnologias web padrão (HTML/CSS/JS) integradas ao backend Python.

Este projeto consolida conhecimentos teóricos e práticos, demonstrando a capacidade de **conceber, projetar, implementar, proteger e monitorar** uma solução de software complexa e de missão crítica, do início ao fim.

## 🏛️ Arquitetura e Filosofia de Design

A arquitetura é centrada na simplicidade, performance e manutenibilidade:

1.  **FastAPI como Núcleo:** Escolhido pela sua performance nativa com `asyncio`, validação automática de dados com Pydantic, geração de documentação interativa (Swagger/ReDoc), e um ecossistema crescente.
2.  **Operações Assíncronas:** Todas as operações de I/O (rede, e potencialmente disco no futuro) são projetadas para serem não bloqueantes, permitindo que o servidor lide com muitas conexões e tarefas concorrentemente.
3.  **Microserviço Autocontido:** O broker roda como um processo independente, minimizando dependências externas (além do Python e suas libs).
4.  **Estado Gerenciado Internamente:** Mantém o estado das filas e mensagens em memória (com persistência opcional para metadados), otimizado para velocidade.
5.  **API Simples e Intuitiva:** Foco em endpoints claros para as operações essenciais de um broker.
6.  **Observabilidade Integrada:** O dashboard não é um 'afterthought', mas uma parte integral do design, fornecendo feedback imediato sobre o comportamento do sistema.

## 💻 Stack Tecnológica Principal

*   **Linguagem:** Python 3.10+
*   **Framework Web/API:** FastAPI
*   **Servidor ASGI:** Uvicorn
*   **ORM (Opcional):** Tortoise ORM (para SQLite)
*   **Validação de Dados:** Pydantic (integrado ao FastAPI)
*   **Autenticação:** PyJWT
*   **Rate Limiting:** SlowAPI
*   **Templating (Dashboard):** Jinja2
*   **Containerização:** Docker
*   **Banco de Dados (Default):** SQLite

## 📊 Dashboard de Analytics em Tempo Real: Um Mergulho Profundo

As imagens de showcase demonstram a capacidade do dashboard integrado. Ele oferece uma visão instantânea da saúde e performance do broker:

*   **KPIs Principais (Cards):**
    *   `PENDING MSGS`: Mensagens aguardando processamento na(s) fila(s) (indica carga/backlog). 🟧
    *   `PROCESSING MSGS`: Mensagens atualmente sendo processadas (se aplicável a lógicas futuras). 🟦
    *   `FAILED MSGS`: Mensagens que falharam no processamento (requer atenção). 🟥
    *   `PROCESSED MSGS`: Total de mensagens processadas com sucesso. 🟩
    *   `TOTAL REQS`: Número total de requisições recebidas pela API do broker. 🟪
    *   `PROCESS CPU %`: Uso atual da CPU pelo processo do broker. 🟣
    *   `PROCESS MEM (MB)`: Uso atual de memória RAM pelo processo. cyan
    *   `UPTIME`: Tempo desde que o processo do broker foi iniciado. ⬜️

*   **Gráficos Temporais (Últimos N Pontos):**
    *   `Requests / Interval`: Mostra a taxa de chegada de requisições ao longo do tempo (identifica picos de carga). 📈
    *   `Message Status`: Visualiza a evolução das mensagens pendentes, processadas, etc. (mostra fluxo e gargalos). 📊
    *   `Performance`: Plota o uso de CPU e Memória ao longo do tempo (ajuda a correlacionar carga com uso de recursos). ⚙️

*   **Distribuição Atual:**
    *   `Requests by Route`: Gráfico de barras mostrando quais endpoints da API são mais acessados. 📊
    *   `Requests by Status Code`: Gráfico de rosca (Donut Chart) mostrando a distribuição dos códigos de status HTTP retornados (2xx, 4xx, 5xx), útil para identificar erros. 🍩

Este nível de observabilidade é crucial para operar e otimizar um sistema de mensageria em produção.

## 🔐 Segurança Implementada

*   **Autenticação JWT:** Clientes devem primeiro obter um token JWT (ex: via endpoint `/login`) e incluí-lo em requisições subsequentes para endpoints protegidos (como `/publish`). Isso garante que apenas entidades autorizadas possam interagir com o broker.
*   **Rate Limiting (SlowAPI):** Limita o número de requisições que um cliente pode fazer em um determinado período (ex: 100/minuto), prevenindo ataques de negação de serviço (DoS) ou uso abusivo dos recursos. A implementação atual usa um backend em memória.
*   **SSL/TLS:** Os logs indicam a configuração para uso de certificados SSL (`cert.pem`, `key_nopass.pem`), permitindo comunicação segura via HTTPS.

## 🚀 Performance e Throughput

O design foca em maximizar o número de mensagens que podem ser publicadas e (eventualmente) consumidas por segundo:

*   **FastAPI + Uvicorn:** Uma combinação conhecida por sua alta performance em benchmarks de IO-bound.
*   **AsyncIO:** Permite lidar com milhares de conexões concorrentes eficientemente.
*   **Código Otimizado:** Busca por implementações eficientes nas operações core de enfileiramento/desenfileiramento (atualmente em memória para velocidade máxima).

## 📈 Casos de Uso e Valor Estratégico para Replika AI

*   **Prototipagem Rápida de IA/ML:** Permite que diferentes componentes de um pipeline (coleta de dados, pré-processamento, inferência, pós-processamento) se comuniquem de forma desacoplada e assíncrona.
*   **Ingestão de Dados:** Pode servir como um ponto de entrada robusto para coletar dados de diversas fontes antes de processá-los ou armazená-los.
*   **Comunicação Inter-Serviços:** Um hub centralizado para microserviços trocarem informações sem acoplamento direto.
*   **Webhooks e Notificações:** Gerenciar filas de eventos ou notificações a serem processadas.
*   **Padronização:** Oferece uma ferramenta de mensageria padronizada e controlada para uso nos projetos da empresa.

## ▶️ Como Usar (Conceitual)

A interação típica com o broker via API (conforme demonstrado no log do cliente) seria:

1.  **Autenticar:** Enviar credenciais para um endpoint de login (`/login`) para obter um token JWT.
2.  **Verificar/Criar Fila:** Tentar publicar em uma fila (`/queues/{queue_name}/messages`). Se a fila não existir, o broker pode criá-la implicitamente (ou um endpoint de gerenciamento pode ser usado).
3.  **Publicar Mensagem:** Enviar uma requisição POST para o endpoint da fila com o conteúdo da mensagem no corpo e o token JWT no header de autorização.
4.  **(Futuro) Consumir Mensagem:** Um cliente consumidor faria requisições (provavelmente GET ou PULL) a um endpoint específico para receber mensagens da fila.

*(Nota: Este README não inclui o código completo de exemplo do cliente, mas descreve o fluxo.)*

## 🧭 Status Atual e Próximos Passos

*   **Status:** O projeto é um **Proof of Concept (POC) funcional e um showcase tecnológico**. O broker é capaz de receber mensagens autenticadas via JWT, aplicar rate limiting, armazená-las em filas em memória e exibir analytics em tempo real no dashboard.
*   **Próximos Passos (Ideias):**
    *   Implementar a lógica de **consumo** de mensagens (diferentes estratégias: pull, push/webhook).
    *   Adicionar mais **backends de persistência** (Redis, PostgreSQL, etc.) usando adaptadores.
    *   Implementar **estratégias de fila** mais avançadas (prioridade, dead-letter queues).
    *   Melhorar a **interface do dashboard** com mais filtros, controles e opções de visualização.
    *   Implementar **clustering** para alta disponibilidade e escalabilidade.
    *   Refinar o **modelo de segurança** e gerenciamento de usuários/permissões.
    *   Criar **SDKs/Clientes** em Python (e outras linguagens) para facilitar a integração.

## ©️ Licença

Este projeto é software proprietário da **Replika AI Solutions**. Todos os direitos reservados.

---
