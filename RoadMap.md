Estrutura Completa de Curso de Git e GitHub
Baseado no roadmap.sh/git-github, este curso abrange desde conceitos básicos até tópicos avançados de Git e GitHub.

Módulo 1: Introdução ao Git e Controle de Versão
1.1 Fundamentos do Controle de Versão
O que é Controle de Versão?

Sistemas Centralizados vs. Distribuídos

Por que usar Git?

1.2 Instalação e Configuração
Instalando Git (Windows, macOS, Linux)

Configurando usuário (git config)

Editor padrão (VS Code, Nano, Vim)

Módulo 2: Comandos Básicos do Git
2.1 Iniciando um Repositório
git init (criar novo repositório)

git clone (clonar repositório existente)

2.2 Ciclo de Vida dos Arquivos
Estados dos arquivos (Untracked, Staged, Modified, Committed)

git status (verificar estado)

git add (adicionar ao staging)

git commit (salvar alterações)

2.3 Visualizando Alterações
git diff (comparar mudanças)

git log (histórico de commits)

git show (detalhes de um commit)

Módulo 3: Trabalhando com Branches (Ramificações)
3.1 Introdução a Branches
O que são branches?

Branch main/master

git branch (listar, criar e deletar branches)

git checkout e git switch (trocar de branch)

3.2 Merge e Conflitos
git merge (unir branches)

Resolvendo conflitos de merge

Fast-forward vs. merge commit

3.3 Rebasing
git rebase (reescrever histórico)

Quando usar merge vs. rebase

Módulo 4: Trabalhando com Repositórios Remotos (GitHub)
4.1 Introdução ao GitHub
O que é GitHub?

Criando uma conta

Configurando SSH Key

4.2 Sincronizando Alterações
git remote (gerenciar repositórios remotos)

git push (enviar alterações)

git pull (baixar alterações)

git fetch (buscar alterações sem merge)

4.3 Trabalhando com Forks e Pull Requests
Forking um repositório

Criando um Pull Request (PR)

Revisão de código e merge no GitHub

Módulo 5: Tópicos Avançados
5.1 Git Stash
git stash (guardar alterações temporárias)

git stash pop (recuperar alterações)

5.2 Git Tags
git tag (marcar versões)

Tags anotadas vs. leves

5.3 Git Hooks
O que são hooks?

Exemplos de hooks (pre-commit, post-merge)

5.4 Git Submodules
Trabalhando com submódulos

git submodule add

5.5 Revertendo Alterações
git reset (soft, mixed, hard)

git revert (desfazer commits públicos)

git cherry-pick (aplicar commit específico)

Módulo 6: Boas Práticas e Workflows
6.1 Convenções de Commit
Mensagens de commit semânticas

Conventional Commits

6.2 Workflows Populares
Git Flow (branches main, develop, feature, release, hotfix)

GitHub Flow (simplificado, baseado em PRs)

Trunk-Based Development

6.3 Git em Equipe
Code Review no GitHub

Protegendo branches (main branch rules)

GitHub Actions (CI/CD básico)

Módulo 7: Projetos Práticos
7.1 Projeto 1: Controle de Versão Pessoal
Criar um repositório local

Fazer commits, branches e merges

7.2 Projeto 2: Contribuição em Open Source
Fork de um projeto no GitHub

Enviar um Pull Request

7.3 Projeto 3: Resolução de Conflitos
Simular conflitos e resolvê-los

Módulo 8: Recursos Extras
8.1 Ferramentas e GUI
GitHub Desktop

GitKraken

VS Code + Git

8.2 Referências e Aprofundamento
Livros: Pro Git (gratuito online)

Cursos avançados (Git Internals)