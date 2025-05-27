# O que é Prompt Engineering no GitHub Copilot?

Prompt engineering é a prática de criar instruções (prompts) claras e eficazes para obter as melhores respostas de uma IA como o GitHub Copilot.

## Como funciona na prática?

Você escreve um comentário ou uma instrução no seu código, e o Copilot sugere automaticamente trechos de código baseados nesse prompt.

### Exemplos reais

#### 1. Gerar uma função simples

```python
# Função para somar dois números
def 
```
O Copilot sugere automaticamente:
```python
def soma(a, b):
    return a + b
```

#### 2. Criar testes unitários

```python
# Testes unitários para a função soma
def 
```
O Copilot pode sugerir:
```python
def test_soma():
    assert soma(2, 3) == 5
    assert soma(-1, 1) == 0
```

#### 3. Documentação automática

```python
def soma(a, b):
    """
    """
```
O Copilot completa:
```python
    """
    Soma dois números e retorna o resultado.
    """
```

## Dicas para prompts melhores

- Seja específico: descreva claramente o que deseja.
- Use comentários detalhados.
- Divida tarefas complexas em etapas menores.

Prompt engineering ajuda a obter respostas mais precisas e úteis do Copilot, tornando o desenvolvimento mais rápido e eficiente.