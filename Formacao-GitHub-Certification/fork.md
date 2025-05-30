🔥 O que é um Fork no GitHub?
Um fork é uma cópia independente de um repositório do GitHub que fica na sua conta. Ele permite que você modifique o código sem alterar o original. Depois, você pode sugerir mudanças ao projeto original por meio de um Pull Request.

🎯 Por que usar um Fork?

Contribuir para projetos Open Source sem alterar o repositório principal.

Criar versões alternativas de um projeto.

Experimentar mudanças sem afetar o código original.

✏️ Exemplo Real: Fork na Prática
Imagine que existe um projeto chamado "calculadora" no GitHub, criado por outra pessoa. Você quer adicionar uma nova funcionalidade sem modificar o projeto original.

✅ Passo a Passo para fazer um Fork
1️⃣ Acesse o repositório que deseja copiar (exemplo: github.com/projeto/calculadora). 
2️⃣ Clique no botão "Fork" no topo direito da página. 
3️⃣ Agora o repositório está na sua conta (github.com/seu-usuario/calculadora).

Agora você tem uma cópia do projeto e pode editá-la livremente! 🛠️

🔄 Como Enviar Melhorias para o Projeto Original?
Se você adicionou uma funcionalidade e quer sugerir ao autor do projeto original, siga esses passos:

1️⃣ Clone seu fork para seu computador:

sh
git clone https://github.com/seu-usuario/calculadora.git
2️⃣ Faça alterações no código:

sh
echo "Nova funcionalidade" >> novas_funcoes.py
3️⃣ Envie as mudanças para seu repositório fork:

sh
git add .
git commit -m "Adicionei uma nova funcionalidade"
git push origin main
4️⃣ Crie um Pull Request no GitHub para sugerir suas mudanças ao autor original!

🎭 Resumo Rápido
✅ Fork cria uma cópia independente de um repositório GitHub. ✅ Você pode modificar essa cópia sem afetar o  original. ✅ Se quiser sugerir melhorias, basta criar um Pull Request.