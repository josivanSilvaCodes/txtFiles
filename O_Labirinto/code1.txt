if ( selectedChoice.name == "Vila") {
  changeLayer("vila");
  changePointVisibility("Cavernas",1);
  changePointVisibility("Ler Carta",1);
  changePointVisibility("Cavernas ( NÃ­vel 2 )",1);
  changePointVisibility("Cavernas ( NÃ­vel 3 )",1);
  changePointVisibility("Biblioteca ( NÃ­vel 1 )",1);
  changePointVisibility("Biblioteca ( NÃ­vel 2 )",1);
  changePointVisibility("Biblioteca ( NÃ­vel 3 )",1);
  changePointVisibility("VER MAPA",1);
  changePointVisibility("Encontrar o papai",1);
} else if ( selectedChoice.name == "Cavernas") {
  changeLayer("caminhos");
  changePointVisibility("Caverna 2",1);
  changePointVisibility("Caverna 3",1);
} else if ( selectedChoice.name == "Voltar") {
  changeLayer("vila");
} else if ( selectedChoice.name == "Caverna 1") {
  changeLayer("CavernaUm");
} else if ( selectedChoice.name == "Virar") {
  changeLayer("CavernaUm2");
} else if ( selectedChoice.name == "Voltar caverna") {
  changeLayer("CavernaUm");
} else if ( selectedChoice.name == "Voltar caminhos") {
  changeLayer("caminhos");
} else if ( selectedChoice.name == "Caverna 2") {
  changeLayer("CavernaDois");
} else if ( selectedChoice.name == "Caverna 3") {
  changeLayer("CavernaTres");
} else if ( selectedChoice.name == "Fugir") {
  changeLayer("VcFugiu");
  playSound("media/sounds/applause.wav");
} else if ( selectedChoice.name == "CRÃ‰DITOS") {
  changeLayer("creditos");
} else if ( selectedChoice.name == "NOVO JOGO") {
  changeLayer("floresta.jpg");
  popup("SEU PAI ESTÃ DESAPARECIDO, VASCULHE SUA CASA EM BUSCA DE PISTAS \n \n Fique de olho nos seus status, nÃ£o os deixe negativo!!!");
} else if ( selectedChoice.name == "MENU") {
  changeLayer("Main");
} else if ( selectedChoice.name == "Labirinto") {
  changeLayer("floresta.jpg");
} else if ( selectedChoice.name == "Casa") {
  changeLayer("casa.gif");
  changePointVisibility("Espada",1);
  changePointVisibility("Ir p/ caverna",1);
} else if ( selectedChoice.name == "Carta") {
  changeLayer("carta.gif");
} else if ( selectedChoice.name == "Sair") {
  changeLayer("casa.gif");
  changePointVisibility("Carta",1);
  changePointVisibility("Espada",2);
} else if ( selectedChoice.name == "Espada") {
  changePointVisibility("Espada",1);
  changePointVisibility("Ir p/ caverna",2);
} else if ( selectedChoice.name == "Ir p/ caverna") {
  changeLayer("vila");
  changePointVisibility("Casa",1);
  changePointVisibility("Cavernas",2);
  changePointVisibility("Ler Carta",2);
} else if ( selectedChoice.name == "Descer") {
  changeLayer("CavernaUm2");
} else if ( selectedChoice.name == "Vilarejo") {
  changeLayer("vila");
} else if ( selectedChoice.name == "Ler Carta") {
  changeLayer("carta2.gif");
}

