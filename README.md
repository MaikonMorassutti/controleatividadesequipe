Dashboard de Controle de Indicadores de Processos

🚀 Sobre o Projeto

Este é um dashboard interativo e completo para o controle e visualização de indicadores de processos industriais. A ferramenta foi desenvolvida para ser uma solução standalone (autônoma), funcionando em um único arquivo HTML, e utiliza o Firebase como backend para armazenamento de dados em tempo real.

O objetivo é centralizar informações cruciais da equipe e dos processos, como status de atividades, metas, avaliações de qualidade (5S, TPM), projetos de melhoria contínua (Kaizen) e competências da equipe, tudo em uma interface visualmente rica e intuitiva.

✨ Principais Funcionalidades
📊 Dashboard Visual: Gráficos dinâmicos e interativos para acompanhar os principais KPIs (Indicadores-Chave de Desempenho).

📝 Gestão de Atividades: Sistema completo de CRUD (Criar, Ler, Atualizar, Deletar) para atividades da equipe e do gestor.

📈 Controle de Metas: Defina e acompanhe metas mensais para colaboradores em diferentes frentes (ITs, SAPs, Avaliações).

✅ Lançamentos de Avaliações: Formulários dedicados para registrar avaliações de 5S e TPM.

💰 Controle de Kaizen: Registre projetos de melhoria contínua e visualize o saving (economia) acumulado.

👥 Matriz de Competências: Visualize de forma clara as habilidades e responsabilidades de cada colaborador por atividade.

🔍 Filtros Dinâmicos: Filtre os dados dos gráficos e tabelas por colaborador, período, setor, máquina e mais.

📱 Design Responsivo: Interface adaptável para uso em desktops, tablets e celulares.

🛠️ Tecnologias Utilizadas
Frontend:

HTML5

Tailwind CSS para estilização moderna e responsiva.

JavaScript (ES6 Modules) para toda a lógica e interatividade.

Banco de Dados:

Google Firebase (Firestore) como backend NoSQL em tempo real.

Visualização de Dados:

Chart.js para a criação dos gráficos.

chartjs-adapter-date-fns para manipulação de datas nos gráficos.

⚙️ Como Utilizar
Para rodar este projeto, você só precisa de um navegador web e uma conta no Firebase.

Clone o Repositório:

git clone https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git

Configure o Firebase:

Crie um novo projeto no console do Firebase.

No seu projeto, crie um banco de dados Firestore.

Vá para as configurações do projeto (Project Settings) e, na aba General, adicione um novo aplicativo Web.

O Firebase fornecerá um objeto de configuração firebaseConfig. Copie este objeto.

Atualize o Código:

Abra o arquivo index.html.

Localize a seção de script no final do arquivo e cole o seu objeto firebaseConfig no local indicado:

// #############################################################################
// ## IMPORTANTE: COLE SEU OBJETO DE CONFIGURAÇÃO DO FIREBASE AQUI             ##
// #############################################################################
const firebaseConfig = {
    apiKey: "SUA_API_KEY",
    authDomain: "SEU_AUTH_DOMAIN",
    projectId: "SEU_PROJECT_ID",
    storageBucket: "SEU_STORAGE_BUCKET",
    messagingSenderId: "SEU_MESSAGING_SENDER_ID",
    appId: "SUA_APP_ID"
};
// #############################################################################

Pronto!

Abra o arquivo index.html no seu navegador para começar a usar o dashboard. Os dados que você inserir serão salvos no seu projeto Firebase.

🖼️ Visualização
Aqui você pode adicionar um screenshot ou um GIF do seu dashboard em ação!

🤝 Contribuições
Contribuições são bem-vindas! Se você tem alguma ideia para melhorar este projeto, sinta-se à vontade para criar um fork e abrir um pull request.

Faça um Fork do projeto.

Crie uma nova Branch (git checkout -b feature/sua-feature).

Faça o Commit de suas mudanças (git commit -m 'Adiciona sua-feature').

Faça o Push para a Branch (git push origin feature/sua-feature).

Abra um Pull Request.

📄 Licença
Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.
