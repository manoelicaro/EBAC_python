# curso_frontend_ebac
# curso_frontend_ebac

----------------------------------------------------------------------------------------
A entrega deste exercício consiste em:
----------------------------------------------------------------------------------------

* Crie uma outra landing page a partir do layout que construímos durante o módulo - o tema do site fica a seu critério;

* Publique o projeto na Vercel;

* Envie o link através da plataforma.

----------------------------------------------------------------------------------------
Paleta de cores
----------------------------------------------------------------------------------------

* Vermelho Escarlate: #C72C41 (representa a paixão e a luta)

* Azul Real: #1E4D92 (evoca a nobreza e a lealdade)

* Dourado: #D4AF37 (simboliza riqueza e poder)

* Verde Esmeralda: #2E8B57 (representa a natureza e a esperança)

* Cinza Claro: #F0F0F0 (para equilíbrio e neutralidade)

----------------------------------------------------------------------------------------
Fontes
----------------------------------------------------------------------------------------

* Cinzel: Uma fonte serifada inspirada na tipografia clássica, perfeita para dar um ar de nobreza e heroísmo.
Link: [Cinzel](https://fonts.google.com/specimen/Cinzel)
HTML code:
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@400..900&display=swap" rel="stylesheet">
CSS code:
.cinzel-<uniquifier> {
  font-family: "Cinzel", serif;
  font-optical-sizing: auto;
  font-weight: <weight>;
  font-style: normal;
}

* Playfair Display: Outra fonte serifada que traz elegância e pode ser usada para títulos e cabeçalhos.
Link: [Playfair Display](https://fonts.google.com/specimen/Playfair+Display)
HTML code:
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400..900;1,400..900&display=swap" rel="stylesheet">
CSS code:
.playfair-display-<uniquifier> {
  font-family: "Playfair Display", serif;
  font-optical-sizing: auto;
  font-weight: <weight>;
  font-style: normal;
}

* Lora: Uma fonte serifada que combina bem com textos longos e traz uma sensação de sofisticação.
Link: [Lora](https://fonts.google.com/specimen/Lora)
HTML code:
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Lora:ital,wght@0,400..700;1,400..700&display=swap" rel="stylesheet">
CSS code:
.lora-<uniquifier> {
  font-family: "Lora", serif;
  font-optical-sizing: auto;
  font-weight: <weight>;
  font-style: normal;
}

----------------------------------------------------------------------------------------
Estrutura
----------------------------------------------------------------------------------------

1- Divs
* Banner
    * Sobre o restaurante - Historia do jogo
        * Uma seção que explora a narrativa e o enredo de "Fire Emblem: Engage", incluindo resumos de capítulos ou arcos de história.
    * Sobre o espaco - Lore e Mundo
        * Uma seção que explora o mundo de "Fire Emblem: Engage", incluindo informações sobre reinos, culturas e mitologia.
* Eventos - Experiência de Jogo
    * Aniversario - Guia de Estratégia:
        * Dicas e táticas para vencer batalhas, construir equipes e maximizar o potencial dos personagens.
    * Recepcao para casamento - Música e Trilha Sonora:
        * Análise das faixas do jogo, informações sobre os compositores e links para ouvir a trilha sonora.
    * Confraternizacoes - Desafios e Conquistas:
        * Uma seção dedicada a desafios específicos do jogo, conquistas que os jogadores podem desbloquear e dicas sobre como completá-los. Isso pode incluir informações sobre modos de dificuldade, conquistas especiais e eventos temporários.
* Personagens
    * Bebidas nao acoolicas - Heróis de Elyos
        * Alear: O protagonista do jogo, Alear é um Dragão Divino que luta para proteger o mundo de Elyos. Com habilidades versáteis, ele pode se adaptar a diferentes classes e estilos de combate.
        * Marianne: Uma personagem com um passado trágico, Marianne é uma usuária de magia que possui uma conexão especial com a natureza. Sua habilidade de cura e suporte é vital para a equipe.
        * Lyn: Uma guerreira ágil e habilidosa, Lyn é conhecida por sua destreza com a espada e sua determinação em proteger seus amigos. Ela é uma lutadora feroz e uma líder natural.
    * Bebidas alcoolicas - Líderes de Facções
        * Lumera: A Rainha de Elyos e mãe de Alear, Lumera é uma figura poderosa e sábia que desempenha um papel crucial na luta contra as forças do mal.
        * Marth: Um dos heróis lendários da série, Marth é um príncipe e um mestre espadachim. Ele é conhecido por sua bravura e liderança em batalhas.
        * Sigurd: Um líder carismático e valente, Sigurd é um cavaleiro que luta pela justiça e pela proteção de seu reino. Sua habilidade em combate é admirada por muitos.
    * Entradas - Guerreiros e Combatentes
        * Alfred: Um cavaleiro destemido e leal, Alfred é conhecido por sua força e determinação. Ele é um defensor feroz de seus aliados e um combatente habilidoso.
        * Celine: Uma guerreira ágil e astuta, Celine é especialista em ataques rápidos e estratégias de combate. Sua inteligência a torna uma valiosa adição ao grupo.
        * Ike: Um guerreiro robusto e determinado, Ike é conhecido por sua força bruta e habilidades de combate. Ele é um líder nato que inspira seus companheiros.
        * Ephraim: Um príncipe guerreiro, Ephraim é conhecido por sua bravura e habilidades em batalha. Ele é um lutador feroz que não hesita em enfrentar desafios.
    * Pratos Principais - Místicos e Magos
        * Soren: Um mago talentoso, Soren é conhecido por seu conhecimento profundo de magia e táticas de batalha. Ele é um estrategista que pode mudar o rumo de uma luta com suas habilidades mágicas.
        * Eirika: Uma princesa e guerreira, Eirika é uma usuária de magia que combina força física com habilidades mágicas. Sua determinação e coragem a tornam uma líder natural.
        * Celica: Uma sacerdotisa poderosa, Celica é uma usuária de magia que pode curar e atacar. Sua conexão com o divino a torna uma figura central em batalhas.
        * Lissa: Uma curandeira e guerreira, Lissa é conhecida por suas habilidades de suporte e sua capacidade de curar os feridos. Ela é uma personagem otimista e cheia de energia.
    * Sobremesa - ********
* Fale conosco