if ( selectedChoice.name == "Palavra Reservada") {
  popup("Palavra Reservada \n Uma palavra que Ã© utilizada pelo compilador/interpretador na anÃ¡lise sintÃ¡tica do programa; vocÃª nÃ£o pode usar palavras reservadas como if, def e while como nomes de variÃ¡veis.");
  changePointVisibility("Palavra Reservada",1);
} else if ( selectedChoice.name == "Variaveis") {
  popup("VariÃ¡vel \n Uma variÃ¡vel Ã© um nome que se refere a um valor. Um comando de atribuiÃ§Ã£o cria uma nova variÃ¡vel e lhe dÃ¡ um valor. \n   VariÃ¡veis sÃ£o usadas para guardarmos valores que serÃ£o usados mais tarde no programa. \n \n  Principais tipos de variavel: \n Tipo Inteiro (int) = O tipo inteiro Ã© um tipo composto por caracteres numÃ©ricos (algarismos) inteiros. Ã‰ um tipo usado para um nÃºmero que pode ser escrito sem um componente decimal, podendo ter ou nÃ£o sinal, isto Ã©: ser positivo ou negativo. \n idade = 18  \n  ano = 2002  \n \n   Ponto Flutuante ou Decimal (float) = Ã‰ um tipo composto por caracteres numÃ©ricos (algarismo) decimais. O famoso ponto flutuante Ã© um tipo usado para nÃºmeros racionais (nÃºmeros que podem ser representados por uma fraÃ§Ã£o) informalmente conhecido como â€œnÃºmero quebradoâ€.  \n altura = 1.80  \n  peso = 73.55   \n \n    String (str) = Ã‰ um conjunto de caracteres dispostos numa determinada ordem, geralmente utilizada para representar palavras, frases ou textos.  \n  nome = 'Labirinto'  \n  profissao = 'Engenheiro de Software'   \n \n    Boolean (bool)  = Tipo de dado lÃ³gico que pode assumir apenas dois valores: falso ou verdadeiro (False ou True em Python). Na lÃ³gica computacional, podem ser considerados como 0 ou 1.  \n  fim_de_semana = True  \n  feriado = False");
  changePointVisibility("Variaveis",1);
} else if ( selectedChoice.name == "AtribuiÃ§Ãµes") {
  popup("AtribuiÃ§Ãµes \n HÃ¡ menos exigÃªncias â€œgramaticaisâ€, como parÃªnteses em estruturas de seleÃ§Ã£o ou ponto-e-vÃ­rgula no fim da linha, e o cÃ³digo Ã© Um comando Ã© uma unidade de cÃ³digo que o interpretador pode executar. \n  Um comando de atribuiÃ§Ã£o tem a seguinte forma: \n \n     variÃ¡vel = expressÃ£o  \n \n  Exemplos: \n nome = 'Labirinto' \n  num  = 15 \n soma = 0  \n  soma = soma + num");
  changePointVisibility("AtribuiÃ§Ãµes",1);
} else if ( selectedChoice.name == "E/S") {
  popup("Entrada e SaÃ­da de Dados (E/S) \n Todo programa possui trÃªs componentes bÃ¡sicos: uma entrada especÃ­fica, uma sequÃªncia de regras (passos) a serem executadas sobre essa entrada, e uma saÃ­da. \n Na prÃ¡tica, um programa de computador pode receber sua entrada de muitas formas: por meio do teclado (quando o usuÃ¡rio digita alguma coisa), via linha de comando, por meio de arquivos de entrada, ou atÃ© mesmo por meio de cliques do usuÃ¡rio em certos botÃµes ou Ã¡reas da tela do computador.\n  A funÃ§Ã£o print() Ã© utilizada para o programa exibir e ler as entradas e mensagens.  Por exemplo: \n \n   soma = 10+20  print(OlÃ¡, mundo!) \n  print(A soma Ã©, soma) \n \n   Escreve na tela do computador \n   OlÃ¡, mundo! \n  A soma Ã© 30 \n\n  Para ler dados digitados pelo usuÃ¡rio durante a execuÃ§Ã£o do programa, utilizamos a funÃ§Ã£o input() (literalmente entrada, em inglÃªs). O exemplo abaixo ilustra o uso dessa funÃ§Ã£o: \n  print(Digite seu nome:)\n nome = input()\n print(Bem-vindo, , nome)");
  changePointVisibility("E/S",1);
} else if ( selectedChoice.name == "Python") {
  popup("Python \n Python Ã© uma linguagem de alto nÃ­vel. Aquelas em que os cÃ³digos tÃªm uma sintaxe prÃ³xima a linguagem humana, assim como Ruby, que tem uma tipagem dinÃ¢mica. EntÃ£o isso significa que ela utiliza recurso em script e Ã© orientada a objetos.");
  changePointVisibility("Python",1);
}
if ( selectedChoice.name == "Incremento") {
  popup("Incremento \n Os operadores de incremento tem a finalidade de acelerar o processo de adicionar uma unidade de um determinado nÃºmero. Geralmente, a utilizaÃ§Ã£o desse operadore estÃ¡ relacionado com os laÃ§os de repetiÃ§Ã£o, haja vista que os mesmos, geralmente, alteram o valor de suas variÃ¡veis para alterar o item a ser manipulado. \n  Sintaxe incremento:  \n \n  count += 1 \n \n   Exemplo: \n \n   num = 1 \n  num += 1 \n  print(num) \n \n   R: 2");
  changePointVisibility("Incremento",1);
} else if ( selectedChoice.name == "Decremento") {
  popup("Decremento \n Os operadores de decremento tem a finalidade de acelerar o processo remover uma unidade de um determinado nÃºmero. Geralmente, a utilizaÃ§Ã£o desse operadores estÃ¡ relacionado com os laÃ§os de repetiÃ§Ã£o, haja vista que os mesmos, geralmente, alteram o valor de suas variÃ¡veis para alterar o item a ser manipulado.  \n  Sintaxe decremento:  \n \n  count -= 1 \n \n   Exemplo: \n \n   num = 1 \n  num -= 1 \n  print(num) \n \n   R: 0");
  changePointVisibility("Decremento",1);
} else if ( selectedChoice.name == "ComentÃ¡rio") {
  popup("ComentÃ¡rios \n Os comentÃ¡rio sÃ£o muito Ãºteis na hora de documentar ou explicar certos trechos do seu cÃ³digo, sendo ignorados durante a execuÃ§Ã£o do script e podem ocupar uma ou mais linhas. \n \n    ComentÃ¡rios inline \n   SÃ£o comentÃ¡rios de â€œuma linhaâ€, indicados pelo sÃ­mbolo # (cerquilha, antÃ­fen, cardinal ou octothorpeâ€¦ ou ainda como vocÃª queira chamÃ¡-lo). \n   Tudo que estÃ¡ apÃ³s o sÃ­mbolo # Ã© ignorado pelo interpretador. \n  \n    # Este Ã© um comentÃ¡rio de uma linha \n \n    ComentÃ¡rios de VÃ¡rias Linhas\n   Caso seja necessÃ¡rio utilizar comentÃ¡rios que ocupem vÃ¡rias linhas, podemos utilizar trÃªs aspas simples no inÃ­cio, â€â€™, e outras trÃªs aspas simples, â€â€™, no final dos comentÃ¡rios. \n    ''' \n   Este Ã© um comentÃ¡rio \n   de vÃ¡rias \n   linhas utilizando-se aspas simples \n   '''");
  changePointVisibility("ComentÃ¡rio",1);
} else if ( selectedChoice.name == "Operadores NumÃ©ricos") {
  popup("Operadores NumÃ©ricos Os operadores sÃ£o utilizados para construir expressÃµes lÃ³gicas, aritmÃ©ticas, associativas, atribuir valores a variÃ¡veis e comparÃ¡-los. Trata-se de um recurso utilizado nas tarefas mais fundamentais da programaÃ§Ã£o e de conhecimento obrigatÃ³rio para qualquer programador. \n Os operadores aritmÃ©ticos sÃ£o utilizados na execuÃ§Ã£o de operaÃ§Ãµes matemÃ¡ticas, tais como a soma e a subtraÃ§Ã£o, por exemplo: \n \n    + = Realiza a soma entre operandos, adiciona o sinal de positivo ao nÃºmero. \n  soma = 10 + 20 \n \n    - = Realiza a subtraÃ§Ã£o entre operandos, adiciona o sinal de negativo ao nÃºmero. \n  subtraÃ§Ã£o = - 10 - 20 \n \n    * = Realiza a multiplicaÃ§Ã£o entre operandos. \n  multiplicaÃ§Ã£o = 10 * 20 \n \n    / = Realiza a divisÃ£o entre operandos. \n  divisÃ£o= 20/10 \n \n    ** = Retorna um nÃºmero elevado a potÃªncia de outro. \n  exponenciaÃ§Ã£o = 2 ** 2 ");
  changePointVisibility("Operadores NumÃ©ricos",1);
}

