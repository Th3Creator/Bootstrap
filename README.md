# Bootstrap
Repositório destinado a colocar instruções, observações e maneiras de se construir da maneira adequada um projeto que possui a biblioteca bootstrap. Sendo assim, trazendo exemplos de 3 landing pages que utiliza-se da biblioteca Bootstrap, bem comentado e intuitivo para que qualquer um compreenda de vez as funcionalidades que o Bootstrap oferece.

![bootstrap](https://user-images.githubusercontent.com/78706060/199778815-9a01b741-3c81-4898-a09e-cd7dc8bdd795.png)

## 👨‍💻 Processos de inserção do bootstrap através de CDN: 
- Instalação via CDN (inserindo os links no código html)

## 🧰 Flex-Box: 
- Responsável por alinhar elementos de forma responsiva e dinâmica, o Bootstrap trouxe o flex como uma das ferramentas dele e criou uma série de classes para que assim, possámos estilizar melhor o nosso código e trabalhar de forma responsiva durante o desenvolvimento do projeto

- No código copiamos apenas o que nos interessa, a classe que fica responsável por deixar os elemento no final "justify-content-end", copiando ela da documentação do Bootstrap falta apenas selecionarmos ela na div pai que contem os elementos que queremos posicionar no final.

- Além do "justify-content" o bootstrap oferece através do flexbox todas suas funcionalidades, para que assim se construa o layout do site da melhor forma possíve 

obs: ma observação forte de se ressaltar é que é de suma importância que esteja ciente da hierarquia que o Flex-Box prioriza na hora da estilização dos elementos
exemplo.comImagem

## ♻️ Estilização do programador em cima de códigos do bootstrap:

- Durante a construção do código é possível observar que veremos detalhes que quando copiamos algo pronto do 
bootstrap não virão exatamente como queremos e às vezes apenas um atributo só do CSS resolveria. Como resolveremos 
isso? pegando a classe dela e estilizando no nosso arquivo index.css? NNÃÃÃOOOOOOO, a própria documentação 
do bootstrap é bem completa e sucinta, já trazendo tudo que faríamos nos nossos próprios arquivos .css na sua documentação, basta apenas 
procurar corretamente, um exemplo disso é quando utilizamos o position: fixed no nosso navbar, são exessões que relevam esse tipo de abordagem 

exemplo.comImagem

- Contradizendo +/- um pouco dito anteriormente, nem sempre o bootstrap vai trazer tudo que queremos, certas
coisas ficam por responsabilidade do programador, como definir largura das imagens, cores e tudo mais, porém, 
mesmo assim o bootstrap ainda continua sendo uma ferramente extremamente poderosa
obs: trazendo exemplo que está no código

- Abordando alguns conceitos de altura e largura em relação ao elemento pai, esse tipo de pesquisa no bootstrap 
fica um pouco difícil de se achar porém é só pesquisar relative father

- Basicamente de uma maneira geral, às mudanças que queremos fazer por exemplo: mudar a cor, mudar o tamanho ou 
algo do tipo, iremos fazer uma classe e inserir ela no início para que haja maior relevância

## 📌HTML Semântico:
Dando enfâse nas tags semânticas do html, a importância de cada uma e o quanto ela facilita na compreensão do código na hora de ler, serve somente pra dizer o que está acontecendo naquela parte do código.

obs: Dentro da parte principal pode haver várias seções...

Com isso às tag's semânticas fazem com que o código se torne mais acessível pelos leitores de tela e para os que trabalham no desenvolvimento do projeto
sua importância e tudo mais...

## 📏Sistema de GRID:
- Partilarmente sendo uma das funcionalidades mais interessantes do bootstrap, o sistema de grid trás de forma 
organizada o modelo de loyout em GRID do css. Sendo ela divida em 12 colunas, que seria um número mais acessível 
para o manunseamento e posicionameento das colunas, o GRID do bootstrap opera de maneira bem simples e dinâmica,
utilizando de alguns breakpoints pré definidos como:

<table>  
  <tr>
      <td>xs</td>
      <td>md</td>
      <td>lg</td>
      <td>xl</td>
      <td>xxl</td>
  </tr>
  
  <tr>
      <td>.col-</td>
      <td>.col-md</td>
      <td>.col-lg</td>
      <td>.col-xl</td>
      <td>.col-xxl</td>
  </tr>
  
  <tr>
      <td><576px à ≥576px</td>
      <td>≥576px à 768px</td>
      <td>768px à ≥992px</td>
      <td>992px à ≥1200px</td>
      <td>1200px à ≥1400px</td>
  </tr>
</table>


## ⚠️ Considerações finais

O bootstrap é uma ferramente muito poderosa e de fato facilita muito na vida do programador que não se dá muito bem com o front-end, além de conseguir implementar tudo que a biblioteca oferece é possível também por meio de classes criadas pelo próprio dev estilizar tudo aquilo importado da biblitoca, como: a mudança de cor, a mudança de fonte e detalhes às vezes que deixamos passar batido

O projeto ainda está sofrendo mudanças...
