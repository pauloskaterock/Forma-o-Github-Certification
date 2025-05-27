Para verificar se o GitHub Copilot CLI está instalado corretamente, primeiro certifique-se de que o GitHub CLI (`gh`) está instalado em seu sistema.

Se ao executar o comando abaixo:

```sh
gh copilot --version
```

você receber a mensagem `Command 'gh' not found`, isso indica que o GitHub CLI não está instalado. Para instalar, utilize um dos comandos abaixo, conforme sua preferência:

```sh
sudo snap install gh
```
ou
```sh
sudo apt install gh
```

Após a instalação, execute novamente:

```sh
gh copilot --version
```

Se aparecer a mensagem `unknown command "copilot" for "gh"`, significa que a extensão Copilot CLI ainda não está instalada. Para instalar, execute:

```sh
gh extension install github/gh-copilot
```

Durante a instalação, pode ser solicitado que você faça login no GitHub CLI. Caso veja a mensagem `To authenticate, please run 'gh auth login'`, execute:

```sh
gh auth login
```

Depois de autenticar, repita o comando de instalação da extensão:

```sh
gh extension install github/gh-copilot
```

Por fim, verifique novamente com:

```sh
gh copilot --version
```

Se tudo estiver correto, será exibida a versão instalada da extensão Copilot CLI.