if ( selectedChoice.name == "NOT") {
  popup("NOT \n NOT = Inverte o resultado: se o resultado da expressÃ£o for True, o operador retorna false \n \n   NOT( FALSE ) = TRUE \n NOT( TRUE ) = FALSE \n \n \n");
  changePointVisibility("NOT",1);
} else if ( selectedChoice.name == "AND") {
  popup("AND \n AND = Retorna True se todas as condiÃ§Ãµes forem verdadeiras, caso contrÃ¡rio retorna False \n \n    TRUE and TRUE = TRUE \n TRUE and FALSE = FALSE \n FALSE and TRUE = FALSE \n FALSE and FALSE = FALSE \n \n \n");
  changePointVisibility("AND",1);
} else if ( selectedChoice.name == "OR") {
  popup("OR \n OR = Retorna True se uma das condiÃ§Ãµes for verdadeiras, caso contrÃ¡rio retorna False \n \n  TRUE or TRUE = TRUE \n TRUE or FALSE = TRUE \n FALSE or TRUE = TRUE \n FALSE or FALSE = FALSE \n \n \n	");
  changePointVisibility("OR",1);
} else if ( selectedChoice.name == "If") {
  popup("if \n Quando programamos, muitas vezes precisamos que determinado bloco de cÃ³digo seja executado apenas se uma determinada condiÃ§Ã£o for verdadeira. Em casos assim, devemos fazer uso de uma estrutura de condiÃ§Ã£o. \n   O if Ã© uma estrutura de condiÃ§Ã£o que permite avaliar uma expressÃ£o e, de acordo com seu resultado, executar uma determinada aÃ§Ã£o. \n  No cÃ³digo a seguir temos um exemplo de uso do if no qual verificamos se a variÃ¡vel idade Ã© menor que 20. Em caso positivo, imprimimos uma mensagem na tela e em caso negativo o cÃ³digo seguirÃ¡ normalmente. \n \n    idade = 18 \n  if idade < 20: \n          print('VocÃª Ã© jovem!') \n \n   Como podemos notar, essa estrutura Ã© formada pela palavra reservada if, seguida por uma condiÃ§Ã£o e por dois pontos (:). As linhas abaixo dela formam o bloco de instruÃ§Ãµes que serÃ£o executadas se a condiÃ§Ã£o for atendida. Para isso, elas devem ser identadas corretamente, respeitando a especificaÃ§Ã£o do Python. \n \n \n");
  changePointVisibility("If",1);
} else if ( selectedChoice.name == "else if") {
  popup("if/else \n  Vimos anteriormente como utilizar o if para executar uma aÃ§Ã£o caso uma condiÃ§Ã£o seja atendida. No entanto, nenhum comportamento especÃ­fico foi definido para o caso de a condiÃ§Ã£o nÃ£o ser satisfeita. Quando isso Ã© necessÃ¡rio, precisamos utilizar a reservada else. \n \n   idade = 18  \n  if idade >= 18:  \n      print('maior de idade') \n  else: \n      print('menor de idade') \n \n    Dessa vez, caso a condiÃ§Ã£o avaliada nÃ£o seja atendida, definimos o fluxo alternativo que o cÃ³digo deve seguir. Ou seja, se a idade nÃ£o for maior ou igual a 18, o bloco abaixo da palavra reservada else deverÃ¡ ser executado. Nesse caso, temos apenas uma instruÃ§Ã£o de impressÃ£o. \n \n \n");
  changePointVisibility("else if",1);
} else if ( selectedChoice.name == "Operadores de comparaÃ§Ã£o") {
  popup("Operadores de comparaÃ§Ã£o \n  Um assunto diretamente relacionado Ã s estruturas de condiÃ§Ã£o e repetiÃ§Ã£o sÃ£o os operadores de comparaÃ§Ã£o. Como o nome sugere, eles sÃ£o usados para avaliar o valor de duas ou mais expressÃµes/variÃ¡veis e comparÃ¡-las. \n \n    SÃ­mbolo	DefiniÃ§Ã£o  \n ==	Igual  \n !=	Diferente \n >	Maior que \n <	Menor que \n >=	Maior ou igual que \n <=	Menor ou igual que \n \n \n");
  changePointVisibility("Operadores de comparaÃ§Ã£o",1);
} else if ( selectedChoice.name == "Continuar") {
  changeLayer("cavernadois2.gif");
} else if ( selectedChoice.name == "Seguir") {
  changeLayer("cavernadoisboss.gif");
} else if ( selectedChoice.name == "Volltar") {
  changeLayer("CavernaDois");
} else if ( selectedChoice.name == "Arregar") {
  changeLayer("cavernadois2.gif");
}

