## Copilot em CLIs: Explicação Lúdica

Imagine que você está cozinhando e tem um assistente que sugere receitas enquanto você escolhe os ingredientes. O GitHub Copilot para CLIs (Command Line Interfaces) funciona de forma parecida: ele sugere comandos e opções enquanto você digita no terminal, tornando seu trabalho mais rápido e fácil.

### Exemplo Real 1: Navegando por Pastas

Você quer encontrar um arquivo, mas não lembra o caminho exato. Com Copilot CLI, basta digitar:

```bash
copilot suggest "encontrar arquivo chamado relatório"
```

O Copilot sugere o comando `find . -name "relatório*"` para você!

### Exemplo Real 2: Gerando um Commit

Precisa criar uma mensagem de commit clara? Experimente:

```bash
copilot suggest "criar commit para corrigir bug de login"
```

O Copilot pode sugerir: `git commit -m "Corrige bug de login ao validar credenciais"`

### Exemplo Real 3: Automatizando Tarefas

Quer rodar testes automaticamente?

```bash
copilot suggest "rodar todos os testes do projeto"
```

Ele sugere: `npm test` ou `pytest`, dependendo do seu projeto.

---

## Consulte a Documentação Oficial

Acesse a documentação oficial do GitHub Copilot CLI para mais detalhes e exemplos:

[https://docs.github.com/en/copilot/using-github-copilot/github-copilot-in-the-cli](https://docs.github.com/en/copilot/using-github-copilot/github-copilot-in-the-cli)