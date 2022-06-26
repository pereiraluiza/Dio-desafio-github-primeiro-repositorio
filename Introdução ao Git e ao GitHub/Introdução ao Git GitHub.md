# O que é Git?

O Git é um sistema de controle de versionamento distribuído, usado principalmente no desenvolvimento de software, mas pode ser usado para registrar o histórico de edições de qualquer tipo de arquivo.

### Comandos mais utilizados no Git

- Git Status: Exibi as condições do diretório de trabalho.

- Commit: É processo de efetivar as alterações.

- Git log: Permite ver o histórico de commits ou um específico.

- Git init: Inicia um projeto e cria um repositório vazio.

- Git clone: serve para baixar o código-fonte existente de um repositório remoto.

- Git add: serve para incluir alterações de um arquivo no próximo commit.

- Git commit: este comando captura um instantâneo das mudanças preparadas do projeto

  no momento.

- Git push: envia as alterações realizadas para o servidor remoto.

- Git pull: recebe atualizações do repositório remoto para a máquina que originou o repositório.

- Git revert: desfaz commits.

### O que é SHA1 e como funciona?

A sigla significa secure hash algorithm (algoritmo de hash seguro), o SHA-1 é uma função de dispersão criptográfica, que embaralha determinado arquivo, imagem ou texto para seja gerado um conjunto (40) de caracteres identificadores.

### Objetos interno do Git

Objetos tree: é um conjunto de valores de índices apontando para os objetos.

Objeto commit: aponta para a tree

Obejto blob: objeto usado para armazenar o conteúdo de cada arquivo em um repositório.