if ( selectedChoice.name == "Derrotar X") {
  changeLayer("decisao1.png");
} else if ( selectedChoice.name == "Operador Soma ( + )") {
  changeLayer("decisao2.png");
} else if ( selectedChoice.name == "Operador DivisÃ£o ( / )") {
  changeLayer("CavernaUmBauF.gif");
} else if ( selectedChoice.name == "Abrir BaÃº ( NÃ­vel 1 )") {
  changeLayer("mapa.gif");
} else if ( selectedChoice.name == "Pegar Mapa/Espada 1") {
  changeLayer("CavernaUmBauA.gif");
} else if ( selectedChoice.name == "Voltar p/ vila") {
  changeLayer("vila");
  changePointVisibility("Cavernas",1);
  changePointVisibility("Cavernas ( NÃ­vel 2 )",2);
  changePointVisibility("Biblioteca ( NÃ­vel 1 )",2);
  popup("PARABÃ‰NS! \n VocÃª desbloqueou a biblioteca!! \n Agora vocÃª pode acessar o itens coletados atÃ© o momento. \n Explore mais as cavernas para desbloquear novos livros. \n E nÃ£o se esqueÃ§a, ir a biblioteca ajuda no cansaÃ§o.");
  popup("\n \n VocÃª desbloqueou novos caminhos nas cavernas!! \n Volte para as cavernas e explore o novo caminho. \n Cuidado, esta pode ser mais perigosa...");
} else if ( selectedChoice.name == "Biblioteca ( NÃ­vel 1 )") {
  changeLayer("biblioteca.gif");
} else if ( selectedChoice.name == "Livro 1") {
  popup("Python \n Python Ã© uma linguagem de alto nÃ­vel. Aquelas em que os cÃ³digos tÃªm uma sintaxe prÃ³xima a linguagem humana, assim como Ruby, que tem uma tipagem dinÃ¢mica. EntÃ£o isso significa que ela utiliza recurso em script e Ã© orientada a objetos. \n \n \n  Entrada e SaÃ­da de Dados (E/S) \n Todo programa possui trÃªs componentes bÃ¡sicos: uma entrada especÃ­fica, uma sequÃªncia de regras (passos) a serem executadas sobre essa entrada, e uma saÃ­da. \n Na prÃ¡tica, um programa de computador pode receber sua entrada de muitas formas: por meio do teclado (quando o usuÃ¡rio digita alguma coisa), via linha de comando, por meio de arquivos de entrada, ou atÃ© mesmo por meio de cliques do usuÃ¡rio em certos botÃµes ou Ã¡reas da tela do computador.\n  A funÃ§Ã£o print() Ã© utilizada para o programa exibir e ler as entradas e mensagens.  Por exemplo: \n \n   soma = 10+20  print(OlÃ¡, mundo!) \n  print(A soma Ã©, soma) \n \n   Escreve na tela do computador \n   OlÃ¡, mundo! \n  A soma Ã© 30 \n\n  Para ler dados digitados pelo usuÃ¡rio durante a execuÃ§Ã£o do programa, utilizamos a funÃ§Ã£o input() (literalmente entrada, em inglÃªs). O exemplo abaixo ilustra o uso dessa funÃ§Ã£o: \n  print(Digite seu nome:)\n nome = input()\n print(Bem-vindo, , nome) \n \n \n  AtribuiÃ§Ãµes \n HÃ¡ menos exigÃªncias â€œgramaticaisâ€, como parÃªnteses em estruturas de seleÃ§Ã£o ou ponto-e-vÃ­rgula no fim da linha, e o cÃ³digo Ã© Um comando Ã© uma unidade de cÃ³digo que o interpretador pode executar. \n  Um comando de atribuiÃ§Ã£o tem a seguinte forma: \n \n     variÃ¡vel = expressÃ£o  \n \n  Exemplos: \n nome = 'Labirinto' \n  num  = 15 \n soma = 0  \n  soma = soma + num \n \n \n  VariÃ¡vel \n Uma variÃ¡vel Ã© um nome que se refere a um valor. Um comando de atribuiÃ§Ã£o cria uma nova variÃ¡vel e lhe dÃ¡ um valor. \n   VariÃ¡veis sÃ£o usadas para guardarmos valores que serÃ£o usados mais tarde no programa. \n \n  Principais tipos de variavel: \n Tipo Inteiro (int) = O tipo inteiro Ã© um tipo composto por caracteres numÃ©ricos (algarismos) inteiros. Ã‰ um tipo usado para um nÃºmero que pode ser escrito sem um componente decimal, podendo ter ou nÃ£o sinal, isto Ã©: ser positivo ou negativo. \n idade = 18  \n  ano = 2002  \n \n   Ponto Flutuante ou Decimal (float) = Ã‰ um tipo composto por caracteres numÃ©ricos (algarismo) decimais. O famoso ponto flutuante Ã© um tipo usado para nÃºmeros racionais (nÃºmeros que podem ser representados por uma fraÃ§Ã£o) informalmente conhecido como â€œnÃºmero quebradoâ€.  \n altura = 1.80  \n  peso = 73.55   \n \n    String (str) = Ã‰ um conjunto de caracteres dispostos numa determinada ordem, geralmente utilizada para representar palavras, frases ou textos.  \n  nome = 'Labirinto'  \n  profissao = 'Engenheiro de Software'   \n \n    Boolean (bool)  = Tipo de dado lÃ³gico que pode assumir apenas dois valores: falso ou verdadeiro (False ou True em Python). Na lÃ³gica computacional, podem ser considerados como 0 ou 1.  \n  fim_de_semana = True  \n  feriado = False \n \n \n  Palavra Reservada \n Uma palavra que Ã© utilizada pelo compilador/interpretador na anÃ¡lise sintÃ¡tica do programa; vocÃª nÃ£o pode usar palavras reservadas como if, def e while como nomes de variÃ¡veis.\n \n \n  Incremento \n Os operadores de incremento tem a finalidade de acelerar o processo de adicionar uma unidade de um determinado nÃºmero. Geralmente, a utilizaÃ§Ã£o desse operadore estÃ¡ relacionado com os laÃ§os de repetiÃ§Ã£o, haja vista que os mesmos, geralmente, alteram o valor de suas variÃ¡veis para alterar o item a ser manipulado. \n  Sintaxe incremento:  \n \n  count += 1 \n \n   Exemplo: \n \n   num = 1 \n  num += 1 \n  print(num) \n \n   R: 2 \n \n \n  Decremento \n Os operadores de decremento tem a finalidade de acelerar o processo remover uma unidade de um determinado nÃºmero. Geralmente, a utilizaÃ§Ã£o desse operadores estÃ¡ relacionado com os laÃ§os de repetiÃ§Ã£o, haja vista que os mesmos, geralmente, alteram o valor de suas variÃ¡veis para alterar o item a ser manipulado.  \n  Sintaxe decremento:  \n \n  count -= 1 \n \n   Exemplo: \n \n   num = 1 \n  num -= 1 \n  print(num) \n \n   R: 0 \n \n \n  ComentÃ¡rios \n Os comentÃ¡rio sÃ£o muito Ãºteis na hora de documentar ou explicar certos trechos do seu cÃ³digo, sendo ignorados durante a execuÃ§Ã£o do script e podem ocupar uma ou mais linhas. \n \n    ComentÃ¡rios inline \n   SÃ£o comentÃ¡rios de â€œuma linhaâ€, indicados pelo sÃ­mbolo # (cerquilha, antÃ­fen, cardinal ou octothorpeâ€¦ ou ainda como vocÃª queira chamÃ¡-lo). \n   Tudo que estÃ¡ apÃ³s o sÃ­mbolo # Ã© ignorado pelo interpretador. \n  \n    # Este Ã© um comentÃ¡rio de uma linha \n \n    ComentÃ¡rios de VÃ¡rias Linhas\n   Caso seja necessÃ¡rio utilizar comentÃ¡rios que ocupem vÃ¡rias linhas, podemos utilizar trÃªs aspas simples no inÃ­cio, â€â€™, e outras trÃªs aspas simples, â€â€™, no final dos comentÃ¡rios. \n    ''' \n   Este Ã© um comentÃ¡rio \n   de vÃ¡rias \n   linhas utilizando-se aspas simples \n   ''' \n \n \n  Operadores NumÃ©ricos Os operadores sÃ£o utilizados para construir expressÃµes lÃ³gicas, aritmÃ©ticas, associativas, atribuir valores a variÃ¡veis e comparÃ¡-los. Trata-se de um recurso utilizado nas tarefas mais fundamentais da programaÃ§Ã£o e de conhecimento obrigatÃ³rio para qualquer programador. \n Os operadores aritmÃ©ticos sÃ£o utilizados na execuÃ§Ã£o de operaÃ§Ãµes matemÃ¡ticas, tais como a soma e a subtraÃ§Ã£o, por exemplo: \n \n    + = Realiza a soma entre operandos, adiciona o sinal de positivo ao nÃºmero. \n  soma = 10 + 20 \n \n    - = Realiza a subtraÃ§Ã£o entre operandos, adiciona o sinal de negativo ao nÃºmero. \n  subtraÃ§Ã£o = - 10 - 20 \n \n    * = Realiza a multiplicaÃ§Ã£o entre operandos. \n  multiplicaÃ§Ã£o = 10 * 20 \n \n    / = Realiza a divisÃ£o entre operandos. \n  divisÃ£o= 20/10 \n \n    ** = Retorna um nÃºmero elevado a potÃªncia de outro. \n  exponenciaÃ§Ã£o = 2 ** 2 \n \n \n");
} else if ( selectedChoice.name == "Subir") {
  changeLayer("CavernaUmBoss.gif");
} else if ( selectedChoice.name == "Cavernas ( NÃ­vel 2 )") {
  changeLayer("caminhos");
  changePointVisibility("Caverna 2",2);
  changePointVisibility("Caverna 1",1);
} else if ( selectedChoice.name == "Villa") {
  changeLayer("vila");
}

