
# TCP/IP

## O que é TCP/IP?

TCP/IP é um conjunto de protocolos que permite a comunicação entre dispositivos conectados em uma rede, incluindo a internet.

O nome vem de dois protocolos importantes:

- **IP (Internet Protocol):** responsável pelo endereçamento e encaminhamento dos pacotes.
- **TCP (Transmission Control Protocol):** responsável por organizar a transmissão e garantir a entrega confiável dos dados enquanto a conexão funciona.

## 1. IP (Internet Protocol)

O IP é responsável por identificar os dispositivos por meio de endereços IP e ajudar a encaminhar os pacotes até o destino.

**Exemplo de endereço IPv4:**

```text
192.168.1.10
```

## 2. TCP (Transmission Control Protocol)

O TCP fornece uma comunicação confiável entre dois dispositivos.

Suas principais funções são:

- Dividir os dados em segmentos.
- Controlar a ordem dos dados recebidos.
- Detectar perdas durante a transmissão.
- Solicitar o reenvio de dados quando necessário.

Isso permite que os dados cheguem organizados ao destino, desde que a conexão consiga ser mantida.

## 3. Portas

As portas identificam qual serviço ou aplicação deve receber os dados em um dispositivo.

**Exemplo:**

```text
192.168.1.10:443
```

Nesse exemplo:
- `192.168.1.10` é o endereço IP.
- `443` é a porta utilizada.

### Portas comuns

| Porta | Protocolo/serviço |
|---|---|
| 80 | HTTP |
| 443 | HTTPS |
| 22 | SSH |
| 21 | FTP |
| 3306 | MySQL |

## 4. Localhost

`localhost` é um nome utilizado para representar o próprio computador.

É muito utilizado durante o desenvolvimento de aplicações.

**Exemplo:**

```text
http://localhost:3000
```

Nesse endereço:
- `localhost` representa o próprio computador.
- `3000` é a porta em que a aplicação está sendo executada.

## 5. Como TCP/IP funciona na prática?

Imagine que você acessa um site:

1. O navegador precisa localizar o servidor.
2. O IP permite identificar o destino da comunicação.
3. O TCP estabelece e controla a conexão.
4. Os dados são transmitidos pela rede.
5. O navegador recebe e interpreta as informações.

## Resumo

| Elemento | Responsabilidade |
|---|---|
| IP | Endereçamento e encaminhamento dos pacotes |
| TCP | Transmissão confiável e organizada |
| Porta | Identificação do serviço ou aplicação |
| Localhost | Representa o próprio computador |

> **Resumo:** TCP/IP é a base da comunicação na internet. O IP ajuda a encontrar o destino, enquanto o TCP organiza e controla a entrega dos dados.
