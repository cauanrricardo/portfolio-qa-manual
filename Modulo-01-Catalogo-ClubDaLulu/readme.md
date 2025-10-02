# Testes Manuais - Catálogo Web

Este diretório reúne os casos de teste manuais elaborados para o sistema **Catálogo Web (Versão 1.0)**, desenvolvido como projeto prático.

##  Estrutura do Diretório

| Diretório | Descrição |
|-----------|-----------|
| **`Casos-de-Teste/`** | Contém os casos documentados para o cenário de Carrinho de Compras (9 casos no total) |
| **`Bug-Reports/`** | Relatórios de inconsistências encontradas durante a execução (1 bug identificado) |
| **`Evidencias/`** | Capturas de tela selecionadas da execução dos testes |
| **`Relatorios/`** | Resumo da execução dos testes e status final |

##  Cenário Testado

### Carrinho de Compras

- Adicionar, remover e alterar produtos
- Inserção de quantidades inválidas (zero, negativa, não numérica)
- Comportamento do checkout com carrinho vazio
- Soma de quantidades ao adicionar o mesmo produto novamente

##  Resultados

| Métrica | Valor |
|---------|-------|
| **Casos de teste executados** | 9 |
| **Casos aprovados** | 8 |
| **Casos reprovados** | 1 (gerou bug report) |
| **Taxa de sucesso** | 88.9% |
