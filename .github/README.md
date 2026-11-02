# LORD CONSULTA

### Dados brasileiros. Inteligência prática. Informação acessível.

Uma plataforma em desenvolvimento para centralizar, consultar e interpretar informações públicas brasileiras por meio de integrações com APIs e fontes de dados abertas.

O Lord Consulta nasce com uma proposta simples: tornar informações que normalmente estão espalhadas por diferentes serviços mais acessíveis, organizadas e úteis para as pessoas.

**Desenvolvido por [@lordjunnior](https://github.com/lordjunnior).**

---

## VISÃO DO PROJETO

Consultar uma informação não deveria exigir que o usuário conhecesse diferentes APIs, documentações técnicas ou estruturas de dados.

O Lord Consulta parte dessa ideia para construir uma experiência unificada de acesso a informações brasileiras.

A base técnica utiliza como referência a [BrasilAPI](https://github.com/BrasilAPI/BrasilAPI), iniciativa comunitária que centraliza endpoints de diferentes fontes de dados e disponibiliza interfaces modernas para integração entre sistemas.

A proposta é evoluir essa base para uma experiência própria, com organização, apresentação e funcionalidades orientadas às necessidades reais dos usuários.

## O QUE PRETENDEMOS CONSTRUIR

### 01. Consultas brasileiras

Centralização de consultas a informações públicas e serviços de dados.

- CEP e informações de endereço.
- CNPJ e dados cadastrais.
- Instituições e códigos bancários.
- DDD e localidades.
- Feriados nacionais.
- Informações de veículos e referências da tabela FIPE.

A disponibilidade de cada consulta depende das integrações e das fontes utilizadas.

### 02. Raio-X Empresarial

Uma proposta de investigação empresarial baseada em informações públicas.

O objetivo é reunir diferentes fontes para permitir a verificação de informações relacionadas a empresas brasileiras.

Possíveis integrações:

- Dados cadastrais empresariais.
- Inscrições em dívida ativa.
- Certidões de regularidade fiscal.
- Recuperação judicial e falência.
- Processos judiciais públicos.
- Débitos trabalhistas consultáveis.
- Protestos disponíveis em centrais públicas.

O sistema deverá apresentar as fontes, datas de referência, documentos disponíveis e limitações de cada consulta.

**Importante:** não existe uma base pública irrestrita que revele todas as dívidas de uma empresa. O projeto não pretende apresentar estimativas como valores oficiais nem transformar ausência de registros encontrados em garantia de regularidade.

### 03. Inteligência sobre informações

Além de apresentar resultados, a proposta é tornar os dados compreensíveis.

- Organização de informações provenientes de diferentes fontes.
- Identificação de divergências entre registros.
- Explicação de termos e classificações técnicas.
- Comparação de informações disponíveis.
- Relatórios organizados com referências verificáveis.

### 04. Relatórios e evidências

Uma consulta deve permitir que o usuário compreenda de onde veio a informação.

A evolução do projeto prevê:

- Histórico de consultas, quando habilitado.
- Identificação das fontes utilizadas.
- Datas de consulta e referência dos dados.
- Exportação de relatórios.
- Organização de documentos e evidências.

---

## FUNDAMENTAÇÃO TÉCNICA

O projeto utiliza como referência a arquitetura e a proposta da BrasilAPI.

A iniciativa original foi criada para facilitar o acesso programático a informações públicas, disponibilizando endpoints modernos e utilizando infraestrutura de distribuição e cache para otimizar o acesso aos dados.

Entre os conceitos técnicos presentes na base original estão:

- APIs REST.
- Integração com diferentes provedores de informação.
- Documentação OpenAPI.
- Estratégias de cache.
- Distribuição de conteúdo por infraestrutura CDN.
- Arquitetura preparada para implantação na Vercel.

A documentação das integrações pode ser consultada em:

- [BrasilAPI — Documentação](https://brasilapi.com.br/docs)
- [BrasilAPI — GitHub](https://github.com/BrasilAPI/BrasilAPI)
- [Vercel](https://vercel.com/)

---

## PRINCÍPIOS DO PROJETO

**Transparência**

Informações devem possuir origem identificável. Resultados não devem ser apresentados sem contexto.

**Precisão**

Dados encontrados, informações não disponíveis e conclusões não verificadas devem ser tratados separadamente.

**Privacidade**

Consultas devem evitar coleta e armazenamento desnecessários de informações pessoais.

**Acessibilidade**

Informações técnicas precisam ser apresentadas de maneira compreensível, sem exigir conhecimento especializado.

**Responsabilidade**

O acesso a dados públicos não significa autorização para abuso, varredura indiscriminada ou utilização incompatível com as condições das fontes.

---

## ROADMAP

A evolução planejada está organizada em etapas:

| Etapa | Objetivo |
|---|---|
| 01 | Estruturação e identidade do Lord Consulta |
| 02 | Integração das consultas brasileiras |
| 03 | Organização e padronização dos resultados |
| 04 | Desenvolvimento do Raio-X Empresarial |
| 05 | Integração com fontes públicas complementares |
| 06 | Relatórios, histórico e ferramentas de investigação |

O roadmap representa a direção de desenvolvimento, não funcionalidades necessariamente disponíveis na versão atual.

---

## RESPONSABILIDADE SOBRE AS FONTES

O Lord Consulta utiliza como referência uma iniciativa comunitária independente.

A BrasilAPI possui seus próprios mantenedores, colaboradores, infraestrutura e condições de utilização.

Este projeto não representa uma iniciativa oficial da BrasilAPI, Receita Federal, PGFN ou qualquer órgão governamental.

A disponibilidade, atualização, precisão e abrangência dos dados dependem das respectivas fontes.

Consultas devem respeitar os limites de utilização e as condições estabelecidas por cada serviço.

Não são permitidas varreduras automatizadas indiscriminadas ou práticas que comprometam a disponibilidade das APIs utilizadas.

---

## AUTORIA E CRÉDITOS

**Lord Consulta**

Concepção, identidade do produto e desenvolvimento da iniciativa:

**[Junnior (Lord) — @lordjunnior](https://github.com/lordjunnior)**

A infraestrutura e as integrações derivadas da BrasilAPI preservam os créditos de seus autores e colaboradores originais.

Projeto de referência:

[github.com/BrasilAPI/BrasilAPI](https://github.com/BrasilAPI/BrasilAPI)

A atribuição de autoria das partes derivadas deve respeitar a licença e os avisos de copyright presentes no repositório original.

---

### LORD CONSULTA

**Informação acessível é o primeiro passo para decisões melhores.**

[GitHub](https://github.com/lordjunnior/lord-consulta) · [Site](https://lordjunnior.com.br)
