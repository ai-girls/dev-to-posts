# A importância de um código de ética na construção de chatbots e IA

chatbot, ArtificialIntelligence, ethic 

Você já deve ter assistido o filme "Exterminador do futuro" ou  "I, Robot", ambos são muitos famosos e falam sobre o extermínio da raça humana através dos robôs, e isso acarretou em medo e receio das pessoas em confiarem na Inteligência Artificial. Portanto entusiastas, desenvolvedores e empresas assumem a importância de um código de ética na construção dessas inteligências. 

<img src="https://github.com/lauraDamacenoAlmeida/dev-to-posts/blob/master/posts/Captura%20de%20Tela%202020-03-30%20a%CC%80s%2015.58.51.png?raw=true">

Ao longo dos últimos anos, muitos investigadores, ativista expuseram os inúmeros erros, preconceitos e uso indevido da tecnologia, como por exemplo um modelo usado em casos criminais norte Americanos para prever quais criminosos têm maior probabilidade de reincidência e assim os juízes tomam as decisões baseados nele, chamado [COMPAS](https://medium.com/thoughts-and-reflections/racial-bias-and-gender-bias-examples-in-ai-systems-7211e4c166a1) que demonstrou carregar viés racial ao fazer essa classificação, onde a cor da pele da pessoa acabava sendo um fator para ser considerado criminoso de alto risco.

<img src='https://miro.medium.com/max/1400/0*cfX-3V_kHwT5o3_T'>

> Alguns dos resultados enviesados trazidos pelo software Compas

Outro caso, curioso foi o de dois pesquisadores da Universidade de Stanford que treinaram um algoritmo de [IA para adivinhar as orientações sexuais das pessoas com base em fotografias](https://www.bbc.com/portuguese/geral-41250020), o que poderia acabar expondo algumas pessoas, levando a outras atormentá-las com insultos homofóbicos, nunca considerando a validade dos dados usados para criar a tecnologia.
Ou, por exemplo se os policiais usassem algo semelhante para procurar criminosos, os algoritmos tendenciosos poderiam tornar as pessoas de certos grupos étnicos cada vez mais vulneráveis a crimes que eles não cometeram.
Os esforços para se lidar com estes desafios crescentes concentram-se frequentemente na importância do binômio “Ética+ IA”.


>Então como nós desenvolvedoras e entusiastas poderíamos construir inteligências que atingem seus objetivos e impactam a sociedade de uma maneira saudável?

## Como as máquinas aprendem?

Existem 3 tipos de aprendizado de máquina Supervisionado, não supervisionado e por reforço. Neste blog como estamos falando mais sobre chatbots vamos falar sobre o supervisionado e não supervisionado.

Supervisionado: Nós desenvolvedores temos controle sobre o que o bot diz, criando respostas em vez de permitir que os usuários o ensinem, ou seja nós temos um poder maior sobre o que nosso bot vai aprender.

•	Vantagens: Você sabe exatamente como ele vai responder e o bot não pode ser corrompido, a menos que você treine ele com dados corrompidos.

•	Desvantagens: É mais demorado e criar um bot convincente leva muito tempo.

Aprendizado não supervisionado: O bot é educado por seus usuários e não pelo desenvolvedor.

•	Vantagens: Os usuários fazem o trabalho de treinar e ensinar o bot e você não precisa se preocupar em gastar tempo atualizando-o.

•	Desvantagens: O seu bot vai desenvolver uma personalidade inconsistente e você pode não ter conhecimento do que está sendo ensinado. Na pior das hipóteses, ele se transforma em um software desagradável, racista, sexista e homofóbico.


Se você quiser saber mais a fundo sobre esses tipos de aprendizados, [clique aqui.]( https://dev.to/aigirlsbr/afinal-o-que-e-machine-learning-ih5)

## Tay e o aprendizado não supervisionado
<img src="https://github.com/lauraDamacenoAlmeida/dev-to-posts/blob/master/posts/Captura%20de%20Tela%202020-03-30%20a%CC%80s%2015.58.36.png?raw=true">

A Tay foi um chatbot criado pela Microsoft em março de 2016, onde ela interagia e aprendia com os tweets dos usuários na rede social. E sem o tratamento correto na base de aprendizado, ela acabou em menos de 24 horas se tornando homofóbica, racista e tudo mais.
E isso fez com que muitos desenvolvedores e empresas questionassem o aprendizado 100% não supervisionado, e como alternativa o aprendizado semi-supervisionado, onde teríamos um tratamento prévio dos dados que serão aprendidos pelo bot, por exemplo no caso da Tay, identificar palavrões, palavras homofóbicas, racistas e retirassem elas da base de conhecimento.


## Mas como garantir a ética nos chatbots e inteligências artificiais?
<img src ="https://media.giphy.com/media/NoCbUpxL1qzCw/giphy.gif">

Eu fiz uma pesquisa sobre os principais códigos de ética que as grandes empresas de inteligência artificial fizeram, entre elas [Google](https://ai.google/principles/), [Microsoft](https://www.microsoft.com/en-us/research/uploads/prod/2018/11/Bot_Guidelines_Nov_2018.pdf) e [IBM](https://www.ibm.com/blogs/watson/2017/10/the-code-of-ethics-for-ai-and-chatbots-that-every-brand-should-follow/), e elenquei alguns princípios que elas têm em comum:

•	Prevenção

•	Transparência

•	Confiabilidade

•	Privacidade

•	Igualdade


### Prevenção
Muitas empresas não pensam em prevenção de abusos por parte dos usuários para o chatbot, por exemplo: reconhecer palavrões, ameaças de morte ou até racismo.
Depois do acontecimento com a Tay, a Microsoft logo tirou-a do ar e criou um novo chatbot a Zo, que tem o tratamento na base de conhecimento onde evita os termos da lista negra. 
Algumas bibliotecas de lista negra de código aberto são mantidas e são usadas por agentes de conversação virtual para evitar determinados diálogos, um exemplo disso é o [Wordfilter]( http://tinysubversions.com/2013/09/new-npm-package-for-bot-makers-wordfilter/).

### Transparência

Seja transparente sobre o fato de usar bots como parte de seu produto ou serviço.
É mais provável que os usuários confiem em uma empresa transparente e próxima sobre o uso de tecnologia, e um bot é mais provável de ser confiável se os usuários entenderem que o bot está trabalhando para servir suas necessidades e é claro sobre têm suas limitações.
Uma vez que os designers podem dotar seus bots com “personalidade” e capacidades de linguagem natural, é importante transmitir aos usuários que eles não estão interagindo com outra pessoa e sim com um bot. Existem várias opções de design e isso pode ser feito para que não prejudique a experiência do usuário.



### Confiabilidade
O desempenho dos sistemas baseados em IA podem variar desde o desenvolvimento até a implementação, além, do tempo que o bot é lançado para novos usuários e em novos contextos, é importante continuamente monitorar a confiabilidade. 
Como fazer isso?! Seja transparente sobre a confiabilidade do bot, apresente resumos de desempenho do sistema ou de em um contexto específico. É importante sempre pedir feedbacks aos usuários referente as interações que ele teve, pois isso nos ajudará a entender melhor onde nosso bot está errando e ajustá-lo.

### Privacidade
Informe ao usuário que os dados serão coletados e como serão usados. Não esqueça de obter consentimento do usuário e não colete mais dados pessoais do que o necessário!
E aí vem um questionamento: “Temos uma IA que está sendo utilizada para prevenir suicídios, mas até que ponto ela pode interferir nas decisões humanas?”

### Igualdade

A possibilidade de sistemas baseados em IA perpetuarem preconceitos sociais existentes ou introduzirem novos vieses, é uma das principais preocupações identificadas pela comunidade de IA relacionada à rápida implantação dela.
As equipes de desenvolvimento devem estar comprometidas em garantir que seus bots tratem todas as pessoas de forma justa. Isso será alcançado com diversidade em sua equipe de desenvolvimento. Pois empregando uma equipe diversificada focada no design, no desenvolvimento e no teste da tecnologia, o bot terá mais chances de funcionar de forma justa.
Preste atenção na base de dados que está sendo utilizada no treinamento da IA ou do chatbot para verificar se ela não está enviesada.

>“As equipes de desenvolvimento devem estar comprometidas em garantir que seus bots tratem todas as pessoas de forma justa.”
( Microsoft, 2018, Bot Guidelines)


Até uma próxima,

AI Girl

Escritora: [Laura Damaceno de Almeida](https://www.linkedin.com/in/laura-damaceno/)

Siga a comunidade nas redes sociais!!

[LinkedIn](https://www.linkedin.com/company/ai-girls/)

[Facebook](https://www.facebook.com/aigirlsbr/)

[Instagram](https://www.instagram.com/aigirlsbrasil/)




