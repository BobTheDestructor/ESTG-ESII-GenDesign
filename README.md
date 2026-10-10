# ESTG-ESII-GenDesign

## Participantes

* 2024126856 Kauã Pina
* 2024121434 Lucas Pina

## Descrição do Projeto

O **DesignAI** é uma aplicação que utiliza Inteligência Artificial para criar designs gráficos a partir de prompts escritos pelos utilizadores.

O objetivo do projeto é permitir que qualquer utilizador consiga gerar conteúdos visuais personalizados através de descrições em linguagem natural, sem precisar de conhecimentos avançados de design gráfico.

A aplicação utiliza uma API de um Large Language Model (LLM) para interpretar os pedidos dos utilizadores e uma API de geração de imagens para produzir os designs correspondentes.

## Funcionalidades Principais

* **Geração de designs por prompt:** criação de designs a partir de descrições escritas pelo utilizador.
* **Personalização com IA:** possibilidade de modificar designs através de novos pedidos em linguagem natural.
* **Alteração de estilos:** adaptação dos designs a diferentes estilos visuais, cores e temas.
* **Alteração de formatos:** criação de designs adequados a diferentes plataformas e finalidades.
* **Regeneração de designs:** geração de novas versões a partir do pedido original.
* **Gestão de projetos:** possibilidade de guardar e consultar designs criados anteriormente.

## Tecnologias

* **Frontend:** HTML, CSS e JavaScript.
* **Backend:** Python.
* **Inteligência Artificial:** API de LLM para interpretação dos prompts e API de geração de imagens.
* **Base de dados:** MySQL ou SQLite para guardar utilizadores e projetos.

## Estrutura do Repositório

```
frontend/   HTML, CSS e JS da interface
backend/    API em Python (Flask)
docs/       Requisitos, diagramas e manuais
```

Documentação:
* [Modelo de dados (diagrama ER)](docs/modelo-dados.md)

## Branches

* `main`: versão estável, só recebe merges de `dev`.
* `dev`: desenvolvimento. Cada tarefa numa branch própria (`feature/<nº-issue>-nome`) com PR para `dev`.

## Configuração

Copiar `.env.example` para `.env` e preencher as API keys. O `.env` está no `.gitignore` e nunca deve ir para o repositório.
