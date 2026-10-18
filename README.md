# QA E-commerce — Test Planning

Projeto de portfólio de QA voltado ao planejamento e à documentação de testes funcionais para um e-commerce. O escopo inicial contempla duas histórias de usuário: cadastro de usuário e login.

> **Status do projeto:** planejamento e documentação concluídos para o escopo inicial. Os casos de teste foram cadastrados, mas ainda não foram executados. Portanto, este repositório não apresenta resultados de aprovação/reprovação nem afirma que os comportamentos foram validados em uma aplicação real.

## Objetivos

- Estruturar histórias de usuário e critérios de aceite.
- Elaborar um mapa mental para apoiar a análise de testes.
- Documentar casos de teste tradicionais, com passos, dados e resultados esperados.
- Escrever cenários BDD/Gherkin.
- Organizar o ciclo de vida de defeitos e o fluxo de trabalho de QA.
- Manter rastreabilidade entre histórias, casos de teste e ciclo de testes.

## Escopo atual

### US-01 — Cadastro de usuário
Como visitante do e-commerce, quero criar uma conta informando meus dados pessoais, para que eu possa me identificar e realizar compras na plataforma.

Cobertura planejada:
- Cadastro com dados válidos.
- Campos obrigatórios.
- Formato do e-mail.
- E-mail já cadastrado.
- Confirmação de cadastro.
- Mensagens de validação.

### US-02 — Login de usuário
Como usuário cadastrado, quero acessar minha conta usando e-mail e senha, para visualizar as funcionalidades autenticadas da plataforma.

Cobertura planejada:
- Login com credenciais válidas.
- Senha incorreta.
- E-mail sem cadastro correspondente.
- Campos obrigatórios.
- Redirecionamento após autenticação.

Os cenários listados são uma proposta educacional. Antes da execução, os critérios e resultados esperados devem ser comparados com os requisitos e o comportamento da aplicação escolhida.

## Ferramentas utilizadas

- **Jira:** registro das histórias de usuário e acompanhamento do projeto.
- **BesTest — Requirement & Test Management for Jira:** cadastro de casos tradicionais e BDD e organização do ciclo de testes.
- **diagrams.net:** criação do mapa mental.
- **GitHub:** versionamento e publicação da documentação.
- **PDF/Markdown:** documentação e compartilhamento dos artefatos.

## Artefatos

| Artefato | Referência | Descrição |
|---|---|---|
| História de cadastro | `KAN-1` | Requisitos propostos para cadastro; o mapa mental em PDF está anexado à história. |
| História de login | `KAN-2` | Requisitos propostos para login. |
| Caso tradicional de cadastro | `KAN-TC-1` | Cadastro com dados válidos, descrito passo a passo. |
| Caso tradicional de login | `KAN-TC-2` | Login com credenciais válidas, descrito passo a passo. |
| BDD de cadastro | `KAN-TC-3` | Cenário Gherkin de cadastro positivo. |
| BDD de login | `KAN-TC-4` | Cenário Gherkin de login positivo. |
| Ciclo de testes | `KAN-CY-1` | Ciclo que agrupa os quatro casos documentados. |

## Documentação em PDF

Os arquivos estão na pasta `docs/` deste repositório:

- `01_Plano_QA_Fluxo_e_Ciclo_de_Vida_de_Bugs.pdf` — fluxo de trabalho de QA, ciclo de vida de defeitos e modelo de registro de bug.
- `02_Historias_de_Usuario_e_Criterios_de_Aceite.pdf` — histórias, critérios de aceite, regras de negócio e rastreabilidade.
- `03_Documentacao_de_Testes_Mapa_Mental_Casos_e_BDD.pdf` — mapa mental, dois casos tradicionais, dois cenários BDD e matriz de rastreabilidade.

## Status da execução

| Item | Status |
|---|---|
| Histórias de usuário documentadas | Concluído |
| Mapa mental da US-01 criado e anexado à história | Concluído |
| 2 casos tradicionais cadastrados | Concluído |
| 2 casos BDD cadastrados | Concluído |
| Ciclo de testes criado com os 4 casos | Concluído |
| Execução dos testes | **Pendente** |
| Registro de resultados e evidências reais | **Pendente** |
| Registro e reteste de defeitos encontrados | **Pendente** |

**Importante:** criar um caso ou adicioná-lo a um ciclo não significa que o teste foi executado. Após a execução, atualizar o status de cada caso e registrar evidências reais. Não marcar casos como aprovados sem comparar o resultado observado com o esperado.

## Próximas etapas

1. Escolher e acessar a aplicação de e-commerce que será usada para validar os requisitos.
2. Confirmar os campos, regras e mensagens reais de cadastro e login.
3. Executar os quatro casos do ciclo `KAN-CY-1`.
4. Registrar resultado observado, ambiente, data e evidências.
5. Se houver divergência, abrir defeito com passos para reprodução, resultado esperado, resultado observado e evidências.
6. Ampliar a cobertura com cenários negativos, especialmente e-mail inválido/duplicado, campos vazios, senha incorreta e e-mail inexistente.
7. Atualizar esta documentação conforme os resultados obtidos.

## Estrutura sugerida do repositório

```text
qa-ecommerce-test-planning/
├── README.md
└── docs/
    ├── 01_Plano_QA_Fluxo_e_Ciclo_de_Vida_de_Bugs.pdf
    ├── 02_Historias_de_Usuario_e_Criterios_de_Aceite.pdf
    └── 03_Documentacao_de_Testes_Mapa_Mental_Casos_e_BDD.pdf
```

## Observações

Este é um projeto de estudo e portfólio. As histórias e critérios são requisitos propostos para planejamento; não devem ser interpretados como confirmação de funcionalidades de um produto específico. Os resultados só serão registrados após execução efetiva em ambiente identificado.

---
Projeto de portfólio QA | Documentação inicial — versão 1.0
