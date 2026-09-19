# Projeto DCExt Programacao 2|3, ProgramAuto: sub-titulo

## Introducao

* Colocar uma explicacao de cada algoritmo escolhido
* Colocar aqui uma breve explicacao do programa
* Explicar o processamento


## Casos e Usos

* Colocar aqui alguns exemplos
* Casos de uso

## Arquivos

* Explicar a producao

## Repositorio

### Arquivos no repositorio

No repositorio devem constar apenas e tao somente os arquivos:

* AUTHORS
* LICENSE
* README.md (este arquivo)
* VERSION
* biblio.bib: arquivo com bibliografia
* makefile
* pext-programaX-benante-sobrenome1-sobrenome2.pdf
* pext-programaX-benante-sobrenome1-sobrenome2.tex
* Imagens usadas que foram incluidas no artigo .tex, na subpasta imagens/

### Comandos para criar repositorio no Hydra

Apenas um aluno do grupo, o responsavel por criar, faz esta sequencia:

Exemplo para grupo 2021s1/pext01-disciplina. Mude os numeros conforme o semestre e o seu grupo.
Entre na pasta de extensao e digite:

```bash
$ cd extensao
$ git init
$ git add .
$ git cm "commit inicial"
$ ssh git@hydra newrepo pext01-disciplina.git
$ git remote add origin git@hydra:repos/2021s2/pext01-disciplina.git
$ git pull origin master --allow-unrelated-histories -s recursive -X ours --no-edit
$ git push -u origin master
```

E a partir de agora seu repositorio esta remoto, e os outros alunos do grupo poderao trabalhar em grupo apos clonarem.
Para ficar com a pasta com o mesmo nome dos colegas, renomeie-a assim:

```bash
$ cd ~/programaX/rascunhos
$ mv extensao pext01-disciplina
```

### Comandos para clonar o repositorio remoto no Hydra

Os outros alunos do grupo irao clonar o repositorio com:

```bash
$ cd ~/programaX/rascunhos
$ git clone git@hydra:repos/2021s1/pext01-disciplina.git
```

Confira com:

```bash
$ cd pext01-disciplina
$ ls
$ git st
```

Talvez confira tambem um "commit" e "push" da sua parte, seguido de um "pull" de outro aluno, para ter certeza que estao colaborando no mesmo repositorio.

E depois de estar satisfeito, os alunos que fizeram clone podem apagar a pasta de extensao que acabou ficando em duplicidade com o clone:

```bash
$ cd programaX/rascunhos
$ rm -rf extensao
```

### Entrega na pasta trabalhos

Antes do final do prazo, basta clonar com:

```bash
$ cd ~/programaX/trabalhos
$ git clone git@hydra:repos/2021s1/pext01-disciplina.git
```


## Copyright

* Date: 2022-02-27
* License: GNU/GPL v2.0

## Authors

* Author: Prof. Dr. Ruben Carlo Benante
* Email: rcb@upe.br

* Author: Nome do aluno 1
* Email:

* Author: Nome do aluno 2
* Email:
