HTTP(HyperText Transfer Protocol) - Protocolo para acessar uma página na web, são regras que definem como um navegador conversa com um servidor.

Navegador - Chrome - Faz a requisição HTTP
Servidor - GitHub - Espera receber a requisição



Porém o HTTP não criptografa os dados, caso vc digite uma senha e usuário, esses dados viajariam em textos claros pela rede, e serial facilmente interceptados, por isso surgiu o HTTPs

HTTP não guarda memória ( se uma pessoa faz requisições, o HTTP não lembra que foram todas do mesmo usuário).



Métodos HTTP

Get - Busca informações;

Post - Envia os dados;

Put - Atualiza tudo;

Patch - Atualiza só uma parte;

Delete - Deleta;


Status Codes(Códigos de resposta)

200 - Indica que deu tudo certo;

201 - Alguma coisa foi criada;

301 - A página mudou de endereço;

400 - Erro na requisição;

401 - Não autenticado - Faça login;

403 - Você não tem autorização;

404 - Página não encontrada;

500 - Erro no servidor; 


Ex: 

Eu faço login;

Navegador: POST - /login (senha, usuário)

Servidor: Verifica o banco de dados,     se estiver certo: 200 ou 201;     se não estiver certo: 401;


Onde ver isso: Abra qualquer site, pressione F12, vá em Network, Você vera diversas requisições sendo feitas em tempo real; 
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------

HTTPs(HyperText Transfer Protocol Secure) - A sua diferença para o HTTP, é que tudo é criptografado.

Ex:

Senha: 12345

com o HTTP: 12345
com o HTTPs: uw#gfy%ewuu273@

Todo o conteúdo fica embaralhado, fazendo com que terceiros não entendam os dados.

HTTPs = HTTP + SSL/TLS(hoje em dia se usa mais o TLS)

Certificado SSL/TLS - ele indica quem é o dono do site, pra qual domínio ele vale, dono do certificado e etc.

Como funciona quando abrir o site HTTPs:  

Chrome -> Servidor -> "Você realmente é o Google" -> O servidor manda o certificado -> Chrome verifica -> Tudo Certo -> Cria um conexão criptografada(para proteger os dados) -> e agora vem o HTTP
| essa etapa é chamada de handshake TLS