if ( selectedChoice.name == "Derrotar R") {
  changeLayer("decisao3.png");
} else if ( selectedChoice.name == "R = TRUE") {
  changeLayer("decisao4.png");
} else if ( selectedChoice.name == "R : FALSE") {
  changeLayer("cavernadoisbauf.gif");
} else if ( selectedChoice.name == "Abrir BaÃº ( NÃ­vel 2 )") {
  changeLayer("mapa2.gif");
} else if ( selectedChoice.name == "Pegar Mapa/Espada 2") {
  changeLayer("cavernadoisbaua.gif");
} else if ( selectedChoice.name == "Voltar p vila ") {
  changeLayer("vila");
  changePointVisibility("Cavernas ( NÃ­vel 2 )",1);
  changePointVisibility("Biblioteca ( NÃ­vel 1 )",1);
  changePointVisibility("Cavernas ( NÃ­vel 3 )",2);
  changePointVisibility("Biblioteca ( NÃ­vel 2 )",2);
  popup("PARABÃ‰NS! \n VocÃª desbloqueou um novo livro na biblioteca!! \n Agora vocÃª pode acessar o itens coletados atÃ© o momento. \n Explore mais as cavernas para desbloquear novos livros. \n E nÃ£o se esqueÃ§a, ir a biblioteca ajuda no cansaÃ§o.");
  popup("\n \n VocÃª desbloqueou novos caminhos nas cavernas!! \n Volte para as cavernas e explore o novo caminho. \n Cuidado, esta pode ser mais perigosa...");
} else if ( selectedChoice.name == "Biblioteca ( NÃ­vel 2 )") {
  changeLayer("biblioteca2.gif");
} else if ( selectedChoice.name == "Livro 2") {
  popup("AND \n AND = Retorna True se todas as condiÃ§Ãµes forem verdadeiras, caso contrÃ¡rio retorna False \n \n    TRUE and TRUE = TRUE \n TRUE and FALSE = FALSE \n FALSE and TRUE = FALSE \n FALSE and FALSE = FALSE \n \n \n  OR \n OR = Retorna True se uma das condiÃ§Ãµes for verdadeiras, caso contrÃ¡rio retorna False \n \n  TRUE or TRUE = TRUE \n TRUE or FALSE = TRUE \n FALSE or TRUE = TRUE \n FALSE or FALSE = FALSE \n \n \n	  NOT \n NOT = Inverte o resultado: se o resultado da expressÃ£o for True, o operador retorna false \n \n   NOT( FALSE ) = TRUE \n NOT( TRUE ) = FALSE \n \n \n	  if \n Quando programamos, muitas vezes precisamos que determinado bloco de cÃ³digo seja executado apenas se uma determinada condiÃ§Ã£o for verdadeira. Em casos assim, devemos fazer uso de uma estrutura de condiÃ§Ã£o. \n   O if Ã© uma estrutura de condiÃ§Ã£o que permite avaliar uma expressÃ£o e, de acordo com seu resultado, executar uma determinada aÃ§Ã£o. \n  No cÃ³digo a seguir temos um exemplo de uso do if no qual verificamos se a variÃ¡vel idade Ã© menor que 20. Em caso positivo, imprimimos uma mensagem na tela e em caso negativo o cÃ³digo seguirÃ¡ normalmente. \n \n    idade = 18 \n  if idade < 20: \n          print('VocÃª Ã© jovem!') \n \n   Como podemos notar, essa estrutura Ã© formada pela palavra reservada if, seguida por uma condiÃ§Ã£o e por dois pontos (:). As linhas abaixo dela formam o bloco de instruÃ§Ãµes que serÃ£o executadas se a condiÃ§Ã£o for atendida. Para isso, elas devem ser identadas corretamente, respeitando a especificaÃ§Ã£o do Python. \n \n \n  if/else \n  Vimos anteriormente como utilizar o if para executar uma aÃ§Ã£o caso uma condiÃ§Ã£o seja atendida. No entanto, nenhum comportamento especÃ­fico foi definido para o caso de a condiÃ§Ã£o nÃ£o ser satisfeita. Quando isso Ã© necessÃ¡rio, precisamos utilizar a reservada else. \n \n   idade = 18  \n  if idade >= 18:  \n      print('maior de idade') \n  else: \n      print('menor de idade') \n \n    Dessa vez, caso a condiÃ§Ã£o avaliada nÃ£o seja atendida, definimos o fluxo alternativo que o cÃ³digo deve seguir. Ou seja, se a idade nÃ£o for maior ou igual a 18, o bloco abaixo da palavra reservada else deverÃ¡ ser executado. Nesse caso, temos apenas uma instruÃ§Ã£o de impressÃ£o. \n \n \n  Operadores de comparaÃ§Ã£o \n  Um assunto diretamente relacionado Ã s estruturas de condiÃ§Ã£o e repetiÃ§Ã£o sÃ£o os operadores de comparaÃ§Ã£o. Como o nome sugere, eles sÃ£o usados para avaliar o valor de duas ou mais expressÃµes/variÃ¡veis e comparÃ¡-las. \n \n    SÃ­mbolo	DefiniÃ§Ã£o  \n ==	Igual  \n !=	Diferente \n >	Maior que \n <	Menor que \n >=	Maior ou igual que \n <=	Menor ou igual que \n \n \n");
} else if ( selectedChoice.name == "Cavernas ( NÃ­vel 3 )") {
  changeLayer("caminhos");
  changePointVisibility("Caverna 3",2);
  changePointVisibility("Caverna 2",1);
}

