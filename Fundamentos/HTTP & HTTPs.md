
# HTTP e HTTPS

## 1. HTTP

HTTP significa **Hypertext Transfer Protocol**. É um protocolo utilizado para permitir a comunicação entre clientes e servidores na web.

### Como funciona?

1. O usuário acessa um site pelo navegador.
2. O navegador envia uma requisição HTTP ao servidor.
3. O servidor processa a solicitação.
4. O servidor retorna uma resposta ao navegador.

### Cliente e servidor

- **Cliente:** geralmente é o navegador, que envia requisições.
- **Servidor:** recebe as requisições, processa e envia respostas.

### Características do HTTP

- É baseado em requisições e respostas.
- É um protocolo sem estado (*stateless*): cada requisição é independente por padrão.
- Utiliza métodos para indicar o tipo de operação desejada.

### Principais métodos HTTP

| Método | Função |
|---|---|
| GET | Buscar informações |
| POST | Enviar dados ou criar um recurso |
| PUT | Substituir um recurso |
| PATCH | Atualizar parte de um recurso |
| DELETE | Excluir um recurso |

### Códigos de status HTTP

| Código | Significado |
|---|---|
| 200 | Requisição realizada com sucesso |
| 201 | Recurso criado |
| 301 | Redirecionamento permanente |
| 400 | Requisição inválida |
| 401 | Não autenticado |
| 403 | Acesso recusado |
| 404 | Recurso não encontrado |
| 500 | Erro interno do servidor |

## 2. HTTPS

HTTPS significa **Hypertext Transfer Protocol Secure**. É a versão segura do HTTP.

Ele utiliza o protocolo TLS para proteger a comunicação entre cliente e servidor.

### Como funciona?

O HTTPS utiliza criptografia para proteger os dados durante a transmissão.

Antes de iniciar a comunicação protegida, cliente e servidor realizam uma negociação de segurança chamada *TLS Handshake*.

Durante esse processo, são estabelecidos os parâmetros necessários para a conexão segura e o servidor apresenta seu certificado digital.

### Certificado digital

O certificado digital ajuda a confirmar a identidade do servidor e contém informações como:

- Nome do domínio.
- Chave pública.
- Autoridade certificadora responsável.
- Período de validade.

### HTTP x HTTPS

| HTTP | HTTPS |
|---|---|
| Sem criptografia própria | Comunicação protegida por TLS |
| Geralmente utiliza a porta 80 | Geralmente utiliza a porta 443 |
| Dados não são protegidos por criptografia do próprio HTTP | Dados são criptografados durante a transmissão |

## Importância do HTTPS

- Protege informações transmitidas.
- Dificulta a leitura dos dados por terceiros.
- Ajuda a verificar a identidade do servidor.
- É essencial para operações como logins e pagamentos.

> **Resumo:** HTTP permite a comunicação entre navegador e servidor. HTTPS utiliza HTTP protegido por TLS, oferecendo mais segurança durante a transmissão dos dados.


## 3. TLS (Transport Layer Security)

TLS significa **Transport Layer Security**. É um protocolo de segurança responsável por proteger a comunicação entre clientes e servidores na internet.

Ele fornece três propriedades principais:

- **Criptografia:** impede que terceiros leiam os dados transmitidos.
- **Autenticação:** ajuda a verificar a identidade do servidor por meio de certificados digitais.
- **Integridade:** permite detectar alterações nos dados durante a transmissão.

### Como funciona o TLS?

Antes de iniciar a comunicação protegida, cliente e servidor realizam um processo chamado **TLS Handshake**.

De forma simplificada:

1. O cliente solicita uma conexão segura.
2. O servidor apresenta seu certificado digital.
3. O cliente verifica a validade e a identidade do certificado.
4. Cliente e servidor negociam os parâmetros de segurança e estabelecem chaves de sessão.
5. A comunicação passa a acontecer de forma criptografada.

### Certificado digital

O certificado digital é utilizado para ajudar a confirmar a identidade do servidor.

Ele contém informações como:

- Nome do domínio.
- Chave pública.
- Autoridade certificadora.
- Período de validade.

### TLS x SSL

SSL (Secure Sockets Layer) foi um protocolo de segurança anterior ao TLS.

O TLS surgiu como seu sucessor e é o padrão utilizado atualmente.

Apesar de muitas pessoas ainda utilizarem o termo "certificado SSL", os sites modernos utilizam TLS.

### Relação entre HTTP, HTTPS e TLS

- **HTTP:** protocolo de comunicação entre cliente e servidor.
- **TLS:** protocolo responsável por proteger a comunicação.
- **HTTPS:** HTTP executado sobre uma conexão protegida por TLS.

> **Resumo:** TLS protege a comunicação na internet por meio de criptografia, autenticação e integridade dos dados. É a tecnologia de segurança utilizada pelo HTTPS.

