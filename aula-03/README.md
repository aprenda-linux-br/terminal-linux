# Aula 03 — Criando Diretórios com o comando mkdir

Nesta aula começamos a realizar operações no sistema de arquivos através do terminal Linux.

Depois de utilizar o comando `ls` para visualizar o conteúdo de um diretório, agora utilizamos o comando `mkdir` para criar novos diretórios.

## O que vamos estudar

- o que é o comando `mkdir`;
- para que ele é utilizado;
- como criar um diretório pelo terminal;
- relação entre terminal e interface gráfica;
- como verificar a criação utilizando `ls`;
- sintaxe básica do comando;
- primeiros exemplos práticos.

## Conceito importante

O comando `mkdir` é utilizado para criar diretórios.

O nome vem de:

**mkdir → make directory / make directories**

Exemplo:

```bash
mkdir projetos
```

Esse comando solicita a criação de um diretório chamado `projetos` dentro do local em que estamos trabalhando.

Depois podemos utilizar:

```bash
ls
```

para verificar se o novo diretório aparece na listagem.

## Terminal x Interface gráfica

Na interface gráfica, normalmente criamos uma pasta utilizando opções como:

**Novo → Pasta**

No terminal podemos realizar uma operação equivalente utilizando:

```bash
mkdir nome-do-diretorio
```

O sistema de arquivos continua sendo o mesmo.

O que muda é a forma utilizada para interagir com ele.

Um diretório criado pelo terminal também poderá ser visualizado normalmente através do gerenciador de arquivos.

## Exemplo prático

Criando um diretório:

```bash
mkdir estudos-linux
```

Verificando o resultado:

```bash
ls
```

O novo diretório deverá aparecer na listagem:

```text
estudos-linux
```

## Sintaxe básica

A forma básica do comando é:

```bash
mkdir nome-do-diretorio
```

Também podemos representar sua sintaxe de forma mais geral:

```text
mkdir [opções] diretório
```

Nesta aula utilizamos principalmente a forma básica.

O material complementar apresenta outros recursos e exemplos do comando `mkdir`.

## Material da aula

📘 [Abrir PDF — Guia do comando mkdir no Linux](./aula-03-mkdir-linux.pdf)

O PDF complementar aprofunda o conteúdo da aula e apresenta exemplos adicionais, incluindo criação de vários diretórios, estruturas aninhadas, uso de opções do `mkdir` e erros comuns.

## Aprenda Linux BR

📺 [Canal Aprenda Linux BR no YouTube](https://www.youtube.com/@AprendaLinuxBR)

🐧 [Projeto Aprenda Linux BR no GitHub](https://github.com/aprenda-linux-br)