if ( selectedChoice.name == "for") {
  popup("Em algumas situaÃ§Ãµes Ã© comum que uma mesma instruÃ§Ã£o (ou conjunto delas) precise ser executada vÃ¡rias vezes seguidas. Nesses casos, normalmente utilizamos um loop (ou laÃ§o de repetiÃ§Ã£o) que permite executar o mesmo bloco de cÃ³digo enquanto uma condiÃ§Ã£o Ã© atendida. Em Python, os loops sÃ£o codificados com as estruturas de repetiÃ§Ã£o for e while. \n \n  FOR \n O laÃ§o for nos permite percorrer os itens de uma coleÃ§Ã£o e, para cada um deles, executar o bloco de cÃ³digo declarado no loop. Sua sintaxe Ã© a seguinte: \n \n  for variavel in lista \n comandos \n \n  Enquanto percorremos a lista de valores, a variÃ¡vel indicada no for receberÃ¡, a cada iteraÃ§Ã£o, um item da coleÃ§Ã£o. Assim, podemos executar algum processamento com esse elemento. No cÃ³digo abaixo percorremos a lista nomes e imprimimos cada elemento. \n \n  nomes = ['Pedro', 'JoÃ£o', 'Leticia'] \n for n in nomes: \n      print(n) \n \n  A variÃ¡vel definida na nomes Ã© uma lista inicializada com uma sequÃªncia de valores do tipo string. A instruÃ§Ã£o for percorre todos esses elementos, um por vez e, em cada caso, atribui o valor do item Ã  variÃ¡vel n, que Ã© impressa em seguida. O resultado, entÃ£o, Ã© a impressÃ£o de todos os nomes contidos na lista. \n \n \n");
  changePointVisibility("for",1);
} else if ( selectedChoice.name == "while") {
  popup("WHILE \n  A estrutura de repetiÃ§Ã£o Ã© um recurso das linguagens de programaÃ§Ã£o responsÃ¡vel por executar um bloco de cÃ³digo repetidas vezes enquanto determinada condiÃ§Ã£o Ã© atendida. No Python, possuÃ­mos dois tipos de estruturas de repetiÃ§Ã£o: for e while. \n \n  O comando while faz com que um conjunto de instruÃ§Ãµes seja executado enquanto uma condiÃ§Ã£o Ã© atendida. Quando o resultado dessa condiÃ§Ã£o passa a ser falso, a execuÃ§Ã£o do loop Ã© interrompida, como mostra o exemplo a seguir: \n \n  1 contador = 0 \n 2 while (contador < 5): \n 3       print(contador) \n 4       contador   = contador + 1 \n \n  Neste cÃ³digo, enquanto a variÃ¡vel contador, inicializada com 0, for menor do que 5, as instruÃ§Ãµes das linhas 3 e 4 serÃ£o executadas. \n \n \n");
  changePointVisibility("while",1);
} else if ( selectedChoice.name == "while-else") {
  popup(" While-else\n Ao final do while podemos utilizar a instruÃ§Ã£o else. O propÃ³sito disso Ã© executar alguma instruÃ§Ã£o ou bloco de cÃ³digo ao final do loop, como podemos ver no exemplo a seguir: \n \n  contador = 0 \n while (contador < 5): \n       print(contador) \n       contador = contador + 1 \n else: \n       print(O loop while foi encerrado com sucesso!) \n \n  Assim como acontece com for/else, declarando o else ao final do while Ã© possÃ­vel executar um cÃ³digo ao final do loop. Neste caso serÃ¡ impressa a mensagem: â€œO loop while foi encerrado com sucesso!â€. \n \n \n");
  changePointVisibility("while-else",1);
} else if ( selectedChoice.name == "Listas") {
  popup("Listas \n   Durante o desenvolvimento de software, independentemente de plataforma e linguagem, Ã© comum a necessidade de lidar com listas. Por exemplo, elas podem ser empregadas para armazenar contatos telefÃ´nicos ou tarefas. \n   Uma lista Ã© uma estrutura de dados composta por itens organizados de forma linear, na qual cada um pode ser acessado a partir de um Ã­ndice, que representa sua posiÃ§Ã£o na coleÃ§Ã£o (iniciando em zero). \n \n  Em Python, uma lista Ã© representada como uma sequÃªncia de objetos separados por vÃ­rgula e dentro de colchetes [], assim, uma lista vazia, por exemplo, pode ser representada por colchetes sem nenhum conteÃºdo. A Listagem 1 mostra algumas possibilidades de criaÃ§Ã£o desse tipo de objeto. \n \n  lista = [] \n lista = ['O carro','peixe',123,111]  \n \n \n");
  changePointVisibility("Listas",1);
} else if ( selectedChoice.name == "OperaÃ§Ãµes com Lista") {
  popup("Op com Listas \n  A linguagem Python dispÃµe de vÃ¡rios mÃ©todos e operadores para auxiliar na manipulaÃ§Ã£o de listas. O primeiro e mais bÃ¡sico Ã© o operador de acesso aos seus itens a partir dos Ã­ndices. Para compreendÃª-lo, Ã© importante entender como os dados sÃ£o armazenados nessa estrutura. \n \n  lista = ['O carro','peixe',123,111] \n posiÃ§Ã£o [0, 1, 2, 3] \n \n  A lista representada Ã© composta por quatro elementos, cujos Ã­ndices variam de zero a trÃªs. Por exemplo, o primeiro objeto, no Ã­ndice 0, Ã© a string 'O carro'. Tendo em mente essa organizaÃ§Ã£o interna, podemos acessar cada um dos elementos utilizando a sintaxe lista[Ã­ndice] \n \n  lista[0] \n R: 'O carro' \n \n  lista[2] \n R: 123  \n \n \n");
  changePointVisibility("OperaÃ§Ãµes com Lista",1);
} else if ( selectedChoice.name == "Seguir em frente") {
  changeLayer("CavernaTres2.gif");
} else if ( selectedChoice.name == "Voltar p/ lava") {
  changeLayer("CavernaTres");
} else if ( selectedChoice.name == "Ir em frente") {
  changeLayer("CavernaTresBoss.gif");
} else if ( selectedChoice.name == "Desistir") {
  changeLayer("CavernaTres2.gif");
} else if ( selectedChoice.name == "Derrotar P") {
  changeLayer("decisao5.png");
}

