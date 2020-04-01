# Boas práticas de um commit

Toda vez que você realizar uma alteração no projeto, como, criar uma pasta ou arquivo, atualizar um conteúdo, remover alguma coisa, você precisará submeter um commit. Cada commit submetido é ordenado, como você pode ver nos [commits do projeto](https://github.com/ai-girls/dev-to-posts/commits/master) e seria legal se eles contassem uma história (por isso, isso é uma boa pratica). 

E como fazemos para o nosso commit contar uma história? Para isso precisamos seguir algumas boas práticas.

> Tudo que eu vou falar aqui, está na documentação do [git](https://git-scm.com/doc). Recomendo você estudar mais a fundo isso. 

## Utilize o modo imperativo

Utilize verbos no imperativo em suas mensagens de commit. Para ter certeza que você está fazendo isso, valide a mensagem colocando ela como resposta da pergunta: *"Se submetido, esse commit vai?"*.

Ainda não conseguiu imaginar como seria isso? Segue alguns exemplos: "Adiciona introdução do post blabla", "Remove erros de portugues no post blabla", "Atualiza resumo do post blabla".

## Seja direta nos seus commits

Explique o seu commit o que está falando, não diga apenas que ele "Adiciona tal coisa", ou "Remove outra coisa". Porque assim, quando você olhará para o histórico, você ou outras pessoas, não entenderão de cara o que o commit está fazendo. Por isso, **seja direta e detalhada**!

Utilize o campo de descrição (que o GitHub fornece), para te ajudar a explicar mais a fundo o que seu commit faz. 

## Limite o commit a 50 caracteres

Isso mesmo! O commit precisa ser direto e detalhado, mas também **precisa ter menos do que 50 caracteres**. Com o tempo você acostuma com essa limitação e se você precisar digitar uma mensagem que possua mais de 50 caracteres, tente colocar ela no campo maior de descrição.

> O número 50 é uma convenção, essa quantidade permite que a mensagem será lida por completo em qualquer interface (terminal, monitores...).

## Capitalize seu commit

Comece seus commits com letras maiúsculas, é uma convenção que veio da utilização do git no terminal (que é o padrão) e se segue até hoje. 

E não custa nada, né mesmo? hehe.



