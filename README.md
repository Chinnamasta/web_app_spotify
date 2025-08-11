### 🎵 Web App Spotify
Este é um projeto de um Web App desenvolvido com Python e Streamlit que se conecta à API do Spotify para buscar e exibir informações sobre artistas e suas músicas mais populares. É uma ótima maneira de explorar a API e criar uma interface interativa para seus dados.

### ✨ Recursos 
- Busca de Artistas: Encontre qualquer artista do banco de dados do Spotify.
- Detalhes do Artista: Veja o nome e o nível de popularidade de um artista.
- Top Músicas: Descubra as 10 músicas mais populares de um artista, com links diretos para ouvi-las no Spotify.
- Interface Simples: Graças ao Streamlit, a aplicação é fácil de usar e de navegar.

### 🚀 Como Rodar o Projeto
Siga estes passos para configurar e executar o projeto na sua máquina local.

1. Pré-requisitos
Certifique-se de que você tem o Python (versão 3.6 ou superior) e o pip instalados.

2. Chaves da API do Spotify
Você precisará de um Client ID e um Client Secret para se autenticar na API do Spotify.
- Vá para o Dashboard de Desenvolvedor do Spotify.
- Faça login ou crie uma conta.
- Clique em "Create an App" e preencha as informações necessárias.
- Após a criação, você encontrará o Client ID e o Client Secret do seu aplicativo. Anote-os!

3. Configuração do Ambiente
- Clone o repositório:
git clone [URL_DO_SEU_REPOSITORIO]
cd [pasta-do-repositorio]
- Crie um ambiente virtual (recomendado):
python -m venv .venv
- Ative o ambiente virtual:
Windows: .\.venv\Scripts\activate
macOS/Linux: source ./.venv/bin/activate

4. Instale as dependências:
pip install streamlit requests python-dotenv

5. Crie o arquivo .env:
Na raiz do seu projeto, crie um arquivo chamado .env e adicione suas chaves da API do Spotify:
SPOTIFY_CLIENT_ID="seu_client_id"
SPOTIFY_CLIENT_SECRET="seu_client_secret"
Substitua "seu_client_id" e "seu_client_secret" pelas suas chaves reais.

6. Execute o aplicativo:
Com o ambiente virtual ativado, execute o seguinte comando no terminal:
streamlit run web_app_spotify.py

### 🎤🎸 O aplicativo será aberto automaticamente no seu navegador. Agora é só buscar seus artistas favoritos! 

### 🛠️ Tecnologias Utilizadas:
- Python
- Streamlit
- Requests
- python-dotenv

Contribuições 🤝
Contribuições, sugestões e melhorias são sempre bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request.
