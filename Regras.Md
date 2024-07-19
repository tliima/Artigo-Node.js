##Assunto:
 Angular - Diretivas

## titulo
Diretivas Estruturais vs. Diretivas Atributivas no Angular

##capa
Lexica.Art e power point

## blocos

- o que são sao diretivas do angular 
- o que sao diretivas estruturais
- o que sao diretivas de atributos 
- cite exemplos com codigos de diretivas estruturais 
- cite exemplos com codigos de diretivas atributos
- faça um caal to action para as minhas redes sociais 
- coloque 3 hastags que façam sentido 

Ilustração da capa: gerado pela Lexica.Art e no power point
Conteudo gerado por IA: chatGPT e revisões humanas.

comporte-  secomo um escritor de artigos tech front-end e escreva o artigo atendendo as regras abaixo

{Regras}
> no maximo 5 blocos de explicação
>explique de maneira informal, como se fosse para uma criança
> os blocos que serão criados estão abaixo:
- o que são sao diretivas do angular 
- o que sao diretivas estruturais
- o que sao diretivas de atributos 
- cite exemplos com codigos de diretivas estruturais 
- cite exemplos com codigos de diretivas atributos
- faça um caal to action para as minhas redes sociais 
- coloque 3 hastags que façam sentido



Artigo:

Introdução
Ei, você gosta de mágica? No mundo do desenvolvimento web, o Angular tem algumas "mágicas" próprias que tornam nosso trabalho mais fácil e divertido. Essas mágicas se chamam "diretivas". Se você quer entender melhor como elas funcionam, vem comigo que eu vou te explicar de um jeito bem simples, como se você fosse uma criança!



Diretivas Angular
O que são Diretivas do Angular?

Imagine que você tem uma varinha mágica que pode fazer coisas incríveis no seu site. No mundo do Angular, essa varinha mágica se chama "diretiva". Diretivas são instruções especiais que você coloca no seu código HTML para fazer o Angular mexer, mudar ou adicionar coisas na página.



<p [hidden]="esconderTexto">Este texto pode ser escondido.</p>
<button (click)="esconderTexto = !esconderTexto">Mostrar/Esconder Texto</button>




Diretivas são como instruções mágicas no código.
Elas fazem o Angular mudar, mexer ou adicionar coisas na página.
São usadas diretamente no HTML.


Diretivas estruturais
O que são Diretivas Estruturais?

Agora, vamos pensar nas diretivas estruturais. São como grandes ferramentas que podem construir ou demolir partes da sua página. Elas podem, por exemplo, fazer aparecer uma lista de itens ou esconder algo dependendo de uma condição. É como um mágico que faz aparecer ou desaparecer coisas em um piscar de olhos!


<ul>
  <li *ngFor="let item of itens">{{ item }}</li>
</ul>


Diretivas estruturais podem adicionar ou remover elementos na página.
Elas controlam a estrutura do DOM (Document Object Model).
Exemplos comuns: *ngIf, *ngFor, *ngSwitch.


Diretivas de atributos
O que são Diretivas de Atributos?

As diretivas de atributos são um pouco diferentes. Elas são mais como os pinceis e tintas de um artista. Elas não adicionam ou removem partes da página, mas sim, mudam a aparência ou o comportamento de um elemento que já está lá. Por exemplo, podem mudar a cor de um texto ou adicionar um efeito especial quando você clica em um botão.



<p [ngStyle]="{ 'color': textoVermelho ? 'red' : 'black' }">Este texto muda de cor.</p>
<button (click)="textoVermelho = !textoVermelho">Mudar Cor</button>


Diretivas de atributos alteram a aparência ou comportamento de elementos existentes.
Não adicionam nem removem elementos da página.
Exemplos comuns: ngClass, ngStyle, ngModel.


Exemplos com Códigos de Diretivas Estruturais

Vamos ver um exemplo? Imagine que você quer mostrar uma lista de frutas só se houver frutas disponíveis. Usamos a diretiva *ngIf para isso:


<div *ngIf="frutas.length > 0">
  <h2>Lista de Frutas:</h2>
  <ul>
    <li *ngFor="let fruta of frutas">{{ fruta }}</li>
  </ul>
</div>
<div *ngIf="frutas.length === 0">
  <p>Não há frutas disponíveis.</p>
</div>


Aqui, a diretiva *ngIf verifica se há frutas na lista. Se houver, mostra a lista; se não, mostra uma mensagem dizendo que não há frutas.



Exemplos com Códigos de Diretivas de Atributos

E as diretivas de atributos? Vamos dar um toque especial a um botão usando a diretiva ngClass para mudar a cor quando o botão é clicado:



<button [ngClass]="{ 'btn-ativo': ativo }" (click)="ativo = !ativo">
  Clique-me!
</button>


.btn-ativo {
  background-color: green;
  color: white;
}


Nesse exemplo, a diretiva ngClass adiciona a classe btn-ativo ao botão se a variável ativo for verdadeira, mudando a cor do botão para verde com texto branco.



Conclusão
E aí, gostou de aprender sobre diretivas no Angular? Se sim, me siga nas redes sociais para mais dicas e truques incríveis sobre desenvolvimento front-end!



Fontes de produção

Ilustrações da capa: lexica.art

Conteúdo gerado por: ChatGPT e revisão humana



#Angular #WebDevelopment #Front-end
