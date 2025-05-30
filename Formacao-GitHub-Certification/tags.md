🔖 O que são Tags no Git?
Uma tag no Git é como um marcador especial que aponta para um commit específico. Elas são frequentemente usadas para criar versões do software, como v1.0.0, facilitando a organização e o histórico de lançamentos.

🎯 Por que usar tags? ✔ Permite marcar versões do projeto (Exemplo: v1.0, v2.1). ✔ Ajuda a organizar marcos importantes, como lançamentos oficiais. ✔ Facilita reverter para uma versão específica no futuro.

🏷️ Tipos de Tags no Git
1️⃣ Tags Anotadas (git tag -a):

Contêm mensagens e informações extras (como autor e data).

São mais recomendadas para controle de versões.

2️⃣ Tags Leves (git tag):

Apenas marcam um commit, sem informações adicionais.

Útil para marcações temporárias ou rápidas.

✏️ Exemplo Prático de Uso de Tags
Imagine que você terminou uma versão estável do seu projeto e quer marcá-la como "v1.0.0".

✅ Criando uma Tag
sh
git tag -a v1.0.0 -m "Primeira versão estável"
🔹 Isso cria uma tag anotada chamada v1.0.0 no último commit.

🔄 Listando Todas as Tags
sh
git tag
🔹 Exibe todas as tags já criadas no seu repositório.

⏳ Verificando Detalhes de uma Tag
sh
git show v1.0.0
🔹 Mostra detalhes do commit associado à tag.

🚀 Enviando Tags para o GitHub
sh
git push origin v1.0.0
🔹 Isso envia apenas essa tag para o repositório remoto. Se quiser enviar todas as tags, use:

sh
git push --tags
🔄 Removendo uma Tag
🔹 Se precisar deletar uma tag localmente:

sh
git tag -d v1.0.0
🔹 Para removê-la do GitHub:

sh
git push origin --delete v1.0.0


🎭 Resumo Rápido

✅ Tags ajudam a marcar versões importantes do código. 
✅ Use git tag -a para tags anotadas com detalhes extras. 
✅ Envie tags para GitHub com git push origin v1.0.0. 
✅ Liste tags com git tag e remova com git tag -d nome-da-tag.