if ( selectedChoice.name == "R - FALSE") {
  changeLayer("decisao6");
} else if ( selectedChoice.name == "A = 18") {
  changeLayer("CavernaTresBauF.gif");
} else if ( selectedChoice.name == "Abrir BaÃº ( NÃ­vel 3 )") {
  changeLayer("mapa3.gif");
} else if ( selectedChoice.name == "Pegar Mapa/Chave 3") {
  changeLayer("CavernaTresBauA.gif");
} else if ( selectedChoice.name == "Voltar para vila") {
  changeLayer("vila");
  changePointVisibility("Cavernas ( NÃ­vel 3 )",1);
  changePointVisibility("Biblioteca ( NÃ­vel 2 )",1);
  changePointVisibility("Labirinto",1);
  changePointVisibility("Biblioteca ( NÃ­vel 3 )",2);
  popup("PARABÃ‰NS! \n VocÃª desbloqueou um novo livro na biblioteca!! \n Agora vocÃª pode acessar o itens coletados atÃ© o momento. \n Explore mais as cavernas para desbloquear novos livros. \n E nÃ£o se esqueÃ§a, ir a biblioteca ajuda no cansaÃ§o.");
  popup("\n \n VocÃª desbloqueou novos caminhos nas cavernas!! \n Volte para as cavernas e explore o novo caminho. \n Cuidado, esta pode ser mais perigosa...");
  changePointVisibility("VER MAPA",2);
  changePointVisibility("Encontrar o papai",2);
} else if ( selectedChoice.name == "Biblioteca ( NÃ­vel 3 )") {
  changeLayer("biblioteca3.gif");
} else if ( selectedChoice.name == "Livro 3") {
  popup("for \n Em algumas situaÃ§Ãµes Ã© comum que uma mesma instruÃ§Ã£o (ou conjunto delas) precise ser executada vÃ¡rias vezes seguidas. Nesses casos, normalmente utilizamos um loop (ou laÃ§o de repetiÃ§Ã£o) que permite executar o mesmo bloco de cÃ³digo enquanto uma condiÃ§Ã£o Ã© atendida. Em Python, os loops sÃ£o codificados com as estruturas de repetiÃ§Ã£o for e while. \n \n  FOR \n O laÃ§o for nos permite percorrer os itens de uma coleÃ§Ã£o e, para cada um deles, executar o bloco de cÃ³digo declarado no loop. Sua sintaxe Ã© a seguinte: \n \n  for variavel in lista \n comandos \n \n  Enquanto percorremos a lista de valores, a variÃ¡vel indicada no for receberÃ¡, a cada iteraÃ§Ã£o, um item da coleÃ§Ã£o. Assim, podemos executar algum processamento com esse elemento. No cÃ³digo abaixo percorremos a lista nomes e imprimimos cada elemento. \n \n  nomes = ['Pedro', 'JoÃ£o', 'Leticia'] \n for n in nomes: \n      print(n) \n \n  A variÃ¡vel definida na nomes Ã© uma lista inicializada com uma sequÃªncia de valores do tipo string. A instruÃ§Ã£o for percorre todos esses elementos, um por vez e, em cada caso, atribui o valor do item Ã  variÃ¡vel n, que Ã© impressa em seguida. O resultado, entÃ£o, Ã© a impressÃ£o de todos os nomes contidos na lista. \n \n \n  WHILE \n  A estrutura de repetiÃ§Ã£o Ã© um recurso das linguagens de programaÃ§Ã£o responsÃ¡vel por executar um bloco de cÃ³digo repetidas vezes enquanto determinada condiÃ§Ã£o Ã© atendida. No Python, possuÃ­mos dois tipos de estruturas de repetiÃ§Ã£o: for e while. \n \n  O comando while faz com que um conjunto de instruÃ§Ãµes seja executado enquanto uma condiÃ§Ã£o Ã© atendida. Quando o resultado dessa condiÃ§Ã£o passa a ser falso, a execuÃ§Ã£o do loop Ã© interrompida, como mostra o exemplo a seguir: \n \n  1 contador = 0 \n 2 while (contador < 5): \n 3       print(contador) \n 4       contador   = contador + 1 \n \n  Neste cÃ³digo, enquanto a variÃ¡vel contador, inicializada com 0, for menor do que 5, as instruÃ§Ãµes das linhas 3 e 4 serÃ£o executadas. \n \n \n  While-else\n Ao final do while podemos utilizar a instruÃ§Ã£o else. O propÃ³sito disso Ã© executar alguma instruÃ§Ã£o ou bloco de cÃ³digo ao final do loop, como podemos ver no exemplo a seguir: \n \n  contador = 0 \n while (contador < 5): \n       print(contador) \n       contador = contador + 1 \n else: \n       print(O loop while foi encerrado com sucesso!) \n \n  Assim como acontece com for/else, declarando o else ao final do while Ã© possÃ­vel executar um cÃ³digo ao final do loop. Neste caso serÃ¡ impressa a mensagem: â€œO loop while foi encerrado com sucesso!â€. \n \n \n  Listas \n   Durante o desenvolvimento de software, independentemente de plataforma e linguagem, Ã© comum a necessidade de lidar com listas. Por exemplo, elas podem ser empregadas para armazenar contatos telefÃ´nicos ou tarefas. \n   Uma lista Ã© uma estrutura de dados composta por itens organizados de forma linear, na qual cada um pode ser acessado a partir de um Ã­ndice, que representa sua posiÃ§Ã£o na coleÃ§Ã£o (iniciando em zero). \n \n  Em Python, uma lista Ã© representada como uma sequÃªncia de objetos separados por vÃ­rgula e dentro de colchetes [], assim, uma lista vazia, por exemplo, pode ser representada por colchetes sem nenhum conteÃºdo. A Listagem 1 mostra algumas possibilidades de criaÃ§Ã£o desse tipo de objeto. \n \n  lista = [] \n lista = ['O carro','peixe',123,111]  \n \n \n  Op com Listas \n  A linguagem Python dispÃµe de vÃ¡rios mÃ©todos e operadores para auxiliar na manipulaÃ§Ã£o de listas. O primeiro e mais bÃ¡sico Ã© o operador de acesso aos seus itens a partir dos Ã­ndices. Para compreendÃª-lo, Ã© importante entender como os dados sÃ£o armazenados nessa estrutura. \n \n  lista = ['O carro','peixe',123,111] \n posiÃ§Ã£o [0, 1, 2, 3] \n \n  A lista representada Ã© composta por quatro elementos, cujos Ã­ndices variam de zero a trÃªs. Por exemplo, o primeiro objeto, no Ã­ndice 0, Ã© a string 'O carro'. Tendo em mente essa organizaÃ§Ã£o interna, podemos acessar cada um dos elementos utilizando a sintaxe lista[Ã­ndice] \n \n  lista[0] \n R: 'O carro' \n \n  lista[2] \n R: 123  \n \n \n");
} else if ( selectedChoice.name == "Encontrar o papai") {
  changeLayer("floresta.jpg");
} else if ( selectedChoice.name == "VER MAPA") {
  changeLayer("mapatotal");
}