# Branches no Git e GitHub

Branches (ramificações) são fundamentais no controle de versões com Git e GitHub. Elas permitem que você trabalhe em diferentes funcionalidades, correções ou experimentos de forma isolada, sem afetar o código principal.

---

## O que é uma branch?

Uma branch é uma linha independente de desenvolvimento. Por padrão, todo repositório Git começa com a branch `main` (ou `master`). Ao criar uma nova branch, você pode desenvolver funcionalidades sem impactar o código estável.

---

## Por que usar branches?

- **Desenvolvimento paralelo:** Várias pessoas podem trabalhar em diferentes funcionalidades ao mesmo tempo.
- **Isolamento:** Mudanças experimentais não afetam o código principal.
- **Facilidade de integração:** Permite testar e revisar código antes de integrá-lo à branch principal.

---

## Comandos básicos de branches

### Criar uma nova branch

```bash
git branch nome-da-branch
```

### Mudar para uma branch existente

```bash
git checkout nome-da-branch
```

Ou, a partir do Git 2.23:

```bash
git switch nome-da-branch
```

### Criar e mudar para uma nova branch

```bash
git checkout -b nome-da-branch
```

Ou:

```bash
git switch -c nome-da-branch
```

### Listar branches

```bash
git branch
```

### Excluir uma branch

```bash
git branch -d nome-da-branch
```

---

## Exemplo real

Imagine que você está desenvolvendo um site e precisa adicionar uma nova funcionalidade de login:

1. Crie uma branch para a funcionalidade:
    ```bash
    git checkout -b feature/login
    ```
2. Faça as alterações e commits necessários.
3. Suba a branch para o GitHub:
    ```bash
    git push origin feature/login
    ```
4. Abra um Pull Request no GitHub para revisar e integrar a branch ao `main`.

---

## Trabalhando com branches no GitHub

No GitHub, você pode criar, visualizar e gerenciar branches diretamente pela interface web. Também é possível abrir Pull Requests para sugerir mudanças de uma branch para outra.

---

## Documentação oficial

- [Branches no Git - Documentação Oficial](https://git-scm.com/book/pt-br/v2/Ramifica%C3%A7%C3%A3o-Branching-no-Git)
- [Branches no GitHub Docs](https://docs.github.com/pt/github/collaborating-with-issues-and-pull-requests/about-branches)
