# Anotações sobre front-end

## HTML 

## CSS
Linguagem de estilização que "casa" com elementos HTML.

Em geral, CSS serve para:

1. Estilos de vários tipos
2. Alinhamentos e espaçamentos
3. Desig Responsivo
4. Animações e efeitos especiais de interação

### Formas de implementação

#### Inline

O CSS é aplicado diretamente em cada tag HTML.

#### Interna/Onpage

O CSS é criado usando regras (com seletores, propriedades, valores,) dentro da própria página que queremos formatar.

As regras vão valer para todos os elementos/tags desta página.

#### Externa

É criado um arquivo de extensão CSS dedicado ás regras de formatação. Este arquivo é então "conectado" ás páginas HTML.

##### Como fazer uma regra CSS?


```css
seletor { propriedade: valor; } 

seletor { propriedade1: valor;
          propriedade2: valor; 
          propriedade3: valor;
}
```

---

### Tipos de seletor

- TAG: seletor mais abrangente/generalista, casa com elementos HTML de acordo com a tag especificada.

- Descendente: seletor mais especifico, casa com elementos que são filhos (descendentes) de outro elemento. Usa-se espaço para separar o filho/pai.

- Agrupado: grupo de seletores que compartilham com a mesma formatação. Usa-se vírgula para separar os seletores.

- Pseudoclasse: classes "prontas/nativas" da linguagem que podem ser aplicadas em diversas situações. Exemplos: passar mouse, reconhecer foto, selecionar determinados elementos etc. TODAS pseudo-classes começam com dois-pontos(:).

- Classe: seletor versátil que permite a aplicação de estilos em diversos elementos, possibilitanto também a combinação de diferentes classes. No CSS usa-se .nome-da-classe para criar a classe, e no HTML usa-se o atributo class="nome-da-classe" para aplicar a classe.

- Identificado: seletor bastante restrito(o mesmo ID só pode ser usado em um elemento por página), permitindo criar uma estilização altamente específica. No CSS usa-se #nome-do-id para criar, e no HTML usa-se o atributo id="nome-do-id" para aplicar.