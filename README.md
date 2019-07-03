# Lista de que tecnologias utilizadas

**Flex**
Situações em que utilizei flex:
- Para posicionar os elementos do header porque só precisava de trabalhar elementos numa dimensão (coluna em mobile e row em desktop).
Em ecrãs mais pequenos usei wrap para a nav se posicionar por baixo do logo. Em desktop coloquei justify-content flex-end para todos os elementos se alinharem à direita e ao logo dei flex:1 para ser o único elemento a ficar encostado à esquerda.
- Introduction cards e Projects na home: para colocar os cards/projectos dois a dois.
- No footer: para em ecrãs pequenos colocar todos os elementos numa só coluna e em ecrãs maiores colocar os icons de contacto e social media em linha. 
- No form: para colocar os elementos em coluna.


**CSS Grid**
Optei por utilizar Grid sempre que precisei de trabalhar quer colunas quer linhas. Permitiu-me ter mais liberdade no posicionamento dos elementos.
Utilizei em:
- Zona com os post its na Home: permitiu-me colocar os posts its agrupados em “says”, “thinks”, “does”, “feels” e definir que em ecrãs pequenos estes 4 grupos ficavam empilhados, enquanto que em ecrãs maiores “says” e “thinks” ficavam lado a lado, bem como “does” e “feels”.
- Posts: Defini que tinha a coluna tinha 3fr e que por exemplo o texto ocupava 2fr (da 1 à 2 - grid-column: col / span 3), enquanto que a primeira imagem ocupava toda a largura (da 1 à 3 - grid-column: 1 / 4).
- Footer: Para em ecrãs grandes poder manter a nav em coluna e alinhada à esquerda e o contacto e redes sociais encostados à margem direita.


**SCSS variáveis**
Para facilitar a escrita do SCSS bem como facilitar fazer alterações optei por utilizar variáveis para:
- as cores
- tipos de letra 
- margens que se repetiam: margin-left em mobile pois para a maioria dos elementos queria que tivessem 10px, mas para ecrãs maiores já queria que a margin-left fosse 0.


**SCSS Mixins**
- Para colocar aspect ratio facilmente nas imagens do site optei por criar um mixin.
- Como repetia várias vezes duas regras de CSS juntas sempre que usava type em uppercase, juntei essas duas regras num mixin.
- Através dum mixin escrevi duas regras para todos os headings.
- Para facilitar a personalização do type coloquei um mixin com: fonte, tamanho de letra, cor e line-height.


**Animations**
Optei por utilizar animation em duas situações que considerei importante chamar à atenção do utilizador:
- Indicação para fazer scroll para baixo na home: Como a primeira zona do site não deixa ver a secção seguinte optei por fazer uma animation para indicar ao utilizador para fazer scroll para baixo, para alertar que o site não acaba ali.
- Back to top: No final de cada página para facilitar o utilizador a continuar a explorar o site coloquei uma animação no botão para regressar ao topo.
- Usei ainda animation no hover dos botões.


**Form**
Para facilitar aos utilizadores entrarem em contacto comigo optei por utilizar um form na página contact, com os seguintes campos: nome, email, mensagem e botão de envio.

