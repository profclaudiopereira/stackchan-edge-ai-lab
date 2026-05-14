![StackChan Edge AI Lab](assets/banners/stackchan-edge-ai-lab-overview.png)

# stackchan-edge-ai-lab

Experimentos de Edge AI conversacional utilizando StackChan, Arduino UNO Q, OpenAI e Linux Embarcado.

---

# Visão Geral

Este projeto documenta, passo a passo, a criação de um laboratório pessoal de IA conversacional focado em:

* Voice AI
* Edge AI
* Sistemas embarcados
* ESP32-S3
* Integração OpenAI
* Conversações em PT-BR e inglês
* Arquiteturas híbridas de IA
* IoT conversacional
* Interação humano-computador

O objetivo NÃO é apenas construir um robô.

O principal objetivo é criar uma plataforma experimental prática e didática para:

* estudos técnicos
* produtividade em engenharia
* interfaces conversacionais
* interação bilíngue (Português/Inglês)
* experimentação em Edge AI
* futuras integrações IoT

---

# Hardware Principal

## StackChan

Documentação oficial:

https://docs.m5stack.com/en/StackChan

StackChan é um robô de IA desktop open-source baseado em ESP32-S3.

Principais características:

* ESP32-S3
* display
* microfones duplos
* speaker
* servos
* Wi‑Fi/Bluetooth
* interação conversacional
* ecossistema open-source

O StackChan será utilizado como:

* terminal conversacional
* interface física de voz
* dispositivo de interação com IA
* plataforma experimental de embodied AI

---

## Arduino UNO Q

Documentação oficial:

https://www.arduino.cc/product-uno-q

O Arduino UNO Q é uma moderna plataforma híbrida embarcada combinando:

* sistema Linux
* processamento Qualcomm
* aceleração embarcada de IA
* MCU em tempo real
* Wi‑Fi/Bluetooth
* suporte multimídia

O UNO Q atuará inicialmente como:

* backend de IA
* gateway OpenAI
* servidor de orquestração conversacional
* plataforma experimental

---

# Arquitetura Inicial

```text
StackChan (ESP32-S3)
        ↓
Arduino UNO Q
        ↓
OpenAI APIs
```

O objetivo inicial é manter a arquitetura SIMPLES.

No início, o foco será:

* qualidade de voz
* baixa latência
* suporte PT-BR
* suporte inglês
* experiência conversacional
* streaming
* estabilidade

---

# Por Que Este Projeto?

O projeto foi criado para explorar:

* Edge AI
* Voice AI
* Hybrid AI
* Sistemas conversacionais
* Linux embarcado
* Sistemas ESP32
* Interação humano-computador
* Produtividade técnica utilizando voz

Exemplos de uso:

* fazer perguntas técnicas por voz
* estudar sistemas embarcados
* discutir arquitetura de firmware
* praticar inglês técnico
* interagir hands-free durante trabalhos de eletrônica

---

# Filosofia do Projeto

Este repositório segue um princípio MUITO importante:

## Começar simples.

Em vez de modificar tudo imediatamente, o projeto irá primeiro:

1. Testar o firmware original do StackChan
2. Documentar a experiência do fabricante
3. Medir limitações e pontos fortes
4. Criar um baseline técnico
5. Evoluir gradualmente

Esta abordagem melhora:

* reprodutibilidade
* qualidade do aprendizado
* debugging
* qualidade da documentação
* comparações futuras

---

# Fases de Desenvolvimento

# Fase 0 — Preparação do Projeto

Fase atual.

Objetivos:

* preparar repositório GitHub
* preparar documentação
* preparar Arduino UNO Q
* estudar APIs OpenAI
* definir arquitetura

---

# Fase 1 — Avaliação Original do StackChan

IMPORTANTE:

O StackChan será PRIMEIRO testado exatamente como entregue pelo fabricante.

Esta fase documentará:

* unboxing
* versão do firmware
* primeiro boot
* configuração Wi‑Fi
* qualidade de voz
* testes PT-BR
* testes em inglês
* latência
* qualidade do speaker
* qualidade do microfone
* qualidade conversacional
* limitações

