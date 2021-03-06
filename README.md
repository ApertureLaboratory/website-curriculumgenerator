# Projeto Open Source - Aperture Laboratories
## Feito por Fukubi e Henrique Nitatori

Esse projeto é um website onde é requisitado os dados básicos do usuário como escolaridade, experiências profissionais e depois é efetuado a criação de um currículo em formato .PDF pronto para ser utilizado. O documento gerado não tem nenhuma restrição, podendo ser considerado como autor o dono dos dados fornecidos.

## Prints do projeto

![landing-page](https://github.com/ApertureLaboratory/website-curriculumgenerator/blob/main/git%20images/curriculum-example.png?raw=true)

![form-page](https://github.com/ApertureLaboratory/website-curriculumgenerator/blob/main/git%20images/requirements-print.png?raw=true)

## Técnologias utilizadas

Para a criação desse projeto foi utilizado ReactJS para a criação do front-end, sengundo a wikipedia, o ReactJS é:

```
O React é uma biblioteca JavaScript de código aberto com foco em criar interfaces de usuário em páginas web.
É mantido pelo Facebook, Instagram, outras empresas e uma comunidade de desenvolvedores individuais.
```

Através dele as páginas, encontradas nos arquivos About.tsx, Landing.tsx e MainForm.tsx  
Para criação do PDF foi utilizado o jsPDF, o jsPDF é uma biblioteca feita para o node em que é possível criar PDFs no client-side, sem a utilização de um back-end. Assim o projeto conseguiu se manter sem a necessidade de guardar os dados informados, dando mais segurança as informações

## Possíveis melhorias que estão por vir

1. Melhoria no visual do PDF
2. Mais campos adicionados de acordo com a necessidade

## Como escrever uma mensagem de commit

Para fazer um commit siga as seguintes regras:

`git commit -m "*tipo*: mensagem-do-commit"`

- Os tipos são: [ `build`, `chore`, `ci`, `docs`, `feat`, `fix`, `perf`, `refactor`, `revert`, `style`, `test` ]
- E a mensagem do commit deve ser escrito em letras minúsculas.

## Como contribuir no projeto

- Fetch/Pull a Branch Develop
- Crie uma Branch de acordo com sua issue
- ex: O nome da Branch é feature/fcg
- ex: O nome da Branch é bug/fcg
  Feito isso pode fazer o push na branch origin e depois submeter um PR para a branch Develop para a review 🥳

## Créditos

Créditos especiais ao:   
[Fukubi](https://github.com/Fukubi) desenvolvimento das telas e da lógica.

[Henrique Nitatori](https://github.com/henrique-nitatori) por ter apoiado no desenvolvimento do projeto e ter feito a maior parte dos layouts das telas.

[Fernando dos Santos](https://github.com/codder404) que realizou e fez a padronização do código.
