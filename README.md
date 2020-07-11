## Ferramentas Front-End utilizados:
  - BootStrap
  - CSS
  - JavaScript
  - JQuery
 
> *BootStrap*
>> Esta ferramenta foi utilizada para a correção de posicionamento dos elementos da página.

> *CSS*
>> Ferramenta utilizada para edição de elementos e, principalmente, fazer com que a interface seja responsiva para diversos dispositivos. <br>

> *JavaScript*
>> Ferramenta utilizada para animação/optmização dos elementos da página.

> *JQuery*
>> Ferramenta implementada para manuseio de BootStrap com mais facilidade.

## Elementos da Interface
  
  - Responsividade.
  ```css
@media(min-width: 768px) { /*tela tablet projetos lado a lado*/
    .projetos-responsivo {
    width: 50%;
    float: left;
    }
}
#painel-sobre {
    margin-top: 0;
}

@media(in-width:992px) {
    .topCasaFina-banner {
    left: 0;
    transform: translate(0, -80%);
    width: 50%;
    }
}

.topCasaFina-bannerWrapper {
    position: relative;
    height: 100%;
}

```
- Animações
Como por exemplo o efeito Carroussel com uso de JavaScript e BootStrap.

```html
 <div id="carousel-example-generic" class="carousel slide" data-ride="carousel">
      <!-- Indicators -->
      <ol class="carousel-indicators">
        <!--São os bullets da tela representando o Num img-->
        <li data-target="#carousel-example-generic" data-slide-to="0" class="active"></li>
        <li data-target="#carousel-example-generic" data-slide-to="1"></li>
        <li data-target="#carousel-example-generic" data-slide-to="2"></li>
      </ol>

      <!-- Wrapper for slides -->
      <div class="carousel-inner" role="listbox">
        <figure class="item active">
          <img src="./img/depoimentos/depoimento1.png">
          <figcaption class="carousel-caption">
            <h3>Yuri Padilha</h3>
            <p>Gostei muito</p>
          </figcaption>
        </figure>

        <figure class="item">
          <img src="./img/depoimentos/depoimento2.png">
          <figcaption class="carousel-caption">
            <h3>Lais Luderer</h3>
            <p>Atendimento excelente.</p>
          </figcaption>
        </figure>

        <figure class="item">
          <img src="./img/depoimentos/depoimento3.png">
          <figcaption class="carousel-caption">
            <h3>Caio Souza</h3>
            <p>Competência em primeiro lugar.</p>
          </figcaption>
        </figure>

      </div>

      <!--Controls para avançar/voltar img-->
      <a class="left carousel-control" href="#carousel-example-generic" role="button" data-slide="prev">
        <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
      </a>
      <a class="right carousel-control" href="#carousel-example-generic" role="button" data-slide="next">
        <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
      </a>

    </div>
```
- Redirecionamento de Conteúdo - Foi feito em só uma página com intuito de facilitar a navegação, devido isso foi feito com que as opções do cabeçalho levassem o usuário à área específica da área na mesma página.
