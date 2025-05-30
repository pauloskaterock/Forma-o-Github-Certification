🔹 Níveis de Administração no GitHub
🏆 1. Administração de Repositórios
Em um repositório GitHub, as permissões são divididas em cinco níveis principais:

Nível	Permissões
Proprietário (Owner)	Controle total: editar configurações, excluir repositório, gerenciar usuários.
Admin	Pode gerenciar configurações e acesso, mas não excluir o repositório.
Mantenedor (Maintainer)	Gerencia Issues, Pull Requests e revisa código.
Colaborador (Collaborator)	Pode alterar código, criar Issues e enviar Pull Requests.
Leitor (Read-Only)	Apenas visualiza o código e Issues.

📌 Exemplo Real: Se você tem um repositório open-source e quer permitir que outros desenvolvedores contribuam sem alterar configurações, basta adicioná-los como Colaboradores!

🔗 Documentação Oficial: Gerenciamento de Acesso a Repositórios

🏢 2. Administração de Organizações
GitHub permite criar organizações, onde múltiplos repositórios são gerenciados por equipes com diferentes níveis de acesso.

🚀 Funções dentro de uma Organização
Função	Permissões
Owner (Proprietário)	Controle total da organização: adicionar/remover membros, gerenciar repositórios e times.
Admin	Gerencia repositórios e configurações, mas não pode excluir a organização.
Member (Membro padrão)	Pode interagir com repositórios públicos e times, mas tem limitações.
📌 Exemplo Real: Se você tem uma startup e quer gerenciar equipes de desenvolvimento separadas, pode criar times dentro da organização e definir permissões específicas para cada grupo.

🔗 Documentação Oficial: Gerenciando Membros de Organizações

🔗 3. Administração de Times dentro de Organizações
Dentro de uma Organização GitHub, você pode criar times e gerenciar acesso aos repositórios.

📌 Tipos de Times
Tipo de Time	Descrição
Time Privado	Apenas membros do time podem vê-lo.
Time Visível	Qualquer membro da organização pode ver e solicitar entrada.
Time Pai/Subtimes	Permite hierarquias dentro de equipes.
📌 Exemplo Real: Na sua empresa, pode criar um time frontend-devs para cuidar do React e um time backend-devs para cuidar do Rails!

🔗 Documentação Oficial: Gerenciando Times no GitHub

🔐 4. Administração de Segurança e Proteção
Os administradores podem definir proteções para o código:

✅ Branches Protegidas – Evita alterações diretas no código principal 
✅ Revisão Obrigatória – Exige aprovação antes de mesclar mudanças 
✅ Autenticação em Dois Fatores – Requer verificação extra ao fazer login ✅ Tokens de Acesso – Controle avançado para scripts e integrações

📌 Exemplo Real: Para evitar erros em um projeto crítico, você pode configurar uma Branch Protegida que exige revisão antes de aceitar mudanças!

🔗 Documentação Oficial: Configurando Proteções de Branch