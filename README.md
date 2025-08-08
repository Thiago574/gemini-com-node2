# Projeto Gemini Chatbot

## Descrição
Este projeto implementa um chatbot interativo utilizando Node.js. O chatbot é capaz de responder a perguntas, fornecer informações e interagir com os usuários de forma dinâmica. Ele utiliza arquivos de texto para armazenar pacotes de informações e políticas, além de recursos estáticos para a interface do usuário.

## Estrutura do Projeto

A estrutura do projeto é organizada da seguinte forma:

```
3751-gemini-com-node-aula05.zip
app.js
chat.js
embedding.js
inicializaChat.js
package.json
Pacotes_Argentina.txt
Pacotes_EUA.txt
Politicas.txt
static/
	css/
		app.css
		reset.css
	img/
		icone-audio.svg
		icone-chatbot.svg
		icone-enviar.svg
		icone-faq.svg
		icone-mais.svg
		icone-perfil.svg
		logo-chatbot.svg
		logo.png
	js/
		app.js
templates/
	chat.html
```

### Principais Arquivos e Pastas

- **app.js**: Arquivo principal que inicializa o servidor e gerencia as rotas.
- **chat.js**: Contém a lógica do chatbot.
- **embedding.js**: Implementa funcionalidades relacionadas a embeddings.
- **inicializaChat.js**: Configurações iniciais do chatbot.
- **package.json**: Gerencia as dependências do projeto.
- **Pacotes_Argentina.txt** e **Pacotes_EUA.txt**: Arquivos de texto com informações sobre pacotes.
- **Politicas.txt**: Contém as políticas do chatbot.
- **static/**: Contém os recursos estáticos como CSS, imagens e JavaScript.
- **templates/**: Contém os templates HTML, como o arquivo `chat.html`.

## Como Executar o Projeto

1. Certifique-se de ter o Node.js instalado em sua máquina.
2. Instale as dependências do projeto executando o comando:
   ```
   npm install
   ```
3. Inicie o servidor com o comando:
   ```
   node app.js
   ```
4. Acesse o chatbot no navegador através do endereço:
   ```
   http://localhost:3000
   ```

## Dependências
As dependências do projeto estão listadas no arquivo `package.json`. Certifique-se de instalar todas antes de executar o projeto.

## Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

## Licença
Este projeto está licenciado sob a licença MIT. Consulte o arquivo LICENSE para mais informações.
