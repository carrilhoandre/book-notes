## Implementing Domain-Driven Design

by Vaughn Vernon

### Prefácio (By Eric Evans)

* Eric Evans fala sobre a motivação inicial de Vaughn para escrever esse livro. Todo é conteúdo é um complemento do livro Domain-Driven Design (Tackling Complexity in the heart of software), porém com uma abordagem mais pragmática. Após 9 anos da escrita desse primeiro livro, foi possível abordar temas que já passaram por expêriencias reais na comunidade onde temos mais informações para refletir e obter um melhor entendimento. Também são tratados tópicos que foram publicados em artigos e apresentações, mas não foram publicados de forma consolidade em um livro.
No livro são adicionados alguns conceitos novos sobre o DDD onde o evento de dominio é colocado ao lado das entidades e value objects na construção do modelo de dominio. Em resumo esse livro tem uma visão mais completa do DDD e dos caminhos de implementação na prática usando exemplos reais.

### Prefácio

#### Landing with Domain-Driven Design (Aterrissando com Design Orientado a Domínio)
Fazendo uma analogia com uma viagem aéra, temos um passageiro que voa pela primeira vez e observa que a vista do ar é impressionante, mas às vezes as coisas parecem estranhas porque não consegue entender quando muda a cidade ou estado que está sobrevoando. O DDD possibilita traçar curso completo, guiados por um mapa onde indica onde estamos e pra onde vamos. 
O objetivo principal do livro é fazer com que o passageiro consiga pousar de maneira tranquila e segura, em uma rota extremamenta conhecida. Isso vai te ajudar entender a implementação do DDD, fornecendo exemplos que usam ferramentas familiares e tecnologias.

#### Mapping the Terrain and Charting for Flight (Mapeamento do terreno e mapeamento para voo)    
Um grande problema cultural dos desenvolvedores mesmo tendo um padrão que oriente ele a desenvolver com base no domínio, é pensar sempre na implementação técnica. No DDD esse tipo de desenvolvedor foca um pouco mais na modelagem tática porque quer separar logo o que vai ser um service, aggregate ou value object. Nesse tópico enfatizamos a importancia da modelagem estratégica e no quanto ela agrega valor real ao negócio. A linguagem ubíqua permite que as equipes de desenvolvimento e áreas de negócio falem a mesma lingua, permitindo mais clareza no que deve ser implementado e evoluido. A delimitação de contextos possibilita organizar contextos complexos de negócio em partes menores e portanto mais fáceis de gerenciar. Com a visão delimitada dos contextos conseguimos ver onde estamos e pra onde vamos no projeto.
