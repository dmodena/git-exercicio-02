Exercicio 02
===

Em sua branch principal (main), crie um diretório chamado principal com 2 arquivos, da seguinte forma:
.
└── principal
    ├── 001.txt
    └── 002.txt

Faça um commit com essa estrutura.

Depois crie uma nova branch chamada *funcao-a*. Nesta nova branch, crie um diretório chamado funcao-a com 2 novos arquivos. Esta deve ser a estrutura na branch funcao-a:
.
├── funcao-a
│   ├── 001.txt
│   └── 002.txt
└── principal
    ├── 001.txt
    └── 002.txt

Faça um commit na branch funcao-a.

Retorne para a branch main.

A partir desta branch, crie uma nova branch chamada *funcao-b*. Crie um diretório chamado funcao-b com 3 novos arquivos. Esta deve ser a estrutura da branch funcao-b:
.
├── funcao-b
│   ├── 001.txt
│   ├── 002.txt
│   └── 003.txt
└── principal
    ├── 001.txt
    └── 002.txt

Ao fim do exercício, as três branches devem possuir os arquivos da branch principal, mas os arquivos das funções *a* e *b* devem estar contidos em suas respectivas branches.
