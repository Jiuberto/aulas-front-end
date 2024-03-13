# aulas-front-end
 atividades de estudo de html e css

 ## html

 - Estrutura
 - Semântica
 - Padrões web

 ## css

 1. Estilo
 2. Alinhamento
 3. Design Responsavo

 ## js

 Em geral, CSS serva para:

 1. Estilos de varios tipos(coras, sombra, borda e etc)
 2. Alinhamento e espaçamento
 3. Desing Responsivo
 4. Animações e efeitos especiais de interação

 ### Formação de implementação



 #### Inline

 O CSS é aplicado diretamente a cada tag do HTML

#### Interna/OnPage

O CSS é criado usando regras (com seletores, propriedades, valores) dentro da própria página que queremos formatar.

As regras vão valer para todos

#### Como fazer uma regra CSS?

```css
seletor {propriedade: valor; }
```
#### Externa (mais usada)

É criado um arquivo de extensão CSS dedicado as regras de formatação. Este arquivo é então "conectado" as páginas HTML.

---

### Tipos de seletores
- tag: Mais abragente, casa com elementos html de acordo com o tag especifica

- descendente: Seletor mais específico, casa com elementos que são filhos (descendentes) de outro elemento. Us-se espaço para separar o filho/pai.

- agrupado: grupo de seletores que compartilham uma mesma formatação. Usa´se virgula para separar os seletores.

- pseudo-classes: classes "pré-prontas/nativo" da linguagem que pode ser aplicadas em diversas situações. Exemplos: passar mouse, reconhecer foco, selecionar determinados elementos etc.
Todas pseudo-classes começam com dois pontos:

- classes: Seletor versátil que permite a aplicação de estilos em diversos ele,emtos. possibilitando também a combinação de diferentes classes. No CSS usa´se .nome-da-classe para criar a classe, e no HTML usa-se o atributo class="nome-da-classe" para aplicar a classe.

- identificado: seletor bastante restrito (só pode ser usado em um elemento por pagina), permitindo criar uma estilização altamente específica. No CSS usa-se #nome-do-id para criar, e no HTML usa-se o atributo id="nome-do-id" para aplicar.


