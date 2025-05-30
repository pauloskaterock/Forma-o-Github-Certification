🎯 O que são Releases no GitHub?
Um release no GitHub é uma versão oficial de um software, gerada a partir de uma tag. Ele ajuda os usuários a baixarem uma versão estável do projeto, incluindo notas, binários e arquivos necessários.

🎯 Por que usar releases? 
✅ Permite marcar versões estáveis do código, como v1.0.0. 
✅ Facilita a distribuição do software, incluindo arquivos .zip ou .tar.gz. 
✅ Ajuda os usuários a entenderem o que mudou entre versões.

🏷️ Exemplo Real: Criando um Release
Imagine que você desenvolveu um sistema de login e agora quer publicar a versão 1.0.0 para que outros possam usá-la.

✅ Passo a Passo para Criar um Release

1️⃣ Crie uma tag no Git (se ainda não tiver uma):

sh
git tag -a v1.0.0 -m "Primeira versão do sistema de login"
git push origin v1.0.0

2️⃣ Vá para o GitHub e acesse seu repositório. 
3️⃣ Clique em "Tags" → "Create a new release". 
4️⃣ Dê um nome à versão (exemplo: "Sistema de Login v1.0.0"). 
5️⃣ Escreva um resumo das mudanças, como:

✅ Adicionada autenticação JWT

✅ Melhorado suporte a login social (Google, Facebook) 

6️⃣ Adicione arquivos extras (se necessário, como um executável). 
7️⃣ Clique em "Publish Release"! 🎉

🔍 Como Visualizar Releases Existentes?
Se quiser ver todas as versões já lançadas, basta acessar a aba "Releases" no repositório GitHub ou usar o terminal:

sh
git tag
Isso lista todas as versões que já foram criadas.

🔄 Baixando uma Versão Específica do Código
Se precisar obter um release específico, basta rodar:

sh
git checkout tags/v1.0.0 -b minha-versao-1
Isso cria um branch baseado na versão v1.0.0, permitindo que você explore ou modifique essa versão.

🎭 Resumo Rápido
✅ Releases são versões oficiais do código, geradas a partir de tags. 
✅ Podem incluir notas, arquivos binários e changelogs. 
✅ Criamos releases no GitHub via "Tags" → "Create Release". 
✅ Usuários podem baixar versões específicas facilmente.