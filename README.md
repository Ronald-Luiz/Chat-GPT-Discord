# Chat-GPT-Discord

Este projeto permite que você crie um bot Discord que utiliza o modelo GPT-3.5 da OpenAI para responder a mensagens de texto em canais específicos. Para executar o projeto, siga os seguintes passos:

### 1. Crie seu bot no Discord:

Acesse [https://discord.com/developers/](https://discord.com/developers/) e crie um bot.

### 2. Crie uma conta na OpenAI e obtenha sua chave API:

Acesse [https://platform.openai.com/](https://platform.openai.com/) para criar uma conta e obter a chave de API necessária.

### 3. Configure as variáveis de ambiente: 

Crie um arquivo `.env` na raiz do projeto e adicione as seguintes configurações:

```
TOKEN=(Cole aqui o token do seu bot do Discord)
OPENAI_KEY=(Cole aqui a chave da API da OpenAI)
```


### 4. Instale as dependências:

No terminal, execute o seguinte comando para baixar as dependências do projeto:

```
npm i -y
```


### 5. Execute o projeto:

Agora, você pode executar o projeto com o seguinte comando:

```
node index.js
```


Certifique-se de que você definiu o ID do canal para o qual deseja que o bot envie mensagens no arquivo index.js na linha 17, como mostrado no exemplo abaixo:

```
const CHANNELS = ['SEU_ID_DE_CANAL_AQUI'];
```
