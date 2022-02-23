# Agradecimento-Trybe

Olá meu nome é Caio, sou da Turma 20 Tribo A.

Comecei esse projeto quando embarcamos no CSS e logo descobri que era possível fazer animações usando o CSS apenas. Foi então que pensei: 

>**'por que não fazer uma surpresa pra os funcionários da Trybe?'**

Foi então que comecei a fazer esse projeto.

## Qual o objetivo do Projeto?

### Parte 1 - O inicio

Inicialmente eu pensei em botar um coração verde de cor #2fc18c com um fundo #036b52. 
E um coração que batia no meio com a frase #betrybe.

### Primeiro problema.

Eu estava fazendo o site todo em FlexBox antes de saber como funcionava pois descobri que `justify-content: center;` funcionava muito bem para centralizar as coisas.

O problema é que a Flex não tem como deixar uma `<div>` sobre a outra pois o **CSS z-index Property** não funciona em `display: Flex;`.

Então eu tentei várias outras alternativas mas o Flex é feito para não botar uma `<div>` sobre a outra.

O [Trybe] Lucas Leal me deu uma ideia de usar um pseudo-element ::AFTER com o conteudo `content: "#BETRYBE";`.
O problema ou a solução é que o #BETRYBE agora se transforma também pulsando junto com o coração.

## Minha visão pra o Futuro.

Eu gostaria de fazer 3 páginas.
1. home.html
2. depoimentos.html
3. cadastroDeDepoimento.html

 - Na na lateral esquerda irá aparecer uma foto (se o aluno quiser), e na direita o agradecimento.

 - Isso vai ficar em um web server que vai armazenar as menssagens em um sql.

 - Essas fotos e depoimentos vão trocar de acordo com o número de palavras no depoimento.
 - Existe um código para calcular o tempo de leitura de um texto. (não conheço mais vou achar)
 - E os depoimentos vão entrar em um sistema de posts na segunda página que mostrará todos os depoimentos e agradecimento. Os posts vão ser ca rregados de acordo com o scroll do usuário.

Isso usa 100% de todo o conhecimento que teremos.

#### Se você chegou até obrigado pelo seu tempo.

Se você quiser me ajudar me mande um Slack que eu irei adicionar você ao repositório.
Você também pode me achar no e-mail <caio_bgalvao@hotmail.com>.

