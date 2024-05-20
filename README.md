#Chatbot com Google AI usando GenerativeAI
Este código demonstra como criar um chatbot interativo usando o Google GenerativeAI e o modelo Gemini-1.0-pro. O GenerativeAI é um serviço do Google Cloud que permite a geração de texto de alta qualidade e personalizável.

Pré-requisitos
Uma conta do Google Cloud com a API GenerativeAI habilitada.
Chave de API do Google Cloud Project habilitada para o serviço GenerativeAI.
Instalação
Certifique-se de ter o Python 3.x instalado em seu sistema.
Execute o seguinte comando em seu terminal para instalar a biblioteca google-generativeai:
pip install google-generativeai
Instruções
Crie um arquivo de chave de API:

Acesse o Google Cloud Console.
Selecione ou crie um projeto do Google Cloud.
Habilite a API GenerativeAI para o projeto selecionado.
Crie uma credencial e baixe a chave de API como um arquivo JSON.
Armazene a chave de API com segurança.
Substitua a sua chave de API:

Abra o arquivo Python (Chat_GoogleAI.ipynb neste exemplo).
Localize a linha GOOGLE_API_KEY e substitua "digite_sua_api_key" pela sua chave de API real obtida no passo anterior.
Executar o código:

Abra o arquivo Chat_GoogleAI.ipynb em um ambiente Jupyter Notebook ou Colab.
Siga as instruções nas células do notebook para iniciar o chatbot.
Como funciona
O código define um modelo GenerativeModel usando o gemini-1.0-pro e as configurações de geração e segurança especificadas.

Durante a execução, o código:

Inicia um chat com o modelo.
Solicita uma entrada do usuário (prompt).
Envia o prompt para o modelo e recebe a resposta gerada.
Exibe a resposta do modelo para o usuário.
Repete as etapas 2 a 4 até que o usuário digite "fim" para encerrar o chat.
A função to_markdown formata a resposta do modelo para melhor legibilidade, indenta o texto e adiciona marcadores.

Saída de exemplo
Ao executar o código e interagir com o chatbot, você verá uma saída semelhante a esta:

Esperando Promt: Olá
Resposta: Olá! Como posso te ajudar hoje?
Esperando Promt: Qual é o tempo em São Paulo?
Resposta: Não tenho certeza do tempo atual em São Paulo, mas posso te ajudar a encontrar a previsão do tempo online.
Esperando Promt: fim
Este é um exemplo simples, mas você pode se comunicar com o chatbot em português sobre diversos assuntos, de acordo com as capacidades do modelo gemini-1.0-pro.
