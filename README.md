# Controle de Qualidade em E-commerce — Planejamento e Testes de QA

Projeto de portfólio de Quality Assurance (QA) direcionado ao planejamento, documentação e execução de testes funcionais para uma aplicação de e-commerce.

O escopo inicial contempla duas histórias de usuário: cadastro de usuário e login.

> **Status do projeto:** planejamento e documentação concluídos para o escopo inicial. Foram elaborados quatro casos de teste, sendo dois casos tradicionais e dois cenários BDD/Gherkin. Os quatro casos foram executados no ciclo de testes do Jira, com resultado geral de 100% de aprovação.

> **Nota sobre a cobertura:** a execução contempla os quatro cenários definidos para fins educacionais. Os resultados não representam uma validação abrangente de todos os comportamentos possíveis da aplicação.

## Objetivos

- Estruturar histórias de usuário e critérios de aceitação.
- Elaborar mapa mental para apoiar a análise e a cobertura de testes.
- Documentar casos de teste tradicionais, com passos, dados e resultados esperados.
- Desenvolver cenários BDD utilizando Gherkin.
- Organizar o ciclo de vida de defeitos e o fluxo de trabalho de QA.
- Manter rastreabilidade entre histórias, casos de teste e ciclo de testes.

## Escopo do projeto

### US-01 — Cadastro de usuário

**História de usuário:**

Como visitante do e-commerce, quero criar uma conta informando meus dados pessoais, para que eu possa me identificar e realizar compras na plataforma.

**Cobertura planejada:**

- Cadastro com dados válidos.
- Validação de campos obrigatórios.
- Formato do e-mail.
- E-mail já cadastrado.
- Confirmação de cadastro.
- Mensagens de validação.

### US-02 — Login de usuário

**História de usuário:**

Como usuário cadastrado, quero acessar minha conta utilizando e-mail e senha, para visualizar as funcionalidades autenticadas da plataforma.

**Cobertura planejada:**

- Login com credenciais válidas.
- Senha incorreta.
- E-mail sem cadastro correspondente.
- Validação de campos obrigatórios.
- Redirecionamento após autenticação.

Os cenários acima representam o escopo de análise e planejamento. A execução concluída refere-se aos quatro casos efetivamente cadastrados no ciclo de testes.

## Ferramentas utilizadas

- **Jira:** gerenciamento de histórias de usuário, acompanhamento de requisitos e organização do ciclo de testes.
- **BesTest — Gerenciamento de Requisitos e Testes para Jira:** cadastro e gerenciamento de casos de teste tradicionais e BDD.
- **diagrams.net:** elaboração do mapa mental.
- **GitHub:** versionamento e publicação da documentação.
- **PDF e Markdown:** documentação e compartilhamento dos artefatos.

## Artefatos do projeto

| Artefato | Referência | Descrição |
|---|---|---|
| História de cadastro | `KAN-1` | Requisitos de cadastro e mapa mental anexado à história. |
| História de login | `KAN-2` | Requisitos e critérios de aceitação para autenticação. |
| Caso tradicional de cadastro | `KAN-TC-1` | Cadastro com dados válidos, documentado passo a passo. |
| Caso tradicional de login | `KAN-TC-2` | Login com credenciais válidas, documentado passo a passo. |
| BDD de cadastro | `KAN-TC-3` | Cenário Gherkin de cadastro positivo. |
| BDD de login | `KAN-TC-4` | Cenário Gherkin de login positivo. |
| Ciclo de testes | `KAN-CY-1` | Ciclo que agrupa os quatro casos documentados. |

## Documentação em PDF

Os documentos estão disponíveis na pasta `docs/` deste repositório:

1. `01_Plano_QA_Fluxo_e_Ciclo_de_Vida_de_Bugs.pdf`
   - Fluxo de trabalho de QA.
   - Ciclo de vida de defeitos.
   - Modelo de registro de bugs.

2. `02_Historias_de_Usuario_e_Criterios_de_Aceite.pdf`
   - Histórias de usuário.
   - Critérios de aceitação.
   - Regras de negócio.
   - Rastreabilidade.

3. `03_Documentacao_de_Testes_Mapa_Mental_Casos_e_BDD.pdf`
   - Mapa mental.
   - Dois casos de teste tradicionais.
   - Dois cenários BDD.
   - Matriz de rastreabilidade.

## Resultados da execução

| Item | Status |
|---|---|
| Histórias de usuário documentadas | Concluído |
| Mapa mental da US-01 criado e anexado à história | Concluído |
| Dois casos tradicionais cadastrados | Concluído |
| Dois casos BDD cadastrados | Concluído |
| Ciclo de testes criado com os quatro casos | Concluído |
| Execução dos quatro casos de teste | Aprovado |
| Resultado geral do ciclo | **100% de aprovação** |
| Registro e reteste de defeitos | Não contemplado nos quatro cenários executados |

**Resultado:** os quatro casos de teste definidos para o ciclo `KAN-CY-1` foram executados e aprovados.

A aprovação refere-se exclusivamente aos cenários documentados e executados, não representando cobertura integral das funcionalidades de cadastro e login.

## Próximas etapas

1. Ampliar a cobertura dos testes funcionais.
2. Executar cenários negativos, incluindo e-mail inválido, e-mail duplicado, campos vazios, senha incorreta e e-mail inexistente.
3. Validar os critérios de aceitação em uma aplicação de e-commerce identificada.
4. Registrar resultados obtidos, ambiente, dados utilizados e evidências de execução.
5. Identificar possíveis divergências entre resultados esperados e obtidos.
6. Registrar defeitos, quando identificados, incluindo passos para reprodução, resultado esperado, resultado obtido e evidências.
7. Realizar testes de reteste e regressão após eventuais correções.

## Estrutura do repositório

```text
qa-ecommerce-test-planning/
├── README.md
└── docs/
    ├── 01_Plano_QA_Fluxo_e_Ciclo_de_Vida_de_Bugs.pdf
    ├── 02_Historias_de_Usuario_e_Criterios_de_Aceite.pdf
    └── 03_Documentacao_de_Testes_Mapa_Mental_Casos_e_BDD.pdf
```

## Observações

Este é um projeto educacional de portfólio em Quality Assurance.

As histórias de usuário e os critérios de aceitação foram elaborados para fins de planejamento e documentação de testes.

Os resultados apresentados correspondem aos quatro casos executados no ciclo de testes do Jira. A ampliação da cobertura e a validação de cenários adicionais fazem parte das próximas etapas do projeto.

---

**Projeto de Portfólio QA**  
Planejamento, documentação e execução de testes funcionais  
Versão 1.1
