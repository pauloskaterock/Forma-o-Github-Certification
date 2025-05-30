# Curso Git e GitHub: Autenticação

Este guia cobre as principais formas de autenticação no GitHub: Nome/Senha/Token, SSH e 2FA. Cada seção traz exemplos práticos e links para a documentação oficial.

---

## Parte Prática 1: Nome, Senha e Token

### 1.1. Nome e Senha (Método Antigo)
- **Uso:** Antes, era possível autenticar no GitHub usando apenas nome de usuário e senha.
- **Exemplo:**  
    ```bash
    git clone https://github.com/usuario/repositorio.git
    # Solicita usuário e senha
    ```
- **Importante:** Este método foi descontinuado para operações via Git em agosto de 2021.

### 1.2. Token de Acesso Pessoal (PAT)
- **Uso:** Substitui a senha para autenticação via HTTPS.
- **Como gerar:**
    1. Vá em [Settings > Developer settings > Personal access tokens](https://github.com/settings/tokens).
    2. Clique em "Generate new token".
    3. Selecione os escopos necessários e salve o token.
- **Exemplo de uso:**
    ```bash
    git clone https://github.com/usuario/repositorio.git
    # Use o token como senha quando solicitado
    ```
- **Documentação:**  
    [Autenticação com token](https://docs.github.com/pt/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token)

---

## Parte Prática 2: SSH

### 2.1. O que é SSH?
- **Uso:** Permite autenticação segura sem digitar senha/token a cada operação.
- **Vantagem:** Mais seguro e prático para uso frequente.

### 2.2. Gerando uma chave SSH
```bash
ssh-keygen -t ed25519 -C "seu-email@exemplo.com"
# Pressione Enter para aceitar o local padrão
```

### 2.3. Adicionando a chave ao GitHub
1. Copie o conteúdo da chave pública:
     ```bash
     cat ~/.ssh/id_ed25519.pub
     ```
2. Vá em [Settings > SSH and GPG keys](https://github.com/settings/keys).
3. Clique em "New SSH key" e cole a chave.

### 2.4. Usando SSH no Git
```bash
git clone git@github.com:usuario/repositorio.git
```

- **Documentação:**  
    [Conectando via SSH](https://docs.github.com/pt/authentication/connecting-to-github-with-ssh)

---

## Parte Prática 3: 2FA (Autenticação em Dois Fatores)

### 3.1. O que é 2FA?
- **Uso:** Adiciona uma camada extra de segurança exigindo um código além da senha/token.

### 3.2. Como ativar 2FA
1. Vá em [Settings > Password and authentication](https://github.com/settings/security).
2. Clique em "Enable two-factor authentication".
3. Siga as instruções para configurar via aplicativo autenticador ou SMS.

### 3.3. Usando 2FA
- **Ao acessar o GitHub:** Será solicitado o código do autenticador.
- **Ao usar Git:** Use tokens de acesso pessoal (PAT), pois nome/senha não funcionam com 2FA.

- **Documentação:**  
    [Configurando 2FA](https://docs.github.com/pt/authentication/securing-your-account-with-two-factor-authentication-2fa)

---

## Resumo

- **Nome/Senha:** Não recomendado, substituído por tokens.
- **Token:** Método padrão para HTTPS.
- **SSH:** Mais seguro e prático para desenvolvedores.
- **2FA:** Recomendado para máxima segurança.
