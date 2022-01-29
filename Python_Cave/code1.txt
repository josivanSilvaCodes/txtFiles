if ( selectedChoice.name == "CrÃ©ditos") {
  changeLayer("CrÃ©ditos");
}
if ( selectedChoice.name == "Voltar ao inÃ­cio") {
  changeLayer("Main");
}
if ( selectedChoice.name == "Jogar") {
  changeLayer("Fase1");
  changePointVisibility("Questionario",1);
}
if ( selectedChoice.name == "Ensinamento") {
  popup("VocÃª estÃ¡ em busca da cura da cidade.");
  popup("O jogo comeÃ§ou! VocÃª irÃ¡ passar por diversos locais do mapa, e neles terÃ£o diversas informaÃ§Ãµes que vocÃª terÃ¡ que usar no futuro, entÃ£o, anote.");
  popup("Quando conseguir entender os 10 ensinamentos, volte aqui e selecione Questionario para ter um desafio final para lutar em busca da cura.");
}
if ( selectedChoice.name == "Tipo de dados") {
  popup("Um tipo de dado representa e determina um conjunto de valores, alguns tipos bÃ¡sicos sÃ£o: ");
  popup("int: NÃºmeros inteiros ");
  popup("float: NÃºmeros reais");
  popup("bool: Valor booleano, ou seja, Verdadeiro(true) ou Falso(False)");
  popup("str: Palavras, frases ou textos.");
  popup("");
  popup("Fique atento, vocÃª poderÃ¡ utilizar essa informaÃ§Ã£o no futuro.");
}
if ( selectedChoice.name == "If/Else") {
  popup("As estruturas condicionais permitem que um programa execute diferentes comandos de acordo com as condiÃ§Ãµes estabelecidas. Elas estÃ£o presentes em diversas linguagens de programaÃ§Ã£o e todo profissional da Ã¡rea precisa saber como utilizÃ¡-las.");
  popup("SÃ£o elas: if e else");
  popup("A condicional if  Ã© uma estrutura condicional que executa a afirmaÃ§Ã£o, dentro do bloco, se determinada condiÃ§Ã£o for verdadeira. Se for falsa, executa as afirmaÃ§Ãµes dentro de else.");
  popup("");
  popup("");
}
if ( selectedChoice.name == "Ir para 2Âª questÃ£o") {
  changeLayer("casesensitive.png");
}
if ( selectedChoice.name == "Ir para 3Âª questÃ£o") {
  changeLayer("Ã© uma sequÃªncia de dados ocupando posiÃ§Ãµes  consecutivas de mem.png");
}
if ( selectedChoice.name == "Ir para 4Âª questÃ£o") {
  changeLayer("identaÃ§Ã£o.png");
}
if ( selectedChoice.name == "Ir para 5Âª questÃ£o") {
  changeLayer("Selecione o que nÃ£o Ã© um tipo de dado.png");
}
if ( selectedChoice.name == "Ir para 6Âª questÃ£o") {
  changeLayer("repeticao.png");
}
if ( selectedChoice.name == "Ir para 7Âª questÃ£o") {
  changeLayer("def.png");
}
if ( selectedChoice.name == "FunÃ§Ã£o/def") {
  popup("Em Python, uma funÃ§Ã£o Ã© uma sequÃªncia de comandos que executa alguma tarefa e que tem um nome. A sua principal finalidade Ã© nos ajudar a organizar programas em pedaÃ§os que correspondam a como imaginamos uma soluÃ§Ã£o do problema");
  popup("VocÃª pode inventar qualquer nome para as funÃ§Ãµes que vocÃª cria, exceto que vocÃª nÃ£o pode usar um nome que Ã© uma palavra reservada em Python, e que os nomes devem seguir a regra de identificadores permitidos.");
  popup("Na definiÃ§Ã£o de uma funÃ§Ã£o, a palavra reservada no cabeÃ§alho Ã© def, que Ã© seguida pelo nome da funÃ§Ã£o e alguns parÃ¢metros entre parÃªnteses. A lista de parÃ¢metros pode ser vazia ou conter qualquer nÃºmero de parÃ¢metros separados pos vÃ­rgulas. Em qualquer caso, os parÃªnteses sÃ£o obrigatÃ³rios.");
}
if ( selectedChoice.name == "Vetores") {
  popup("Um vetor Ã© uma sequÃªncia de dados ocupando posiÃ§Ãµes consecutivas de memÃ³ria e por isso existe uma ordem natural (o primeiro elemento, o segundo e assim por diante).");
  changePointVisibility("Questionario",2);
}
if ( selectedChoice.name == "Estruturas de RepetiÃ§Ã£o") {
  popup("A estrutura de repetiÃ§Ã£o Ã© um recurso das linguagens de programaÃ§Ã£o responsÃ¡vel por executar um bloco de cÃ³digo repetidas vezes enquanto determinada condiÃ§Ã£o Ã© atendida. No Python, possuÃ­mos dois tipos de estruturas de repetiÃ§Ã£o: for e while.");
  popup("O comando while faz com que um conjunto de instruÃ§Ãµes seja executado enquanto uma condiÃ§Ã£o Ã© atendida.");
  popup("A estrutura de repetiÃ§Ã£o for permite executar um bloco de cÃ³digos repetidas vezes atÃ© que uma condiÃ§Ã£o seja verdadeira. Na linguagem Python, ela Ã© utilizada para percorrer elementos em sequÃªncia, como uma string, uma lista, uma tupla ou objetos iterÃ¡veis.");
}
if ( selectedChoice.name == "Case Sensitive") {
  popup("A linguagem Python Ã© uma linguagem case-sensitive ou seja, quando um software Ã© capaz de analisar uma cadeia de caracteres, avaliar a existÃªncia de caixa alta e caixa baixa e comportar-se de diferentes maneiras em funÃ§Ã£o disso.");
}
if ( selectedChoice.name == "IdentaÃ§Ã£o") {
  popup("IndentaÃ§Ã£o Ã© uma forma de arrumar o cÃ³digo, fazendo com que algumas linhas fiquem mais Ã  direita que outras, Ã  medida que adicionamos espaÃ§os em seu inÃ­cio. Para a maioria das linguagens a indentaÃ§Ã£o nÃ£o Ã© obrigatÃ³ria, mas no caso Python isso Ã© diferente.");
  popup("A indentaÃ§Ã£o Ã© uma caracterÃ­stica importante no Python, pois alÃ©m de promover a legibilidade Ã© essencial para o bom funcionamento do cÃ³digo. Em outras palavras, se a indentaÃ§Ã£o nÃ£o estiver adequada o programa pode se comportar de forma inesperada ou atÃ© mesmo nÃ£o compilar.");
}
if ( selectedChoice.name == "Questionario") {
  changeLayer("pergunta1");
}
if ( selectedChoice.name == "DepÃ³sito") {
  changeLayer("Oeste");
}
if ( selectedChoice.name == "SalÃ£o Principal") {
  changeLayer("Fase1");
}
if ( selectedChoice.name == "Biblioteca") {
  changeLayer("leste");
}
if ( selectedChoice.name == "SalÃ£o Principal") {
  changeLayer("Fase1");
}
if ( selectedChoice.name == "Lounge") {
  changeLayer("ultim.png");
}
if ( selectedChoice.name == "LaboratÃ³rio") {
  changeLayer("abaixo.png");
}
if ( selectedChoice.name == "SÃ³tÃ£o") {
  changeLayer("sotao.png");
}
if ( selectedChoice.name == "Lugar Seguro") {
  changeLayer("testesul.png");
}
if ( selectedChoice.name == "Estrutura de condiÃ§Ã£o") {
  popup("VocÃª acertou!! If e else sÃ£o estruturas de condiÃ§Ã£o.");
  popup("Por responder este questionÃ¡rio vocÃª recebeu:");
  popup("+5 de Experiencia");
  popup("+5 de Sabedoria");
  changePointVisibility("Estrutura de condiÃ§Ã£o",1);
  changePointVisibility("FunÃ§Ãµes",1);
  changePointVisibility("Variaveis",1);
  changePointVisibility("Estrutura de repetiÃ§Ã£o",1);
}
if ( selectedChoice.name == "FunÃ§Ãµes") {
  popup("VocÃª errou! Leia novamente o ensinamento e volte para refazer o teste!");
  changePointVisibility("Estrutura de condiÃ§Ã£o",1);
  changePointVisibility("FunÃ§Ãµes",1);
  changePointVisibility("Variaveis",1);
  changePointVisibility("Estrutura de repetiÃ§Ã£o",1);
}
if ( selectedChoice.name == "Variaveis") {
  popup("VocÃª errou! Leia novamente o ensinamento e volte para refazer o teste!");
  changePointVisibility("Estrutura de condiÃ§Ã£o",1);
  changePointVisibility("FunÃ§Ãµes",1);
  changePointVisibility("Variaveis",1);
  changePointVisibility("Estrutura de repetiÃ§Ã£o",1);
}
if ( selectedChoice.name == "Estrutura de repetiÃ§Ã£o") {
  popup("VocÃª errou! Leia novamente o ensinamento e volte para refazer o teste!");
  changePointVisibility("Estrutura de condiÃ§Ã£o",1);
  changePointVisibility("FunÃ§Ãµes",1);
  changePointVisibility("Variaveis",1);
  changePointVisibility("Estrutura de repetiÃ§Ã£o",1);
}
if ( selectedChoice.name == "False") {
  popup("VocÃª acertou!! A linguagem python Ã‰ uma linguagem case sensitive.");
  popup("Por responder este questionÃ¡rio vocÃª recebeu:");
  popup("+5 de Experiencia");
  popup("+5 de Sabedoria");
  changePointVisibility("True",1);
  changePointVisibility("False",1);
}
if ( selectedChoice.name == "Vetor") {
  popup("VocÃª acertou! Vetor Ã© uma sequencia de dados ocupando posiÃ§Ãµes consecutivas de memÃ³ria");
  popup("Por responder este questionÃ¡rio vocÃª recebeu:");
  popup("+5 de Experiencia");
  popup("+5 de Sabedoria");
  changePointVisibility("Vetor",1);
  changePointVisibility("Value",1);
  changePointVisibility("Return",1);
  changePointVisibility("FunÃ§Ã£o",1);
}
if ( selectedChoice.name == "Value") {
  popup("VocÃª errou! Leia novamente o ensinamento e volte para refazer o teste!");
  changePointVisibility("Vetor",1);
  changePointVisibility("Value",1);
  changePointVisibility("Return",1);
  changePointVisibility("FunÃ§Ã£o",1);
}
if ( selectedChoice.name == "Return") {
  popup("VocÃª errou! Leia novamente o ensinamento e volte para refazer o teste!");
  changePointVisibility("Vetor",1);
  changePointVisibility("Value",1);
  changePointVisibility("Return",1);
  changePointVisibility("FunÃ§Ã£o",1);
}
if ( selectedChoice.name == "FunÃ§Ã£o") {
  popup("VocÃª errou! Leia novamente o ensinamento e volte para refazer o teste!");
  changePointVisibility("Vetor",1);
  changePointVisibility("Value",1);
  changePointVisibility("Return",1);
  changePointVisibility("FunÃ§Ã£o",1);
}
if ( selectedChoice.name == "Verdadeiro") {
  popup("VocÃª acertou!! A identaÃ§Ã£o Ã© obrigatÃ³ria na linguagem Python");
  popup("Por responder este questionÃ¡rio vocÃª recebeu:");
  popup("+5 de Experiencia");
  popup("+5 de Sabedoria");
  changePointVisibility("Verdadeiro",1);
  changePointVisibility("Falso",1);
}
if ( selectedChoice.name == "Falso") {
  popup("VocÃª errou! Leia novamente o ensinamento e volte para refazer o teste!");
  changePointVisibility("Verdadeiro",1);
  changePointVisibility("Falso",1);
}
if ( selectedChoice.name == "Array") {
  popup("VocÃª acertou! Array nÃ£o Ã© um tipo de dado.");
  popup("Por responder este questionÃ¡rio vocÃª recebeu:");
  popup("+5 de Experiencia");
  popup("+5 de Sabedoria");
  changePointVisibility("Array",1);
  changePointVisibility("String",1);
  changePointVisibility("Int",1);
  changePointVisibility("Boolean",1);
}
if ( selectedChoice.name == "String") {
  popup("VocÃª errou! Leia novamente o ensinamento e volte para refazer o teste!");
  changePointVisibility("Array",1);
  changePointVisibility("String",1);
  changePointVisibility("Int",1);
  changePointVisibility("Boolean",1);
}
if ( selectedChoice.name == "Int") {
  popup("VocÃª errou! Leia novamente o ensinamento e volte para refazer o teste!");
  changePointVisibility("Array",1);
  changePointVisibility("String",1);
  changePointVisibility("Int",1);
  changePointVisibility("Boolean",1);
}
if ( selectedChoice.name == "Boolean") {
  popup("VocÃª errou! Leia novamente o ensinamento e volte para refazer o teste!");
  changePointVisibility("Array",1);
  changePointVisibility("String",1);
  changePointVisibility("Int",1);
  changePointVisibility("Boolean",1);
}
if ( selectedChoice.name == "For") {
  popup("VocÃª acertou! Usamos o for quando sabemos exatamente quantas vezes queremos repetir um bloco de instruÃ§Ã£o");
  popup("Por responder este questionÃ¡rio vocÃª recebeu:");
  popup("+5 de Experiencia");
  popup("+5 de Sabedoria");
  changePointVisibility("If",1);
  changePointVisibility("String",1);
  changePointVisibility("While",1);
  changePointVisibility("For",1);
}
if ( selectedChoice.name == "String") {
  popup("VocÃª errou! Leia novamente o ensinamento e volte para refazer o teste!");
  changePointVisibility("If",1);
  changePointVisibility("String",1);
  changePointVisibility("While",1);
  changePointVisibility("For",1);
}
if ( selectedChoice.name == "If") {
  popup("VocÃª errou! Leia novamente o ensinamento e volte para refazer o teste!");
  changePointVisibility("If",1);
  changePointVisibility("String",1);
  changePointVisibility("While",1);
  changePointVisibility("For",1);
}
if ( selectedChoice.name == "While") {
  popup("VocÃª errou! Leia novamente o ensinamento e volte para refazer o teste!");
  changePointVisibility("If",1);
  changePointVisibility("String",1);
  changePointVisibility("While",1);
  changePointVisibility("For",1);
}
if ( selectedChoice.name == "def minha_funcao():") {
  popup("VocÃª acertou! ");
  popup("Por responder este questionÃ¡rio vocÃª recebeu:");
  popup("+5 de Experiencia");
  popup("+5 de Sabedoria");
  changePointVisibility("def void minha_funcao():",1);
  changePointVisibility("void minha_funcao():",1);
  changePointVisibility("def minha_funcao():",1);
  changePointVisibility("def public void minha_funcao():",1);
}
if ( selectedChoice.name == "def void minha_funcao():") {
  popup("VocÃª errou! Leia novamente o ensinamento e volte para refazer o teste!");
  changePointVisibility("def void minha_funcao():",1);
  changePointVisibility("void minha_funcao():",1);
  changePointVisibility("def minha_funcao():",1);
  changePointVisibility("def public void minha_funcao():",1);
}
if ( selectedChoice.name == "void minha_funcao():") {
  popup("VocÃª errou! Leia novamente o ensinamento e volte para refazer o teste!");
  changePointVisibility("def void minha_funcao():",1);
  changePointVisibility("void minha_funcao():",1);
  changePointVisibility("def minha_funcao():",1);
  changePointVisibility("def public void minha_funcao():",1);
}
if ( selectedChoice.name == "def public void minha_funcao():") {
  popup("VocÃª errou! Leia novamente o ensinamento e volte para refazer o teste!");
  changePointVisibility("def void minha_funcao():",1);
  changePointVisibility("void minha_funcao():",1);
  changePointVisibility("def minha_funcao():",1);
  changePointVisibility("def public void minha_funcao():",1);
}
if ( selectedChoice.name == "Sair") {
  changeLayer("Fase1");
}