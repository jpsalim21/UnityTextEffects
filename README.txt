Olá, sou João Pedro Miranda Salim. Hoje é dia 24/12/2023.
Ao longo do ano, tentei desenvolver um meio mais fácil de adicionar personalidade ao texto dos meus jogos, sem a dublagem.
O resultado é esse.
Enfim, um pequeno tutorial de como usar:

Use <> com texto dentro e um > para finalizar o trecho com efeito. Lista de efeitos:
<jump> = Faz as letras ficarem pulando, estilo telas de carregamento do ps2.
<s> <sw> <sl> = s faz o texto inteiro vibrar. sw faz palavras separadas vibrarem diferente. sl faz letras vibrarem diferente.
<w> = efeito de onda no texto.
<rainbow> = efeito de arco-íris.

Exemplo de texto:
Apenas como <w>teste>, vou fazer muita coisa <s>estranha>! Tipo colocar esse texto <rainbow>colorido>

Além disso, ao usar o TextEffectComponent (contido nessa package), você pode usar os efeitos nativos do textMeshPro e ainda usar o efeito de escrever ao longo do tempo. Efeitos como <#fffff></color> e <font="aaa"></font>. 
Para isso, use o TextEffectComponent.WriteText(insira o texto aqui);

Essa última propriedade pode causar problemas com os caracteres < e >. Por isso, vou buscar melhorar.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Hello, I'm João Pedro Miranda Salim. Today's 12/24/2023
Among this year, I tried to develop an easier way to add personality into text in my games, without dubbing.
This is the result.
So, there goes a little tutorial:

Use <> with the effect name inside and an > to end the effect. Effect list:
<jump> = Make the letters jump, like the ... in loading screens from ps2 games. 
<s> <sw> <sl> = s make all the text shake. sw make words shake. sl make every letter shake.
<w> = make the text wooble.
<rainbow> = rainbow effect.

Example:
Just for the <w>test>, gonna write something <s>strange>! Like making this text <rainbow>colorful>.

Furthermore, using TextEffectComponent (in this package), you can use native textMeshPro's effects and even use the write over time effect. 
For this, use the TextEffectComponent.WriteText("Example text");

This last property can cause problems with the char < and >. I'll try to fix this later.