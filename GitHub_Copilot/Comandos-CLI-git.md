# 30 Comandos Importantes do CLI do GitHub Copilot

> **Observação:** O GitHub Copilot CLI é uma extensão experimental para terminal. Para usá-lo, instale e configure o [GitHub Copilot CLI](https://docs.github.com/pt/copilot/github-copilot-in-the-cli/getting-started-with-github-copilot-in-the-cli).

## Comandos Básicos

1. `gh copilot help`  
    Exibe ajuda geral sobre o Copilot CLI.

2. `gh copilot suggest`  
    Gera sugestões de código com base em um prompt.

3. `gh copilot explain`  
    Explica o que um trecho de código faz.

4. `gh copilot generate`  
    Gera código a partir de uma descrição.

5. `gh copilot alias`  
    Gerencia aliases personalizados para prompts.

6. `gh copilot alias list`  
    Lista todos os aliases criados.

7. `gh copilot alias add <nome> <prompt>`  
    Adiciona um novo alias.

8. `gh copilot alias remove <nome>`  
    Remove um alias existente.

9. `gh copilot alias update <nome> <novo-prompt>`  
    Atualiza um alias.

10. `gh copilot config`  
     Gerencia configurações do Copilot CLI.

## Exemplos de Uso

11. `gh copilot suggest "crie uma função em Python para inverter uma string"`  
     Sugere código para a tarefa descrita.

12. `gh copilot explain arquivo.py`  
     Explica o código presente em `arquivo.py`.

13. `gh copilot generate "classe em Java para conexão com banco de dados"`  
     Gera uma classe Java conforme a descrição.

14. `gh copilot suggest -f main.py`  
     Sugere melhorias para o arquivo `main.py`.

15. `gh copilot explain -f script.js`  
     Explica o código do arquivo `script.js`.

## Comandos Avançados

16. `gh copilot suggest --language javascript`  
     Força a sugestão em uma linguagem específica.

17. `gh copilot generate --output resultado.py`  
     Salva o código gerado em um arquivo.

18. `gh copilot explain --line 10-20 arquivo.py`  
     Explica apenas as linhas 10 a 20 do arquivo.

19. `gh copilot suggest --shell`  
     Gera comandos de shell.

20. `gh copilot generate --stdin`  
     Usa entrada padrão para gerar código.

## Integração e Configuração

21. `gh copilot config set key value`  
     Define uma configuração.

22. `gh copilot config get key`  
     Obtém o valor de uma configuração.

23. `gh copilot config list`  
     Lista todas as configurações.

24. `gh copilot config unset key`  
     Remove uma configuração.

25. `gh copilot feedback`  
     Envia feedback sobre o Copilot CLI.

## Outros Comandos Úteis

26. `gh copilot version`  
     Mostra a versão instalada do Copilot CLI.

27. `gh copilot login`  
     Faz login na sua conta GitHub.

28. `gh copilot logout`  
     Faz logout da sua conta GitHub.

29. `gh copilot status`  
     Mostra o status atual do Copilot CLI.

30. `gh copilot update`  
     Atualiza o Copilot CLI para a última versão.

---

> Consulte a [documentação oficial](https://docs.github.com/pt/copilot/github-copilot-in-the-cli) para mais detalhes e exemplos.

