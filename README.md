# **Gestor de Consumo de Energia Residencial:** menosluz.com

Trabalho de Experiencia do Usuário (UX) apresentado ao Centro Universitário [FEI](https://portal.fei.edu.br/), como parte dos requisitos necessários para aprovação na disciplina de Experiência do Usuário e Front-End (CCP310) do curso de Ciencia da Computação, orientado pelo Prof. Dr. [Fagner de Assis Moura Pimentel](https://github.com/fagnerpimentel).

## Componentes do Grupo

- Yllan Souza
- Lucas Alves


## Resumo
O Gestor de Consumo de Energia Residencial visa empoderar os usuários no controle de seus gastos com energia elétrica, promovendo uma gestão mais consciente, sustentável e econômica.

A aplicação é uma plataforma desenvolvida para monitorar, analisar e otimizar o uso de energia elétrica em residências. Por meio de uma interface intuitiva, o sistema permite que os usuários acompanhem o consumo de energia em tempo real, visualizem históricos detalhados e recebam recomendações para reduzir o desperdício e melhorar a eficiência.

O aplicativo integra dados fornecidos por medidores inteligentes caso tenha ou inseridos manualmente, processando essas informações para gerar relatórios e médias de consumo. Além disso, a aplicação oferece metas de economia, simulações de custo com base em diferentes faixas tarifárias.


## Introdução

- Apresente uma contextualização para o problema que o serviço ou poduto proposto irá resolver e por quê esse tipo de aplicação é necessária.
  
  A aplicação pode ser utilizada para diversos casos atualmente, tanto para uma dona de casa que pretende ter uma maior economia mensal, quanto para uma casa com vários aparelhos de ultima geração que em conjunto, gastam mais energia do que o necessário, podendo ser utilizada em quase todas as situações.
- Em uma única frase, resuma o objetivo do serviço ou produto.
  
  Auxiliar no gerenciamento do consumo de energia.
- Que tipo de experiência o serviço ou poduto deve proporcionar para os usuários?
  
  Menor valor e um consumo mais consciente da eletricidade que ele utiliza em sua residência.

## Publico Alvo

- Determine o seu público alvo:
  
  O publico alvo é bem amplo, podendo ser donos de imóvel próprio, locatários, donos de propriedades para aluguel, focando em uma interface intuitiva para todas as idades elegiveis

### Personas
  Persona Primária: João
  
Descrição: João tem 45 anos, é casado com Maria e tem dois filhos adolescentes. Ele trabalha como analista administrativo e vive em um apartamento de médio porte na capital. Sua principal motivação é reduzir os custos mensais da casa, mas manter uma convivência boa com todos os aparelhos digitais em sua casa e a conta de energia é uma das despesas que mais o preocupa. Ele busca soluções práticas para economizar.

Contexto Social/Cultural: Valoriza a estabilidade financeira e a economia familiar, Ele conversa com amigos e vizinhos sobre dicas para economizar e está sempre de olho em oportunidades para cortar gastos.

Contexto Econômico: Família de classe média com orçamento apertado. A conta de energia alta no fim do mês causa estresse e desorganiza o planejamento financeiro.

O que ele precisa:

Uma forma simples e clara de ver onde o dinheiro está indo.

Alertas sobre picos de consumo inesperados.

Dicas práticas para economizar energia no dia a dia.

Uma estimativa do valor da conta antes que ela chegue.

  
Persona Secundária: Robson
Descrição: Robson tem 22 anos, é filho de João, e universitario. Ela passa grande parte do dia em casa estudando. Ela é a pessoa que mais gasta energia no dia a dia em casa. Sua principal necessidade é se organizar para deixar tudo mais otimizado para o dia a dia, para que ela possa estudar sem gerar muitos gastos. Ele usa o smartphone e computador para organizar sua rotina e se sente confortável com aplicativos que oferecem uma boa usabilidade.

Contexto Social/Cultural: Ele interage com outros os colegas de faculdade usando principalmente as redes sociais e videochamadas

Contexto Econômico: Família de classe média que busca otimizar o orçamento para ter um dia a dia mais tranquilo.

O que ele precisa: Gerar menos gastos no dia a dia para sua família

Gráficos comparativos do consumo atual com meses anteriores.

Categorização de gastos (ex: "geladeira", "ar-condicionado", "iluminação").

Notificações claras e diretas sobre o consumo.

Um "resumo do mês" com os principais pontos de atenção.

### Mapa de empatia

![Mapa de empatia](empatia.png)

- Determine o mapa de empatia[^1] de pelo menos uma persona primária e uma secundária.
  - O que o usuário vê: aqui estamos falando do ambiente visual em que o usuário se encontra. Ou seja, o que ele efetivamente enxerga, as pessoas e objetos que estão ao seu redor. Isso ajuda a entender o contexto em que o usuário está inserido e as influências visuais que está recebendo.
    
 João: visualiza noticias sobre aumento de valores de contas, e novas tecnologias que podem ser utilizadas em sua residência.

 Robson: sempre de olho em como estão as coisas em sua casa no modo geral, e em busca de ter um dia a dia mais otimizado
    
  - O que o usuário ouve: neste quadrante, buscamos entender o que o usuário está ouvindo, os sons que o cercam e como eles influenciam suas ações.
    
    João: Escuta seus amigos e companheiros de trabalho falando sobre costumes para melhor cuidado da residência e tecnologias novas, e sua familía sobre novos itens para sua casa ou outras opções para investir o orçamento mensal.
    
     Robson:Escuta seus colegas falando sobre tecnologias e formas/apps para estudo
 
    
  - O que o usuário diz e faz: aqui consideramos ações e comportamentos que o usuário apresenta durante sua interação com serviço ou produto.
    
  João: Verifica sempre que possível como está indo o consumo geral de sua casa, e quais aparelhos são mais rentaveis manter desligados ou em standby.
  
  Robson: Utiliza a plataforma com foco em abaixar o valor médio mensal para ajudar as contas em casa.
 
    
  - O que o usuário pensa e sente: neste quadrante, buscamos entender os pensamentos, sentimentos, emoções e percepções que o usuário tem em relação ao serviço ou poduto. Quais expectativas o usuário cria sobre o serviço ou produto?
    
    João:Gera uma curiosidade por sempre poder ir atrás de novas oportunidades, e calma por ter uma ideia melhor das cobranças mensais.
    
    Robson: Fica mais tranquilo com o tanto de coisas que utiliza estarem bem otimizadas.
 
    
  -Que tipo de serviço ou produto mais agrada essa persona?
  
  João: Produtos com inovação e garantia de qualidade/eficiência.
  
  Robson:coisas com mais tecnologia e rápidas.


  - Dores: quando falamos sobre dores do usuário, estamos fazendo referência a quaisquer obstáculos, necessidades ou frustrações que o usuário possa experimentar ao tentar realizar uma tarefa ou alcançar um objetivo. Isso inclui, por exemplo, problemas de usabilidade, dificuldades de acesso ou outros desafios que podem afetar a experiência do usuário.
    
  João:Valores altos em novas tecnologias, dificuldade de acesso por multiplataformas em serviços gerais.
  
  Robson:falta de tecnologia, calculos muito complexos/com pouca assistência digital.
 
    
  - Ganhos: nesse caso estamos falando de quaisquer benefícios ou recompensas que o usuário possa experimentar ao utilizar o serviço ou poduto. Isso pode incluir economia de tempo ou facilidade de uso, por exemplo. Que desejos do usuário o serviço ou poduto satisfaz?
    
  João:Maior economia nos custos mensais, facilidade de gerenciamento residencial.
  
  Robson:Maior velocidade de utilização no dia a dia.
 
  

## Contexto de uso

- Descreva o ambiente em que o serviço ou poduto deve ser utilizado.
  
  Residências gerais.!!
- Qual/quais o(s) contexto(s) sociais, econômicos e culturais existentes neste ambiente?
  
  Produto indicado para todos os indices sociais e economicos.!!
- Quais informações sobre o ambiente, o serviço ou produto deve guardar antes de iniciar a interação?
  
  que será utilizado dados de sua residência, verificação quase que diária desses dados.
- O que normalmente deve estar acontecendo com o ambiente quando o usuário interagir com o serviço ou poduto?
  
  estar com o ambiente residencial atualizado, e se necessário realizar mudanças para melhor utilização do produto.

## Jornada do usuário=====

- Criar uma narrativa para o o seu serviço ou produto com o usuário.
- Determine o que o usuário realiza desde a primeira até o última interação com o serviço ou produto.
  - Descreva o que acontece ou pode acontecer passo a passo
  - Como a tarefa começa? Como a tarefa se desenvolve? Como a tarefa termina?

 O usuario após criar a conta na plataforma, coloca algumas informações sobre sua residência, se tiver disponível vincula aparelhos smarts no aplicativo, e acompanha estudos sobre o valor geral, quanto está programado para gastar no mês com energia e o que pode ser feito para reduzir esses valores, e mesmo após conseguir esse objetivo, o aplicativo segue tendo utilidade como consultor de valores, e sempre trazendo dicas para melhores valores.

## Análise de concorrência

- Pesquise serviços ou podutos existentes atualmente que possam realizar o objetivo deste projeto.
- Selecione pelo menos 3 serviços ou podutos diferentes.
- Em relação aos concorrentes, respondam as seguintes perguntas?
  - Existe plataforma similar que atende o mesmo mercado e funcionalidades? Se sim: Quais os pontos positivos? Quais os pontos negativos?
  - Existe plataforma diferente quanto ao serviço, mas que atenda esse mercado? Se sim: Quais os pontos positivos? Quais os pontos negativos?

## Coleta de dados

## Modelo de tarefas

## Design

- Pense nas características de Affordances do seu serviço ou poduto. 
    - Que tipo de acessibilidades devem ser consideradas dentro do seu projeto?
- Discuta o papel das expectativas do usuário no projeto deste serviço ou poduto. Qual a importância e pontos a serem considerados se você quiser vender esse serviço ou poduto?

### Prototipação em baixo nível (papel)
#### Avaliação heurística

### Prtotipação em médio nível (Figma)
#### Avaliação heurística

### Prtotipação em alto nível (React)
#### Avaliação heurística

[^1]: Fonte: Adaptado de <https://hazeshift.com.br/mapa-de-empatia/>

<!-- TODOs:
- Add exemplos
 -->