Nenhuma modificação importante inicialmente.

O objetivo é entender a plataforma original antes da customização.

---

# Fase 2 — Integração OpenAI

Objetivos:

* conectar StackChan à OpenAI
* avaliar qualidade conversacional
* testar interação bilíngue
* avaliar latência
* comparar abordagens de streaming

Tecnologias planejadas:

* Python
* FastAPI
* WebSocket
* OpenAI SDK

---

# Fase 3 — Backend IA UNO Q

Objetivos:

* memória conversacional
* persistência de contexto
* camada de orquestração
* gerenciamento de prompts
* assistente bilíngue
* futuros experimentos locais de IA

---

# Fase 4 — Hybrid AI e IoT

Fase futura.

Possíveis experimentos:

* MQTT
* sensores
* automação
* Home Assistant
* IoT distribuído
* modelos locais de IA
* inferência híbrida cloud/local

---

# Estrutura Inicial do Repositório

```text
stackchan-edge-ai-lab/
├── README.md
├── docs/
│   ├── 00-overview/
│   ├── 01-unboxing/
│   ├── 02-stock-firmware/
│   ├── 03-initial-tests/
│   ├── 04-ptbr-tests/
│   ├── 05-english-tests/
│   ├── 06-openai-integration/
│   ├── 07-unoq-backend/
│   ├── 08-hybrid-ai/
│   └── future/
├── backend/
├── firmware/
├── hardware/
├── voice/
└── experiments/
```

---

# Objetivos Técnicos Iniciais

## Interação por Voz

* suporte PT-BR
* suporte inglês
* baixa latência
* interação natural

---

## Objetivos Educacionais

* melhorar inglês técnico
* estudar sistemas embarcados
* estudar Edge AI
* documentar experimentos publicamente

---

## Objetivos de Engenharia

* arquitetura modular
* ambiente reproduzível
* design escalável
* experimentação prática

---

# Tecnologias Planejadas

## Sistemas Embarcados

* ESP32-S3
* Linux Embarcado
* ecossistema Arduino

---

## Software

* Python
* FastAPI
* WebSocket
* asyncio
* OpenAI SDK
* Git/GitHub

---

## IA

* APIs OpenAI
* voice AI
* interação em streaming
* futuros experimentos híbridos de IA

---

# Notas Importantes

Este projeto é intencionalmente incremental.

As prioridades são:

1. estabilidade
2. qualidade de voz
3. simplicidade
4. qualidade da documentação
5. aprendizado

O projeto NÃO está tentando construir uma plataforma robótica complexa imediatamente.

O principal foco é:

* interação conversacional
* produtividade técnica
* experimentação
* valor educacional

---

# Configuração GitHub

## Criar repositório localmente

```bash
git init
```

---

## Adicionar arquivos

```bash
git add .
```

---

## Primeiro commit

```bash
git commit -m "Initial project structure and README"
```

---

## Conectar repositório GitHub

```bash
git remote add origin https://github.com/YOUR_USER/stackchan-edge-ai-lab.git
```

---

## Push repositório

```bash
git branch -M main
git push -u origin main
```

---

# Primeiras Tarefas Sugeridas

## Antes da Chegada do StackChan

* preparar Arduino UNO Q
* instalar ambiente Python
* configurar Git e SSH
* testar APIs OpenAI
* organizar estrutura do repositório
* planejar documentação

---

# Ideias Futuras

Possíveis direções futuras:

* inferência local de IA
* otimização de streaming de voz
* detecção wake-word
* experimentos embodied AI
* integrações com sensores
* integração Home Assistant
* assistente bilíngue de engenharia
* benchmarks Edge AI

---

# Licença

Projeto atualmente em avaliação.

Possíveis opções futuras:

* MIT
* Apache 2.0

---

# Notas Finais

Este repositório busca se tornar:

* plataforma de aprendizado
* referência prática de engenharia
* laboratório conversacional de Edge AI
* projeto técnico bilíngue de documentação

O projeto evoluirá incrementalmente e será documentado passo a passo.
