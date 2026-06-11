# FolderandFileOperator
Operador de estrutura de diretórios 

# 📂 Operador de Pastas e Arquivos 

> **Ferramenta Corporativa de Filtro Temporal e Replicação Estruturada para Migração Digital.**

O Operador de Pastas e Arquivos é um aplicativo desktop desenvolvido em Electron para simplificar e automatizar o processo de migração de arquivos em larga escala. Ele foi projetado especificamente para operadores que precisam mapear acervos digitais e transferir estruturas de diretórios aplicando filtros baseados na data de modificação (`mtime`), garantindo total rastreabilidade histórica. Ideal para ambiente Office 365 (Sharepoint e Teams), ja que as migrações nativas não possuem essa funcionalidade.

---

## ✨ Principais Funcionalidades

* **Fase 1 — Mapeamento Analítico:** Varredura veloz do disco de origem mostrando volume total de pastas, arquivos, tamanho em gigabytes (GB) e um painel completo com a distribuição do acervo por ano.
* **Fase 2 — Cópia Estruturada com Filtro:** Replicação idêntica da árvore de diretórios aplicando filtros temporais configuráveis ("Copiar Antigos" ou "Copiar Recentes" a partir de uma data de corte).
* **Preservação Temporal Máxima (*Bubble Up*):** O motor atualiza as datas de modificação das pastas criadas no destino com base no timestamp do arquivo mais recente contido nelas, evitando carimbos genéricos com o horário atual do sistema.
* **Monitoramento em Tempo Real (ETA):** Console de logs integrado com barra de progresso física e cálculo automático do tempo restante estimado para a conclusão.
* **Auditoria Premium:** Geração automática de relatórios detalhados ao final do processo, exportáveis para formatos **CSV** ou **HTML Dinâmico** (com filtros avançados e ordenação por cronologia).
* **Onboarding Integrado:** Sistema de tutorial dinâmico por passos (estilo tour guiado) com mini demonstrações em vídeo em loop sem controles de pausa para instrução limpa do operador.

---

## 🛠️ Tecnologias Utilizadas

* **Runtime:** [Electron](https://www.electronjs.org/) (v22.x) — Interface Desktop nativa cross-platform baseada em Chromium.
* **Linguagem:** JavaScript (ES6+), HTML5 e CSS3 (Design Escuro/Sóbrio).
* **Manipulação do Sistema de Arquivos:** [fs-extra](https://www.npmjs.com/package/fs-extra) — Criação de diretórios aninhados assíncronos e controle estrito de timestamps.
* **Empacotador/Build:** [electron-builder](https://www.electronjs.org/docs/latest/tutorial/code-signing) — Compilação e geração de instaladores otimizados para Windows.

---

## 💻 Requisitos para rodar no SO

* **Sistemas baseados em 64x:** Windows 7, 8, 10, 11 e Windows Server a partir da versão 2012.
* **Packages:** Possui o Executavel (Mais pesado) e o Setup, ideal para ambientes virtualizados ou servidores.

### 📥 Instaladores v.1.0.0
[Clique aqui para baixar o Executavel (.exe)](https://github.com/fellipe0244/FolderandFileOperator/releases/tag/versions)

[Clique aqui para baixar o Instalador (.exe)](https://github.com/fellipe0244/FolderandFileOperator/releases/tag/versions_setup)


## 💖 Apoio Financeiro

Este é um projeto independente voltado para facilitar a migração e auditoria de dados corporativos. Se você deseja contribuir financeiramente com a manutenção do software:

* 💸 **Chave Pix (E-mail):** `fellipeandrade1000@gmail.com`
* 🪙 **Chave Pix (Telefone):** `31975063000`

*Todo valor arrecadado é revertido diretamente na infraestrutura de testes e novas melhorias da engine do motor N1.*
