# Aula 04 — mkdir, ls e operadores no terminal

Nesta aula vamos continuar praticando os primeiros comandos do terminal Linux e aprender como executar mais de um comando em sequência.

## Objetivo da aula

Entender como combinar comandos no terminal utilizando os operadores `&&` e `;`, observando a diferença entre uma execução condicionada ao sucesso do comando anterior e uma execução sequencial.

## Conteúdo da aula

- Revisão do comando `mkdir`
- Revisão do comando `ls`
- Execução de mais de um comando na mesma linha
- Operador `&&`
- Operador `;`
- Diferença entre `&&` e `;`

## Comandos utilizados

### Criar um diretório

```bash
mkdir projeto
```

O comando `mkdir` cria um novo diretório.

---

### Listar o conteúdo do diretório atual

```bash
ls
```

O comando `ls` exibe o conteúdo do diretório em que estamos trabalhando.

---

### Utilizando o operador `&&`

```bash
mkdir projeto && ls
```

O operador `&&` permite executar o segundo comando somente se o primeiro terminar com sucesso.

Neste exemplo:

1. `mkdir projeto` tenta criar o diretório `projeto`.
2. Se o comando terminar com sucesso, `ls` será executado.
3. Se o primeiro comando falhar, o `ls` não será executado.

Em sistemas Linux, um comando que termina corretamente normalmente retorna o código de saída `0`.

---

### Utilizando o operador `;`

```bash
mkdir projeto; ls
```

O operador `;` separa comandos que serão executados em sequência.

Diferentemente do `&&`, o segundo comando será executado independentemente de o primeiro ter terminado com sucesso ou com erro.

## Comparando os operadores

```bash
mkdir projeto && ls
```

`ls` somente será executado se `mkdir projeto` terminar com sucesso.

```bash
mkdir projeto; ls
```

`ls` será executado mesmo que `mkdir projeto` apresente erro.

## Conceito importante

Os operadores `&&` e `;` não fazem parte dos comandos `mkdir` ou `ls`.

Eles são interpretados pelo **shell** e controlam como os comandos escritos na linha serão executados.

- `&&` → executa o próximo comando somente se o anterior terminar com sucesso.
- `;` → executa o próximo comando independentemente do resultado do anterior.

## Exemplo prático

Criando uma pasta chamada `projeto` e, em seguida, listando o conteúdo do diretório:

```bash
mkdir projeto && ls
```

Depois da criação da pasta, o comando `ls` permite visualizar o novo diretório no conteúdo listado pelo terminal.

## Material complementar

📄 [Baixar o PDF da Aula 04](./aula-04-mkdir-ls-operadores-terminal.pdf)

---

📺 **Canal:** Aprenda Linux BR

🐧 Linux desde os fundamentos.
