# Peer to peer Chat Simples

Este é um exemplo de aplicativo de chat simples usando o Peer to Peer. Ele permite que dois usuários se conectem e enviem mensagens um para o outro em tempo real.
<br>
<a href="https://claudioss01.github.io/conexao-peer-to-peer-de-um-unico-documento-usando-html-e-javascript/">veja funcionando aqui</a>
<br>
## Como usar

1. Não precisa baixar nada, nem mesmo iniciar em servidor
2. Abra o arquivo `index.html` em seu navegador da web.
3. No primeiro navegador, clique no botão "Conectar". Isso iniciará o peer e exibirá o ID do peer.
4. No segundo navegador, abra o mesmo arquivo `index.html`.
5. Clique no botão "Conectar" novamente para iniciar o segundo peer.
6. Agora, clique no botão "Mostrar Código" em ambos os navegadores para visualizar o ID do peer.
7. Copie o ID do primeiro navegador e cole-o no segundo navegador no campo "ID Remoto" e vice-versa.
8. Clique no botão "Conectar" em ambos os navegadores para estabelecer a conexão entre os peers.
9. Agora você pode enviar mensagens digitando no campo de entrada e clicando no botão "Enviar". As mensagens serão exibidas na área de chat abaixo.

Certifique-se de que os dois navegadores estejam abertos simultaneamente para que a comunicação ocorra adequadamente.

## Observações

- O código fornecido usa IDs aleatórios para simplificar o processo de conexão. No entanto, é possível usar um ID fixo predefinido para permitir que os peers se conectem sem a necessidade de inserir manualmente os códigos de ID. Basta substituir o valor `null` na criação do objeto Peer pelo ID fixo desejado.
- Este é apenas um exemplo básico para ilustrar o uso do Peer to Peer. Para aplicativos mais complexos ou seguros, considere adicionar autenticação, criptografia ou outras medidas de segurança adequadas.



