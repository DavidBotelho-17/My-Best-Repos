My Best Repos 

My Best Repos é uma aplicação web interativa desenvolvida com JavaScript Vanilla, HTML5 e CSS3. O objetivo principal da aplicação é permitir que os usuários pesquisem por repositórios públicos no GitHub, salvem seus repositórios favoritos no navegador e gerenciem as informações do seu perfil pessoal.

💻 Funcionalidades

1. 🔍 Pesquisa de Repositórios

Consulta em tempo real à API pública do GitHub.

Exibição de informações detalhadas de cada repositório:

Nome do repositório.

Proprietário (usuário ou organização).

Descrição.

Linguagem principal utilizada.

Quantidade de estrelas (⭐).

Link direto para acesso no GitHub.

2. ⭐ Gerenciamento de Favoritos

Adição e remoção de repositórios da lista de favoritos com um único clique.

Persistência total dos dados via localStorage (os favoritos não são perdidos ao fechar ou recarregar a página).

Atualização imediata da interface ao remover itens.

3. 👤 Perfil do Usuário

Exibição e edição das informações de perfil:

Nome completo.

E-mail.

Username do GitHub.

Salvamento automático do perfil no localStorage.

4. ⚙️ Tratamento de Estados e Erros

Feedback de Carregamento: Indicador visual durante as requisições à API.

Pesquisa Sem Resultados: Mensagem clara caso a busca não retorne nenhum repositório.

Favoritos Vazios: Estado amigável para quando o usuário ainda não possui favoritos salvos.

Tratamento de Erros: Exibição de mensagens amigáveis em caso de falhas na comunicação com a API do GitHub.

🛠️ Tecnologias Utilizadas

HTML5: Estrutura semântica da aplicação.

CSS3: Estilização responsiva e componentes de interface.

JavaScript (ES6+): Manipulação do DOM, Fetch API para requisições assíncronas e localStorage para persistência de dados local.

🚀 Como Executar o Projeto

Clone o repositório:

git clone https://github.com/DavidBotelho-17/My-Best-Repos.git


Acesse a pasta do projeto:

cd My-Best-Repos


Abra o projeto:

Abra o arquivo index.html em qualquer navegador web, ou utilize a extensão Live Server no VS Code.

📄 Licença

Este projeto está sob a licença MIT - veja o arquivo de licença para mais detalhes.

Desenvolvido por David Botelho.