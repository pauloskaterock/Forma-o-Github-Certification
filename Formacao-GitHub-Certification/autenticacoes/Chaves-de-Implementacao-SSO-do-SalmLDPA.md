# Curso Git e GitHub: Guia Completo

## 1. Introdução ao Git
Git é um sistema de controle de versão distribuído, usado para rastrear alterações em arquivos e coordenar o trabalho entre desenvolvedores.

- **Exemplo real:** Equipes de desenvolvimento usam Git para colaborar em projetos de software, mantendo o histórico de alterações.
- [Documentação oficial do Git](https://git-scm.com/doc)

---

## 2. Conceitos Básicos do Git

- **Repositório:** Local onde o histórico do projeto é armazenado.
- **Commit:** Registro de uma alteração.
- **Branch:** Linha paralela de desenvolvimento.
- **Merge:** Unificação de branches.

```bash
git init                # Inicializa um repositório
git add arquivo.txt     # Adiciona arquivo ao stage
git commit -m "Mensagem" # Salva alterações
git branch nova-feature # Cria uma branch
git merge nova-feature  # Mescla branch
```

---

## 3. Introdução ao GitHub

GitHub é uma plataforma de hospedagem de código-fonte baseada em Git, facilitando colaboração, revisão de código e integração contínua.

- **Exemplo real:** Hospedar projetos open source, colaborar via pull requests.
- [Documentação oficial do GitHub](https://docs.github.com/)

---

## 4. Fluxo de Trabalho Básico

1. **Clone o repositório:**
    ```bash
    git clone https://github.com/usuario/repositorio.git
    ```
2. **Crie uma branch:**
    ```bash
    git checkout -b minha-feature
    ```
3. **Faça commits e envie para o GitHub:**
    ```bash
    git add .
    git commit -m "Implementa nova feature"
    git push origin minha-feature
    ```
4. **Abra um Pull Request no GitHub.**

---

## 5. Chaves de Implementação

Chaves SSH permitem autenticação segura entre seu computador e o GitHub.

- **Exemplo real:** Automatizar deploys usando chaves de implementação.
- [Gerenciar chaves SSH no GitHub](https://docs.github.com/pt/authentication/connecting-to-github-with-ssh)

---

## 6. SSO do Salm e LDPA

- **SSO (Single Sign-On):** Permite login único em múltiplos sistemas.
- **Salm:** Sistema de Autenticação e Login Modular.
- **LDPA:** Protocolo de autenticação baseado em diretórios.

**Exemplo real:** Empresas integram GitHub com SSO corporativo via SAML ou LDAP para facilitar o acesso dos colaboradores.

- [SSO com SAML no GitHub](https://docs.github.com/pt/enterprise-cloud@latest/admin/authentication/using-saml/)
- [Integração LDAP](https://docs.github.com/pt/enterprise-server@3.0/admin/authentication/using-ldap/)

---

## 7. Conclusão

Git e GitHub são essenciais para o desenvolvimento moderno. O uso de chaves de implementação e autenticação SSO aumenta a segurança e a produtividade.
