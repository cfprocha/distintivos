## Como criar Distintivos para o Github?

O processo é muito simples e vou ensiná-lo passo-a-passo aqui:

1. Localize o logotipo que deseja usar no seu distintivo, através do site [Simple Icons](https://simpleicons.org/)

2. Monte a URL para o distintivo, da seguinte forma:
    a) Comece com esse trecho de URL: <span>**https://img.shields.io/badge**</span>
        Sim, vamos usar o site [shields.io](https://img.shields.io/badge) para a criação

    b) Agora adicione o texto que deseja escrito no distintivo. Inicie com um hífen, para deixar um espaço entre o escudo e o texto e se for um texto composto (duas ou mais palavras) use um sublinhado ou o %20 para separar elas. 
    Exs.: https://img.shields.io/badge/-vs_code
          https://img.shields.io/badge/-vs%20code

    c) Defina a cor que deseja no fundo do seu distintivo. Recomendo que use a cor indicada no próprio site do Simple Icons. Só atente que no site ele indica o código hex da cor, colocando um # na frente dos números e aqui precisamos apenas dos números. A cor deve ser informada inserindo um hífen após o texto do distintivo, conforme demonstrado abaixo.
    https://img.shields.io/badge/-vs_code-007ACC

    d) Então chegamos no momento de adicionar o logotipo, para isso, insira no URL o texto **?logo=** seguido pelo nome indicado no site Simples Icons. Repare que se for um nome composto, deve ser usado hífen no lugar dos espaços, conforme exemplo abaixo.
    https://img.shields.io/badge/-vs_code-007ACC?logo=visual-studio-code
    *Caso não esteja disponível um logotipo para o seu distintivo, basta pular essa etapa, que, simplesmente, será inserido um distintivo sem logotipo. Mas siga todas etapas seguintes

    e) Nesse momento deve ser definida a cor do logotipo e do texto. Sugiro que use sempre branco, para um melhor contraste com o fundo. A definição da cor é feita inserindo no URL a expressão **&logoColor=**. Para usar branco, simplesmente insira **white**, conforme exemplo abaixo.
    https://img.shields.io/badge/-vs_code-007ACC?logo=visual-studio-code&logoColor=white

    f) Para evitar que fique com distintivos de alturas diferentes, adicione uma outra propriedade para padronizar, que é **&style=for-the-badge**, conforme exemplo abaixo.
    https://img.shields.io/badge/-vs_code-007ACC?logo=visual-studio-code&logoColor=white&style=for-the-badge

    g) Isso já é o suficiente, mas se desejar padronizar ainda mais, pode usar qualquer uma das propriedades abaixo, lembrando sempre de adicionar um **&** antes de informar cada propriedade.
    **style=flat
    style=plastic
    style=flat-square
    logoWidth=** (aqui informe uma quantidade de pixels)

3. Agora incorpore essa URL ao seu readme.md usando a tag IMG do HTML, conforme demonstrado abaixo:

    \<img alt="VS Code" src="https://img.shields.io/badge/-vs_code-007ACC?logo=visual-studio-code&logoColor=white&style=for-the-badge" /\>

    Não esqueça do atributo **alt** para garantir que seja apresentado um texto para usuários que não tenham como visualizar a imagem

