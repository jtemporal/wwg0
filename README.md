# Women Who Go Sampa - Encontro 0

Primeira palestra em Go \o/

E vai ser live coding feelings

## Estrutura incial

- Declaração de pacote
- Importar pacotes: [`fmt`](https://golang.org/pkg/fmt/)
- `func main()`

Tudo em Go funciona em pacotes, você pode ter vários pacotes desde que eles estejam separados em diretórios.

Para organizar e reaproveitar podemos separar tudo em pacotes e importar eles. Também utilizamos `import` para ter acesso aos pacotes embutidos do próprio Go como o pacote de formatação `fmt`.

E o pacote `main` espera a existência de uma função `main()`.

## Rodando e buildando

- go run main.go
- go build
- ./wwg0

Para executar o código podemos só usar o comando `run` do Go que faz um build numa pasta temporária e mostra pra você o resultado. Ou você pode criar o executável do seu pacote com o comando `build`.
