# Pull Requests no Git e GitHub

Pull Requests (PRs) são uma funcionalidade central do GitHub para colaboração em projetos. Eles permitem sugerir alterações em um repositório, discutir melhorias e revisar código antes da integração.

---

## 1. O que é um Pull Request?

Um Pull Request é uma solicitação para mesclar alterações de um branch (ramo) para outro, geralmente de um branch de feature para o branch principal (`main` ou `master`). Ele permite revisão, discussão e testes antes da integração.

---

## 2. Fluxo Básico de um Pull Request

1. **Criação de um branch**  
    Crie um novo branch para sua feature ou correção:
    ```bash
    git checkout -b minha-feature
    ```

2. **Faça alterações e commit**  
    Edite arquivos, adicione e faça commit:
    ```bash
    git add .
    git commit -m "Adiciona nova feature"
    ```

3. **Envie para o GitHub**  
    Suba seu branch para o repositório remoto:
    ```bash
    git push origin minha-feature
    ```

4. **Abra um Pull Request**  
    No GitHub, clique em "Compare & pull request" ou vá na aba "Pull requests" e clique em "New pull request". Escolha o branch de origem e destino.

---

## 3. Revisão e Discussão

- Outros colaboradores podem comentar, sugerir mudanças ou aprovar.
- Você pode responder comentários e fazer novos commits no mesmo branch; o PR será atualizado automaticamente.

---

## 4. Merge do Pull Request

Após aprovação, clique em "Merge pull request" para integrar as alterações ao branch principal. Depois, exclua o branch se desejar.

---

## 5. Exemplo Real

Imagine um projeto open source. Você encontrou um bug, criou um fork, fez as correções em um branch, enviou para seu fork e abriu um Pull Request para o repositório original. Os mantenedores revisam, sugerem ajustes e, após aprovação, fazem o merge.

---

## 6. Boas Práticas

- Faça PRs pequenos e focados.
- Escreva descrições claras.
- Use títulos descritivos.
- Sempre revise o código antes de pedir revisão.

---

## 7. Documentação Oficial

- [Documentação de Pull Requests no GitHub](https://docs.github.com/pt/pull-requests)
- [Fluxo de trabalho de Pull Requests](https://docs.github.com/pt/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)
