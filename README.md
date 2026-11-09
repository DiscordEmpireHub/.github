# .github — Configurações Globais da EmpireCommunity

Este repositório contém as configurações e padrões globais de governança, saúde de comunidade e automação para todos os repositórios da **EmpireCommunity**.

## 📁 Estrutura deste Repositório

- **`profile/README.md`**: Página pública principal do perfil da organização no GitHub.
- **`CODE_OF_CONDUCT.md`**: Código de Conduta (Contributor Covenant v2.1) aplicado a todos os repositórios públicos e privados.
- **`CONTRIBUTING.md`**: Diretrizes de contribuição, padrões de commit, branching e fluxo de trabalho colaborativo.
- **`DISCUSSIONS.md`**: Guia de comunicação da comunidade (quando usar Discord vs GitHub Discussions vs Issues).
- **`SECURITY.md`**: Política de segurança e reporte responsável de vulnerabilidades.
- **`SUPPORT.md`**: Guia de suporte ao usuário e canais oficiais.
- **`.github/pull_request_template.md`**: Modelo padrão de Pull Request herdado automaticamente por qualquer repositório da organização que não tenha template próprio.
- **`.github/ISSUE_TEMPLATE/`**: Formulários estruturados de abertura de issues (Bugs com logs e gravidade, Features, Documentação, RFCs e Chooser).
- **`.github/DISCUSSION_TEMPLATE/`**: Formulários das categorias de discussão (Ideas, Q&A e Show and tell).
- **`.github/workflows/`**: Automação de colaboração (lint do título de PRs).
- **`.github/dependabot.yml`**: Atualização semanal das GitHub Actions deste repositório.

## 🚀 Como Funciona

O GitHub usa automaticamente os arquivos deste repositório (`.github`) como *fallback* padrão para qualquer repositório da organização que não possua seu próprio arquivo de `CONTRIBUTING.md`, `CODE_OF_CONDUCT.md`, `SECURITY.md`, `SUPPORT.md` ou templates de Issues/PR.
