
# URL (Uniform Resource Locator)

## O que é URL?

URL é a sigla para **Uniform Resource Locator**. É o endereço utilizado para localizar um recurso na internet, como páginas, imagens, vídeos, arquivos e endpoints de APIs.

Uma URL é formada por diferentes componentes que identificam como e onde um recurso pode ser acessado.

## 1. Estrutura de uma URL

Exemplo:

```text
https://www.exemplo.com:443/produtos?id=10#detalhes
```

| Componente | Exemplo | Função |
|---|---|---|
| Protocolo | `https://` | Define como a comunicação será realizada |
| Domínio | `www.exemplo.com` | Identifica o endereço do site |
| Porta | `:443` | Indica a porta de comunicação |
| Caminho | `/produtos` | Indica o recurso solicitado |
| Query String | `?id=10` | Envia parâmetros adicionais |
| Fragmento | `#detalhes` | Indica uma seção específica da página |

## 2. Principais componentes

### Protocolo

Define o protocolo utilizado para acessar o recurso.

- `http://` - Comunicação HTTP.
- `https://` - Comunicação HTTP protegida por TLS.

### Domínio

É o nome utilizado para localizar um site.

Exemplos:
- `google.com`
- `github.com`
- `youtube.com`

O DNS ajuda a encontrar o endereço IP associado ao domínio.

### Porta

Indica o ponto de comunicação utilizado pelo serviço.

Portas comuns:

| Porta | Serviço |
|---|---|
| 80 | HTTP |
| 443 | HTTPS |
| 3000 | Frequentemente utilizada em desenvolvimento local |

A porta pode ser omitida quando é a porta padrão do protocolo.

### Caminho (Path)

Indica qual recurso está sendo solicitado dentro do site.

Exemplo:

```text
https://loja.com/produtos/camiseta
```

Nesse caso, `/produtos/camiseta` é o caminho do recurso.

### Query String

Permite enviar parâmetros adicionais por meio da URL.

Exemplo:

```text
https://loja.com/produtos?id=10&categoria=roupas
```

- `id=10` identifica um produto.
- `categoria=roupas` indica uma categoria.
- `&` separa os parâmetros.

### Fragmento (Hash)

Indica uma seção específica de uma página.

Exemplo:

```text
https://site.com/artigo#introducao
```

O navegador pode utilizar `#introducao` para navegar até um elemento específico da página.

O fragmento normalmente não é enviado ao servidor na requisição HTTP.

## 3. URL absoluta e relativa

- **URL absoluta:** contém o endereço completo do recurso.
- **URL relativa:** utiliza um caminho em relação à localização atual.

Exemplo em HTML:

```html
<!-- URL absoluta -->
<a href="https://github.com">GitHub</a>

<!-- URL relativa -->
<a href="/sobre.html">Sobre</a>
```

## 4. URL x Domínio

É importante não confundir os dois conceitos:

- **Domínio:** identifica o endereço de um site.
- **URL:** representa o endereço de um recurso.

Exemplo:

```text
Domínio:
github.com

URL:
https://github.com/openai
```

O domínio faz parte da URL, mas não representa toda a URL.

> **Resumo:** a URL é o endereço completo de um recurso na internet. Ela pode conter protocolo, domínio, porta, caminho, parâmetros e fragmento.
