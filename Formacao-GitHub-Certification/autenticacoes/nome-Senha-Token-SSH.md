# Autenticação no Git e GitHub

Aprender a autenticar-se corretamente é essencial para trabalhar com Git e GitHub. Existem três métodos principais: **nome e senha**, **Token de Acesso Pessoal (PAT)** e **chave SSH**. Abaixo, cada método é explicado com exemplos práticos e links para a documentação oficial.

---

## 1. Nome de Usuário e Senha

> **Atenção:** O GitHub **não aceita mais autenticação via senha** para operações Git. Este método é apenas histórico.

### Como funcionava:
- Você fazia `git push` ou `git pull` e informava seu usuário e senha do GitHub.

### Exemplo:
```bash
git clone https://github.com/usuario/repositorio.git
# Solicita usuário e senha
```

### Documentação:
- [Autenticação via senha (obsoleto)](https://docs.github.com/pt/authentication/keeping-your-account-and-data-secure/about-authentication-to-github)

---

## 2. Token de Acesso Pessoal (PAT)

O método recomendado atualmente para HTTPS.

### Como funciona:
- Gere um token no GitHub.
- Use o token no lugar da senha ao autenticar.

### Exemplo:
```bash
git clone https://github.com/usuario/repositorio.git
# Usuário: seu-usuario
# Senha: cole o token gerado
```

#### Gerando um Token:
1. Vá em **Configurações > Developer settings > Personal access tokens**.
2. Clique em **Generate new token**.
3. Defina permissões e salve o token.

### Documentação:
- [Tokens de acesso pessoal](https://docs.github.com/pt/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token)

---

## 3. Chave SSH

Método seguro e prático para autenticação sem senha.

### Como funciona:
- Gere um par de chaves SSH (pública/privada).
- Adicione a chave pública ao GitHub.
- Use o repositório via SSH.

### Exemplo:
```bash
# Gerar chave SSH
ssh-keygen -t ed25519 -C "seu-email@exemplo.com"

# Adicionar chave ao ssh-agent
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_ed25519

# Adicionar chave pública ao GitHub (Settings > SSH and GPG keys)

# Clonar repositório via SSH
git clone git@github.com:usuario/repositorio.git
```

### Documentação:
- [Conectar-se ao GitHub com SSH](https://docs.github.com/pt/authentication/connecting-to-github-with-ssh)

---

## Resumo

- **Senha:** Não é mais aceita.
- **Token:** Use para HTTPS.
- **SSH:** Use para autenticação sem senha.

> Sempre prefira **Token** ou **SSH** para segurança e praticidade.

---

## Links Úteis

- [Documentação oficial do GitHub](https://docs.github.com/pt)
- [Guia de autenticação do GitHub](https://docs.github.com/pt/authentication)
