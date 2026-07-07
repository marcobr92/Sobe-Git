# Sobe-Git

Repositório de validação da integração entre ambiente local (WSL/Ubuntu), GitHub e o agente **OpenCode**.

## Objetivo

Testar e comprovar o fluxo completo de trabalho com Git + GitHub utilizando um agente de IA autônomo: criação de branches, commits, pull requests e merges — tudo com sucesso.

## Resultado

- Conexão SSH e autenticação com GitHub configuradas e funcionando.
- Branchs criadas e gerenciadas (`main`, `atualiza-pipe`, `atualiza-branch`, `feature/readme-upd`, `feature/updt-actions`).
- Pull Requests abertos e mergedos via merge commit.
- CI validado com GitHub Actions (workflow básico).
- Arquivo `AGENTS.md` gerado automaticamente pelo OpenCode.

## Sobre o OpenCode

**OpenCode** é um agente autônomo de engenharia de software que opera via CLI.  
Este repositório foi utilizado para validar sua capacidade de interagir com Git/GitHub de forma prática.

- Agente: **OpenCode**
- Modelo: **big-pickle** (`opencode/big-pickle`)
- README atualizado por OpenCode em 07/07/2026, a pedido de **Marco Beraldi**.
