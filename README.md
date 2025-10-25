# Lab02 - Integração Contínua com GitHub Actions

---

Este repositório contém a implementação de um workflow de Integração Contínua (CI) utilizando o **GitHub Actions**. O objetivo deste projeto foi configurar um workflow básico para automatizar a execução de um código Node.js, incluindo a instalação de dependências e a execução de um script simples.

## Objetivo

O principal objetivo deste exercício foi criar um workflow que:
1. Realiza o **checkout** do código sempre que um commit é enviado para o repositório.
2. Instala as dependências do projeto, incluindo o pacote `moment`.
3. Executa o script **`app.js`**, que imprime a data atual utilizando a biblioteca `moment`.

## Estrutura do Projeto

- **.github/workflows/build.yml**: Contém o arquivo de configuração do GitHub Actions que define o workflow.
- **package.json**: Define as dependências do projeto, incluindo a biblioteca `moment`.
- **app.js**: Script simples em Node.js que exibe a data atual utilizando o `moment`.
- **.gitignore**: Arquivo que define quais arquivos e diretórios o Git deve ignorar (como o `node_modules`).
- **README.md**: Este arquivo de documentação.

## Conclusão
Este exercício ajudou a configurar um pipeline de Integração Contínua simples usando o GitHub Actions para automatizar o processo de execução de código. A automação facilita a execução de testes, builds, e outras tarefas necessárias para o desenvolvimento contínuo de software.

---

### Discente: Alicia Caldeira
### Curso: Web Academy - UFAM
