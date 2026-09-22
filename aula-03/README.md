# Aula 03 — Criando Diretórios com o comando mkdir

Nesta aula começamos a realizar operações no sistema de arquivos através do terminal Linux.

Depois de utilizar o comando `ls` para visualizar o conteúdo de um diretório, agora vamos utilizar o comando `mkdir` para criar novos diretórios.

## O que vamos estudar

- o que é o comando `mkdir`;
- para que ele é utilizado;
- como criar um diretório pelo terminal;
- relação entre o terminal e a interface gráfica;
- como confirmar a criação utilizando `ls`;
- erros básicos que podem acontecer ao criar diretórios.

## Conceito importante

O comando `mkdir` é utilizado para criar diretórios.

O nome vem de:

**mkdir → make directory**

Exemplo:

```bash
mkdir projetos
```

Esse comando solicita a criação de um diretório chamado `projetos` dentro do diretório atual.

Depois podemos utilizar:

```bash
ls
```

para verificar se o novo diretório aparece na listagem.

## Terminal x Interface gráfica

Na interface gráfica, normalmente criamos uma pasta utilizando o mouse e opções como:

**Novo → Pasta**

No terminal podemos realizar a mesma operação utilizando:

```bash
mkdir nome-do-diretorio
```

O sistema de arquivos é o mesmo.

O que muda é a forma utilizada para realizar a operação.

## Exemplo prático

Criando um diretório:

```bash
mkdir estudos-linux
```

Verificando o resultado:

```bash
ls
```

Resultado esperado:

```text
estudos-linux
```

Também podemos abrir o gerenciador de arquivos e verificar que o diretório criado pelo terminal aparece normalmente na interface gráfica.

## Sintaxe básica

```bash
mkdir [opções] nome-do-diretorio
```

Nesta aula começamos utilizando a forma mais simples:

```bash
mkdir nome-do-diretorio
```

Opções e usos mais avançados serão apresentados no material complementar.

## Material da aula

📘 O PDF complementar sobre o comando `mkdir` será disponibilizado nesta pasta.

## Aprenda Linux BR

📺 [Canal Aprenda Linux BR no YouTube](https://www.youtube.com/@AprendaLinuxBR)

🐧 [Projeto Aprenda Linux BR no GitHub](https://github.com/aprenda-linux-br)
