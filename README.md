# Pôster do Dia

[![Status](https://img.shields.io/badge/status-[em_desenvolvimento]-yellow)]()
[![Versão](https://img.shields.io/badge/versão-[0.1.0]-blue)]()
[![Licença](https://img.shields.io/badge/licença-[acadêmica]-lightgrey)]()

**Instituição:** CEUB 

**Curso:** Ciência da Computação 

**Disciplina:** Desenvolvimento Web

**Professor(a):** Felippe Pires Ferreira 

**Status do projeto:** Em desenvolvimento

---

## Sumário

- [1. Descrição do projeto](#1-descrição-do-projeto)
- [2. Funcionalidades](#2-funcionalidades)
- [3. Tecnologias utilizadas](#3-tecnologias-utilizadas)
- [4. Arquitetura](#4-arquitetura)
- [5. Organização dos diretórios](#5-organização-dos-diretórios)
- [6. Participantes](#6-participantes)
- [7. Licença, referências e contato](#7-licença-referências-e-contato)

---

## 1. Descrição do projeto

  Inspirado na popularidade dos jogos diários de adivinhação visual como Flagle e Frame6, o Pôster do Dia nasce para oferecer a cinéfilos e jogadores casuais uma plataforma intuitiva para testar seu repertório cinematográfico através da identificação de pôsteres. Ao mesmo tempo, a aplicação resolve a carência de ferramentas centralizadas para curadores e administradores do sistema, disponibilizando uma interface estruturada para catalogar produções, agendar desafios diários e analisar métricas de uso da comunidade.
  O objetivo principal do projeto é entregar uma aplicação web completa de adivinhação baseada na revelação fracionada do pôster oficial (1/6 da imagem a cada tentativa), acompanhada de um painel de gestão de catálogo e de uma API REST pública. Dentre as funcionalidades prioritárias, destacam-se o mecanismo de busca multicritério por filmes (título, gênero, ano e diretor), a integração com a API externa do TMDB para preenchimento automatizado de dados e a geração de relatórios consolidados de desempenho com opções de filtragem e exportação para PDF/impressão.
  Academicamente, o desenvolvimento justifica-se pela aplicação prática de uma arquitetura full-stack completa. O escopo abrange a construção de rotas e rotinas de CRUD com validação de dados, a implementação de uma API REST própria documentada no padrão JSON, o gerenciamento de estado local no navegador e a aplicação rigorosa de um guia de identidade visual coeso, unindo a engenharia de software à entrega de um produto de entretenimento funcional e acessível.

### Objetivos

- **Objetivo geral:**  Desenvolver uma aplicação web completa de adivinhação de filmes por revelação fracionada de pôster, acompanhada de um sistema de gestão de catálogo e API REST pública.
- **Objetivos específicos:**
  - Implementar o módulo de Cadastro de Informações (CRUD) para gestão de filmes e desafios com validação de campos.
  - Desenvolver mecanismo de Busca Múltipla por critérios como título, gênero, ano e diretor.
  - Criar um módulo de Relatórios Consolidados de partidas e estatísticas com opções de filtro, visualização e exportação/impressão.
  - Construir uma API REST Própria documentada, em formato JSON, com rotas, parâmetros e códigos de status HTTP bem definidos.
  - Integrar o sistema ao Consumo de API Externa (ex.: TMDB API) para importação automatizada de dados e pôsteres.
  - Definir e aplicar uma Identidade Visual coesa (logotipo, paleta de cores e tipografia) em todas as telas da aplicação.

### Público-alvo

- Jogadores/Usuários Finais: Cinéfilos e entusiastas de jogos diários de adivinhação.
- Administradores/Curadores do Sistema: Responsáveis por cadastrar, alterar, validar e organizar os filmes e os desafios diários da plataforma.
---

## 2. Funcionalidades

*Liste as funções implementadas (ou previstas) no sistema. Marque o status de cada uma.*

| Funcionalidade | Descrição | Status |
| --- | --- | --- |
| Módulo de Administração do Catálogo| Painel administrativo contendo formulários para incluir, consultar, alterar e excluir filmes e desafios do banco de dados, com validação de campos obrigatórios e mensagens de sucesso/erro. | Planejada |
| Pesquisa Multicritério de Filmes | Barra de pesquisa e filtros para localizar filmes cadastrados combinando título, ano de lançamento, gênero ou diretor, exibindo os resultados formatados em cards/tabela. | Planejada |
| Relatório de Desempenho e Indicadores | Tela de consolidação de métricas (total de jogos, taxa de vitória, média de tentativas e filmes com menor índice de acerto) com suporte a filtros por período e botões de exportação em PDF/impressão. | Planejada |

---


## 3. Tecnologias utilizadas

*Informe as tecnologias de fato usadas no projeto. Remova as linhas que não se aplicarem.*

| Camada | Tecnologia | Versão |
| --- | --- | --- |
| Linguagem | Python | 3.12 |
| Frontend | HTML, CSS, JavaScript | - |
| Backend | Django | - |
| Banco de dados | A definir | - |
| Testes | A definir | - |
| Infraestrutura | [Ex.: Docker, GitHub Actions] | — |
| Outras ferramentas | Figma | — |

---

## 4. Arquitetura

A arquitetura do Pôster do Dia foi estruturada sob o padrão de Camadas e Componentes Independentes, visando garantir a separação clara de responsabilidades, alta manutenibilidade, testabilidade e baixo acoplamento. O sistema atende tanto às necessidades de entretenimento dos jogadores finais quanto às demandas de gestão dos administradores e de integração de desenvolvedores terceiros.


## 5. Organização dos diretórios

```text
.
├── README.md                            
├── docs/                     
│   |          
│   └── modelagem/
│       ├── casos-de-uso/
│       │   └── Diagrama Casos de Uso.pdf
│       │   └── Caso de Uso.pdf
│       └── banco-de-dados/
│           ├── Modelo de Dados.pdf
│           └── modelo-dados-poster_do_dia.png                              
                 
```

| Diretório / arquivo | Função |
| --- | --- |
| `README.md` | Apresentação do projeto, objetivos, tecnologias e instruções de uso |
| `docs/` | Artefatos de análise e modelagem em PDF |
| `docs/modelagem/` | Casos de uso, componentes e modelo de dados |

---

## 6. Participantes

- Diogo Lucas Sobreira de Lucena
- Pedro Heringer 

**Professor(a) responsável:** Felippe Pires Ferreira

---

## 7. Licença, referências e contato

**Licença:**  uso exclusivamente acadêmico

Este material destina-se a fins educacionais.


