# Testes Manuais - Sistema de Login

Este diretório reúne os casos de teste manuais elaborados para o sistema **Sistema de Login (Versão 1.0)**, desenvolvido por mim e como projeto prático.

## Estrutura do Diretório

| Diretório | Descrição |
|-----------|-----------|
| **`Casos-de-Teste/`** | Contém os casos documentados para o cenário de Login (14 casos no total) |
| **`Bug-Reports/`** | Relatórios de inconsistências encontradas durante a execução (3 bugs identificados) |
| **`Evidencias/`** | Capturas de tela selecionadas da execução dos testes |

## Cenário Testado

### Sistema de Login

- Login válido com diferentes perfis de usuário
- Login inválido com senha incorreta, usuário inexistente ou campos vazios
- Tratamento de maiúsculas/minúsculas no usuário e senha
- Inserção de espaços no início ou fim dos campos de login
- Verificação de mensagens de erro e sucesso

## Resultados

| Métrica | Valor |
|---------|-------|
| **Casos de teste executados** | 14 |
| **Casos aprovados** | 11 |
| **Casos reprovados** | 3 (geraram bug reports) |
| **Taxa de sucesso** | 78.6% |
