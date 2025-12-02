🔐 Controle de Permissões MySQL – GRANT para o Usuário ALUNO

Bem-vindo ao repositório dedicado ao estudo de permissões e segurança no MySQL!
Aqui você encontra um script completo mostrando como conceder diferentes tipos de privilégios ao usuário 'ALUNO'@'localhost'.
Ideal para quem está aprendendo administração de banco e quer visualizar como cada permissão funciona na prática. 🚀

🧩 O que este script ensina

✨ Concessão de permissões específicas:

🔄 UPDATE

❌ DELETE

➕ INSERT

🔍 SELECT

✨ Permissões globais em todos os bancos (*.*)
✨ Combinação de privilégios (ex.: SELECT, INSERT)
✨ SELECT limitado por colunas, permitindo acesso apenas ao necessário
✨ Organização e boas práticas para controle de usuários

📘 Por que isso é útil?

Esse material ajuda a entender como funciona a “trava e chave” do MySQL 🗝️
Você aprende:

Como limitar o que um usuário pode fazer

Como proteger tabelas e dados sensíveis

Como administrar acessos sem comprometer a segurança

Como aplicar GRANT de maneira consciente

🛠️ Como usar

Certifique-se de ter criado o usuário ALUNO:
CREATE USER 'ALUNO'@'localhost' IDENTIFIED BY 'senha';

Copie o script e execute no MySQL Workbench, CLI ou ferramenta similar.

Teste as permissões e observe como cada GRANT modifica o nível de acesso.

Simples, direto e muito útil para prática profissional. ⚙️

📦 Objetivo do repositório

Criar um ambiente de estudo claro e acessível, ajudando estudantes e iniciantes a dominar permissões e segurança em banco de dados de forma prática e visual.
