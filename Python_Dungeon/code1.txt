if ( selectedChoice.name == "Começar") {
  changeLayer("tela.gif");
  popup(" Você está preso em uma dungeon onde para conseguir escapar você deve passar por diversos desafios sendo\nNecessário entender a linguagem python, todo conteúdo necessário para os desafios é encontrado nos npcs durante sua jornada, Boa Sorte!!!");
  changePointVisibility("1F - A",1);
}
if ( selectedChoice.name == "Creditos") {
  changeLayer("Creditos.gif");
}
if ( selectedChoice.name == "Voltar ao menu") {
  changeLayer("Main");
}
if (( selectedChoice.name == "1F - A") && (Prontos_de_Conhecimento) <= 0) {
  changeLayer("Sala1.png");
  changePointVisibility("Pegar Livro",1);
  changePointVisibility("1F - B",1);
  changePointVisibility("Inicar Desafio do mago",2);
} else if (( selectedChoice.name == "1F - A") && (Prontos_de_Conhecimento) >= 1) {
  changeLayer("Sala1.gif");
}
if ( selectedChoice.name == "1F-A") {
  changeLayer("Sala1.png");
  changePointVisibility("Pegar Livro",1);
  changePointVisibility("1F - B",1);
  changePointVisibility("Inicar Desafio do mago",1);
}
if ( selectedChoice.name == "1F - B") {
  changeLayer("Tesouro1.png");
}
if (( selectedChoice.name == "Salão Principal") && (Prontos_de_Conhecimento) == 1) {
  changeLayer("Sala2.png");
  changePointVisibility("subterrâneo",1);
  changePointVisibility("Caveira",1);
} else if (( selectedChoice.name == "Salão Principal") && (Prontos_de_Conhecimento) <= 0) {
  popup("Para entrar nessa sala é necessário ao menos 1 ponto de conhecimento");
} else if (( selectedChoice.name == "Salão Principal") && (Prontos_de_Conhecimento) >= 2) {
  changeLayer("Sala2.png");
  changePointVisibility("Caveira Suspeita",1);
  changePointVisibility("Caveira",2);
}
if ( selectedChoice.name == "1F") {
  changeLayer("Mapa.gif");
}
if (( selectedChoice.name == "subterrâneo") && (Prontos_de_Conhecimento) <= 1) {
  changeLayer("Sub1.png");
} else if (( selectedChoice.name == "subterrâneo") && (Prontos_de_Conhecimento) >= 2) {
  changeLayer("SubNada.gif");
}
if (( selectedChoice.name == "2F - A2") && (Prontos_de_Conhecimento) <= 1) {
  popup("Você sente uma magia estranha te teletransportando de volta  ao salão principal, necessário 2 pontos de conhecimento para continuar!!!");
  changeLayer("Sala2.png");
} else if (( selectedChoice.name == "2F - A2") && (Prontos_de_Conhecimento) >= 2) {
  changeLayer("WhatsApp Image 2021-10-18 at 12.36.19 (2).jpeg");
  changePointVisibility("Fonte Azul",1);
  changePointVisibility("Fonte Verde",1);
  changePointVisibility("Fonte Vermelha",1);
  changePointVisibility("Subsolo",1);
} else if (( selectedChoice.name == "2F - A2") && (Prontos_de_Conhecimento) >= 2) {
  changeLayer("WhatsApp Image 2021-10-18 at 12.36.19 (2).jpeg");
  changePointVisibility("Fonte Verde",1);
  changePointVisibility("Fonte Azul",1);
  changePointVisibility("Fonte Vermelha",1);
  changePointVisibility("Subsolo",1);
  changePointVisibility("Iniciar Desafio",1);
}
if (( selectedChoice.name == "2F - B") && (Prontos_de_Conhecimento) <= 2) {
  popup("Para entrar nessa sala é necessário ao menos 3 ponto de conhecimento");
} else if (( selectedChoice.name == "2F - B") && (Prontos_de_Conhecimento) >= 3) {
  changeLayer("WhatsApp Image 2021-10-18 at 12.36.19 (1).jpeg");
}
if ( selectedChoice.name == "2F - A") {
  changeLayer("WhatsApp Image 2021-10-19 at 18.36.23 (1).jpeg");
}
if (( selectedChoice.name == "2F - B1") && (Chaves) == 2) {
  changeLayer("WhatsApp Image 2021-10-18 at 12.36.18.jpeg");
  changePointVisibility("Somar múltiplas variáveis ao mesmo tempo",1);
  changePointVisibility("Criar um laço de repetição",1);
  changePointVisibility("Alterar o valor de uma variável",1);
  changePointVisibility("Apagar uma variável",1);
} else if (( selectedChoice.name == "2F - B1") && (Chaves) <= 2) {
  popup("Para entrar nessa sala é necessário ao menos 2 chaves");
} else if (( selectedChoice.name == "2F - B1") && (Chaves) >= 3) {
  changeLayer("Esquerda22.gif");
}
if (( selectedChoice.name == "2F - B2") && (Chaves) == 1) {
  changeLayer("WhatsApp Image 2021-10-18 at 12.36.19.jpeg");
} else if (( selectedChoice.name == "2F - B2") && (Chaves) >= 2) {
  changeLayer("Comida0.gif");
} else if (( selectedChoice.name == "2F - B2") && (Chaves) <= 1) {
  popup("Para entrar nessa sala é necessário ao menos 1 chaves");
}
if ( selectedChoice.name == "2F - A1") {
  changeLayer("WhatsApp Image 2021-10-19 at 18.36.23 (2).jpeg");
}
if (( selectedChoice.name == "Subsolo") && (Chaves) <= 0) {
  changeLayer("Sub3.gif");
} else if (( selectedChoice.name == "Subsolo") && (Chaves) >= 1) {
  changeLayer("Sub2.gif");
}
if (( selectedChoice.name == "2F - A2") && (Chaves) >= 1) {
  changePointVisibility("Fonte Verde",1);
}
if (( selectedChoice.name == "2F - B3") && (Chaves) >= 3) {
  changeLayer("esquerda4.gif");
} else if (( selectedChoice.name == "2F - B3") && (Chaves) <= 3) {
  popup("Para entrar nessa sala é necessário ao menos 3 chaves");
}
if (( selectedChoice.name == "2F - B4") && (Chaves) == 3) {
  changeLayer("Esquerda51esqueleto.gif");
} else if (( selectedChoice.name == "2F - B4") && (Chaves) >= 4) {
  changeLayer("EsquerdaChave");
}
if (( selectedChoice.name == "3F") && (Chaves) >= 4) {
  popup("Você insere as 4 chaves obtidas na porta, após gira-las é possível ouvir o barulho da porta abrindo, de fundo você consegue ver a sombra de uma criatura estranha.");
  changeLayer("Mapa Boss.png");
} else if (( selectedChoice.name == "3F") && (Chaves) <= 4) {
  popup("Código:\n\n if chave < 4:\n     print(''Acesso negado'')\n elif chave >= 4:\n     print(''Acesso Liberado'')\n \n <h2>Acesso Negado.<\h2>");
}

if ( selectedChoice.name == "Sábio da dungeon") {
  popup("Seja bem vindo(a), Aventureiro(a)!\n\n Você também ficou preso aqui?\n\n  Já vou lhe adiantando todos os monstros daqui podem ser derrotados com conhecimento sobre python igual aquele esqueleto ali, como sou generoso posso te dar algumas informações. \n <h3>Vamos la!</h3>\n Python é uma linguagem de programação de alto nível, ou seja, com sintaxe mais simplificada e próxima da linguagem humana, utilizada nas mais diversas aplicações, como desktop, web, servidores e ciência de dados. \n \n O Python foi lançado no início da década de 90 pelo programador e matemático holandês Guido Van Rossum. A linguagem foi projetada para dar ênfase no trabalho do desenvolvedor, facilitando a escrita de um código limpo.");
}
if (( selectedChoice.name == "Dono Do Livro") && (Dinheiro) >= 50) {
  popup("Tudo bem, Agora você pode pegar o livro, mais descontarei os <font color=green>50 de gold.</font>");
  changePointVisibility("Pegar Livro",2);
} else if (( selectedChoice.name == "Dono Do Livro") && (Dinheiro) < 50) {
  popup("O quê? Você deseja ler meu livro para obter pontos de conhecimento? \n\n  Claro, eu posso te emprestar ele para você ler, mais vou querer <font color=green>50 de gold.</font> \n\n Fale comigo novamente quando tiver o dinheiro necessário.");
}
if ( selectedChoice.name == "Pegar Livro") {
  changeLayer("Sala1.gif");
  popup("<font color=green>Ponto de conhecimento +1.</font>\n<font color=red>Dinheiro -50.</font>");
}
if ( selectedChoice.name == "Pegar Dinheiro") {
  changeLayer("Tesouro1_3.gif");
  popup("<font color=green>Dinheiro +50.</font>");
}
if ( selectedChoice.name == "Pegar Vida") {
  changeLayer("Tesouro1_2.gif");
  popup("<font color=green>Vida +12.</font>");
}
if ( selectedChoice.name == "Mago Print") {
  popup("Olá Aventureiro(a) quer aprender sobre o print?\n  Print como o nome já diz, serve para imprimir, escrever algo na tela que sera o resultado do código que criarmos em python. \n\n Para fazer isso, temos que digitar o seguinte código:\n\n   print('ola meu nome é João')\n\n   Esse exemplo acima mostrará o seguinte resultado: \n\n Ola meu nome é João\n\n Ou seja, tudo o que queremos mostrar na tela como resultado, precisamos usar a função print.\n\n Se quiser tentar a sorte em passar em meu desafio fique a vontade, eu preparei uma recompensa para quem conseguir!");
}
if (( selectedChoice.name == "Necromancer porteiro") && (Chaves) >= 4) {
  changeLayer("Sala2.png");
} else if (( selectedChoice.name == "Necromancer porteiro") && (Chaves) < 4) {
  popup("Olá aventureiro(a)\n Você deseja acessar a porta que leva a saída da dungeon?? \n Infelizmente estou tentando a anos.\n\n Tem um código escrito na porta, mas não consigo entender.");
}
if ( selectedChoice.name == "Elfo primitivo") {
  popup("Durante o tempo que estive aqui aprendi um pouco sobre os  tipos primitivos, posso te ensinar se quiser!\n\n Os tipos de dados primitivos são os tipos básicos que devem ser implementados por todas as linguagens de programação, como os números reais, inteiros, booleanos, caracteres e strings.\n\n  int = todos os números inteiros: 1 , 10 , 100\n\n float = números com ponto flutuante: 1.0, 2.5, 6.2\n\n string = para definirmos algo como string temos que fazer assim: 'Nome', 'churrasco',\n\n boolean = boolean guarda somente dois valores: verdadeiro(true) e falso(false)\n");
}
if ( selectedChoice.name == "Caveira Suspeita") {
  popup("Ei Amigo(a)\n Tem uma criatura nesse subsolo que eu preciso derrotar, porem eu sempre saio ferido, o que acha de me ajudar e em troca posso lhe dar um pouco de conhecimento?");
  changePointVisibility("subterrâneo",2);
}
if ( selectedChoice.name == "Aventureiro Perdido") {
  popup("Não me interrompa agora, estou tentando pegar a chave das salas que se encontram a frente, mais parece que sempre vou parar no mesmo lugar.\n");
}
if ( selectedChoice.name == "Mago da Dungeon") {
  popup("Olá aventureiro(a)\n Que fique entre nós , mais descobri que a primeira chave se encontra no caminho da direita, porem para passar é necessário 2 pontos de conhecimento, se não é sempre mandado de volta para cá, e até o momento só consegui 1\n\n Hmmm... Ah sim, para avançar é necessário ter conhecimentos de variáveis também.\n O quê? Você não sabe o que é uma variável? Não se preocupe eu te ajudo, é bem simples.\n\n Em python as sua variáveis são de tipagem dinâmica, isso significa que não é necessário declarar o seu tipo, basta atribuir seu valor, como o exemplo abaixo .\n\n a = 10 \n\n Fale com Elfo Primitivo para saber os tipos de variáveis, e não se esqueça de anotar, isso faz toda a diferença no aprendizado.");
}
if ( selectedChoice.name == "Dono do livro") {
  popup("Já te vendi meu livro, agora tenho o dinheiro para tentar sair dessa dungeon.");
}
if ( selectedChoice.name == "Cavalheiro IF") {
  popup("Ei amigo(a)\n\n Você já ouviu falar de if e elif ?\n O If serve para verificar uma condição e o elif serve para verificar outra condição caso a condição do If seja falsa. \n\n Eu sei, isso parece um pouco confuso, vou mostrar na prática\n\n  Digamos que eu avisto um semáforo.\n\n Prosseguir(verde)\n Atenção(amarelo)\n Parar(vermelho).\n\n Se semáforo esta na cor verde então:\n  Prosseguir;\n\n Agora vamos ver na linguagem python:\n\n  semáforo = Verde \n\n   if semáforo == Verde:\n  print(''Prosseguir'')\n elif semáforo == Amarelo:\n print(''Atenção'')\n elif semáforo == Vermelho:\n print(''Parar'')\n\n Saida: <h3>Prosseguir</h3>\n É bem simples não acha ?\n ");
}
if ( selectedChoice.name == "Cavalheiro Else") {
  popup("Meu irmão deve ter te falado sobre if e elif, meu irmão sempre foi muito regrado, mas eu já sou mais liberal.\n\n Vou te explicar como o else funciona.\n\n if e elif são condições mais específicas, ja o else não é necessário especificar uma regra para ser executado.\n Vou te mostrar um exemplo para entender melhor.\n\n Se sua idade for maior ou igual a 18 anos, você é maior de idade, se não é menor de idade.\n\n Agora vamos ver como fica em python.\n\n idade = 15\n\n if idade >= 18 :\n     print(Você é maior de idade)\n else:\n     print(Você é menor de idade)\n\n Saida:  <h3>Você é menor de idade</h3>\n  Qualquer outro número que seja menor que 18, ira cair na condição de menor de idade.\n Isso é muito útil em seus códigos, pode apostar.");
}
if ( selectedChoice.name == "Pegar Chave 1") {
  changeLayer("Sub2.gif");
  popup("<font color=green>Chave +1.</font>");
}
if ( selectedChoice.name == "Zumbi Operadores") {
  popup("Olá Aventureiro(a) Python também usa operadores aritméticos,  Abaixo esta é a lista dos operadores aritméticos que podem ser usados na linguagem python com seus respectivos sinais:\n\n  somar '+' EX: 5+2 = 7\n subtrair '-' EX: 5-2 = 3\n multiplicar '*' EX: 5*2 = 10\n dividir '/' EX: 5/2 = 2.5\n potencia '**' EX: 5**2 = 25\n divisão inteira '//' EX: 5//2 = 2\n resto da divisão '%' EX: 5%2 =  1\n");
}
if ( selectedChoice.name == "Lagarto For") {
  popup("Ei, você já ouviu falar de estrutura de repetição?\n\n A estrutura de repetição for permite executar um bloco de códigos repetidas vezes até que uma condição seja verdadeira.\n Na linguagem Python, ela é utilizada para percorrer elementos em sequência, como uma string ,Por exemplo.\n\n Fale com meu irmão para ver alguns exemplos\n\n  ");
}
if ( selectedChoice.name == "Pratica For") {
  popup("em python a estrutura é montada da seguinte forma:\n  for i in range(1,10):\n 	print('passo')\n 	print('chegou em casa')\n\n  esse i é somente uma variavel que recebe os valores da repetição que nesse caso é de 1 a 10, exemplo:\n na primeira execução dessa estrutura a variavel i ira receber o valor 1 por exemplo;\n o range é o intervalo ou seja, de 1 a 10;\n enquanto nao chegar no 10, a estrutura sera executada sempre dando print em passo, quando a estrutura chegar no intervalo 10, o comando a ser executado sera o print( chegou em casa) e a variavel i ira parar de receber os valores ja que a contagem é ate 10;  \n");
}
if ( selectedChoice.name == "Orc Comparação") {
  popup("Os operadores de comparação são operadores que possuem o objetivo de analisar os valores de uma expressão e retornar um valor booleano, ou seja,\n verdadeiro (1) ou falso (0). Os numeros 0 e 1 é como se fosse ligado e desligado, ou seja, se uma lampada esta ligada, logo receberá o valor 1 de verdadeiro, se estiver apagada receberá o valor 0 de falso.\n\n menor '<'\n maior '>'\n maior ou igual '>='\n menor ou igual '<='\n igual '=='\n diferente '!='\n");
}
if ( selectedChoice.name == "Pegar conhecimento") {
  changeLayer("SubNada.gif");
}
if ( selectedChoice.name == "Pegar Chave 2") {
  changeLayer("5.gif");
  popup("<font color=green>Chave +1.</font>");
}
if ( selectedChoice.name == "Pegar Vida 1") {
  popup("<font color=green>Vida +12.</font>");
  changeLayer("Comida1.gif");
}
if ( selectedChoice.name == "Pegar Vida 2") {
  popup("<font color=green>Vida +12.</font>");
  changeLayer("Comida0.gif");
}
if ( selectedChoice.name == "Pegar chave 3") {
  changeLayer("Esquerda22.gif");
  popup("<font color=green>Chave +1.</font>");
}
if ( selectedChoice.name == "Pegar Chave 4") {
  changeLayer("EsquerdaChave");
  popup("<font color=green>Chave +1.</font>\n\n Agora que você possui todas as chaves bastar ir ao salão principal derrotar o chefão!.");
}
if ( selectedChoice.name == "Caveira") {
  popup("Obrigado amigo!");
}

if ( selectedChoice.name == "Esqueleto Desafio 1") {
  popup("Para passar você terá que responder meu desafio!!!");
  changeLayer("Desafio 1.gif");
}
if ( selectedChoice.name == "90") {
  changeLayer("Mapa.gif");
  popup("Você consegue roubar o machado do esqueleto e o acerta com um golpe fatal.\n<font color=green>Machado adquirido.</font>");
} else if ( selectedChoice.name == "80") {
  popup("Você foi atingido pelo esqueleto.\nMantenha a calme e lembe-se do que fio aprendido ate agora.\n<font color=red>Vida -12</font> ");
} else if ( selectedChoice.name == "70") {
  popup("Você foi atingido pelo esqueleto.\nMantenha a calme e lembe-se do que fio aprendido ate agora.\n<font color=red>Vida -12</font> ");
} else if ( selectedChoice.name == "60") {
  popup("Você foi atingido pelo esqueleto.\nMantenha a calme e lembe-se do que fio aprendido ate agora.\n<font color=red>Vida -12</font> ");
}

if ( selectedChoice.name == "Ler desafio") {
  popup("Você consegue ler algo fogo\n\n ''Para que serve o for na linguagem python''\n \n Em cada porta existe uma escritura em sua madeira.");
  changePointVisibility("Somar múltiplas variáveis ao mesmo tempo",2);
  changePointVisibility("Criar um laço de repetição",2);
  changePointVisibility("Alterar o valor de uma variável",2);
  changePointVisibility("Apagar uma variável",2);
}
if ( selectedChoice.name == "Criar um laço de repetição") {
  changeLayer("22Chave.gif");
  popup("Você coloca sua mão na porta.\nA porta brilha com uma magia e sua tranca é liberada.");
} else if ( selectedChoice.name == "Somar múltiplas variáveis ao mesmo tempo") {
  popup("Você coloca sua mão na porta.\nUma magia estranha te empurra com força para trás.\n<font color=red>Vida -12</font> ");
} else if ( selectedChoice.name == "Alterar o valor de uma variável") {
  popup("Você coloca sua mão na porta.\nUma magia estranha te empurra com força para trás.\n<font color=red>Vida -12</font> ");
} else if ( selectedChoice.name == "Apagar uma variável") {
  popup("Você coloca sua mão na porta.\nUma magia estranha te empurra com força para trás.\n<font color=red>Vida -12</font> ");
}

if ( selectedChoice.name == "Inicar Desafio do mago") {
  changeLayer("Desafio Mago.gif");
}
if ( selectedChoice.name == "Imprimir/Escrever mensagem na tela") {
  changeLayer("Sala1.png");
  changePointVisibility("1F - B",2);
  changePointVisibility("Inicar Desafio do mago",1);
  popup("Você coloca sua mão na porta.\nA porta brilha com uma magia e sua tranca é liberada.");
} else if ( selectedChoice.name == "Somar dois números") {
  popup("Você coloca sua mão na porta.\nUma magia estranha te empurra com força para trás.\n<font color=red>Vida -12</font> ");
} else if ( selectedChoice.name == "Comentar uma mensagem") {
  popup("Você coloca sua mão na porta.\nUma magia estranha te empurra com força para trás.\n<font color=red>Vida -12</font> ");
} else if ( selectedChoice.name == "Cria um laço de repetição") {
  popup("Você coloca sua mão na porta.\nUma magia estranha te empurra com força para trás.\n<font color=red>Vida -12</font> ");
}

if ( selectedChoice.name == "Esqueleto desafio 4") {
  changeLayer("Desafio 4.gif");
  popup("O quê?\n Você quer passar pela minha porta??\n Você não vai conseguir pegar a chave sem passar por mim.\n Me enfrente se tiver coragem.");
}
if ( selectedChoice.name == "Verdadeiro") {
  changeLayer("Esquerda51.gif");
  popup("Você se esquiva do ataque do esqueleto e o acerta com toda a sua força.\n O esqueleto parece ter sido derrotado.");
} else if ( selectedChoice.name == "Falso") {
  popup("Você foi atingido pelo esqueleto.\nMantenha a calme e lembe-se do que fio aprendido ate agora.\n<font color=red>Vida -12</font> ");
}

if ( selectedChoice.name == "Esqueleto Desafio 2") {
  changeLayer("Desafio 2.gif");
  popup("O que você esta fazendo aqui?\nAquele fantasma deve ter te enviado, você não vai desvendar os segredos dessa dungeon.\n<font color=red>Agora não tem escapatória, vai ter que me enfrentar.</font>");
}
if ( selectedChoice.name == "Guardar valores verdadeiro e falso") {
  changeLayer("SubLivro.gif");
  popup("Você se esquiva do ataque do esqueleto e o acerta com toda a sua força.\n O esqueleto parece ter derrubado algo.");
} else if ( selectedChoice.name == "Guardar valores do tipo inteiro") {
  popup("Você foi atingido pelo esqueleto.\nMantenha a calme e lembe-se do que fio aprendido ate agora.\n<font color=red>Vida -12</font> ");
} else if ( selectedChoice.name == "Guardar valores com ponto flutuante") {
  popup("Você foi atingido pelo esqueleto.\nMantenha a calme e lembe-se do que fio aprendido ate agora.\n<font color=red>Vida -12</font> ");
} else if ( selectedChoice.name == "Guardar variáveis do tipo texto") {
  popup("Você foi atingido pelo esqueleto.\nMantenha a calme e lembe-se do que fio aprendido ate agora.\n<font color=red>Vida -12</font> ");
}

if ( selectedChoice.name == "Escapar da dungeon") {
  changeLayer("Creditos.gif");
  popup("Você finalmente consegue ver a luz do lado de fora da dungeon, parabéns você masterizou o básico sobre python e escapou da dungeon!!!");
}

if ( selectedChoice.name == "Iniciar Desafio") {
  popup("Caso o seguinte código seja executado, qual será o resultado obtido?? \n\ncor = 1\n\n  if cor == 1:\nprint(Vermelho)\n elif cor == 2:\nprint(Azul)\n else:\nprint(Verde)\n");
  changePointVisibility("Fonte Verde",2);
  changePointVisibility("Fonte Vermelha",2);
  changePointVisibility("Fonte Azul",2);
}
if ( selectedChoice.name == "Fonte Vermelha") {
  changePointVisibility("Subsolo",2);
  changePointVisibility("Fonte Azul",1);
  changePointVisibility("Fonte Verde",1);
  changePointVisibility("Fonte Vermelha",1);
  changePointVisibility("Iniciar Desafio",1);
  popup("Você coloca sua mão na fonte vermelha.\nNo fundo, tem uma alavanca e você a puxa.\nUma tranca é liberada e uma escada aparece.\nMais ao fundo da fonte você encontra uma pedra magica.\n<font color=green>Conhecimento +1.</font>");
} else if ( selectedChoice.name == "Fonte Azul") {
  popup("Você coloca sua mão na fonte azul.\nNo fundo, tem uma alavanca e você a puxa.\nUma armadilha é ativada e machuca sua mão.\n<font color=red>Vida -12</font>");
} else if ( selectedChoice.name == "Fonte Verde") {
  popup("Você coloca sua mão na fonte verde.\nNo fundo, tem uma alavanca  e você a puxa.\nUma armadilha é ativada e machuca sua mão.\n<font color=red>Vida -12</font>");
}

if ( selectedChoice.name == "Esqueleto desafio 3 - 1") {
  changeLayer("Desafio 3-1.gif");
  popup("O quê?\n Como você chegou aqui?\n Agora isso não importa mais, você não vai conseguir pegar a chave sem passar por mim.\n Me enfrente se tiver coragem.");
}
if ( selectedChoice.name == "**") {
  changeLayer("Esquerda5.gif");
  popup("Esqueleto tenta te acertar com o machado, mas você se defende.\n Em seguida você tenta acertá-lo, mas ele se esquiva e foge.\n \n \n Esqueleto:\n Parece que você apendeu alguns comandos, mas vamos ver como vai se sair quando nos encontrarmos de novo.\n");
} else if ( selectedChoice.name == "//") {
  popup("Você foi atingido pelo esqueleto.\nMantenha a calme e lembe-se do que fio aprendido ate agora.\n<font color=red>Vida -12</font> ");
} else if ( selectedChoice.name == "&&") {
  popup("Você foi atingido pelo esqueleto.\nMantenha a calme e lembe-se do que fio aprendido ate agora.\n<font color=red>Vida -12</font> ");
} else if ( selectedChoice.name == "^^") {
  popup("Você foi atingido pelo esqueleto.\nMantenha a calme e lembe-se do que fio aprendido ate agora.\n<font color=red>Vida -12</font> ");
}

if ( selectedChoice.name == "Esqueleto desafio 3 - 2") {
  changeLayer("Desafio 3-2.gif");
  popup("Você teve coragem de vir atrás de mim.\n Vamos ver como se sai dessa vez.\n");
}
if ( selectedChoice.name == "25") {
  changeLayer("Esquerda6.gif");
  changePointVisibility("Pegar chave 2",1);
  popup("Esqueleto tenta te acertar com uma magia, mas você se esquiva por pouco.\n Quando se levanta o esqueleto foge de medo.\n \n \n Esqueleto:\n Agora chega, na próxima vez que nos encontrarmos sera a última.\n Venha preparado.\n");
} else if ( selectedChoice.name == "30") {
  popup("Você foi atingido pelo esqueleto.\nMantenha a calme e lembe-se do que fio aprendido ate agora.\n<font color=red>Vida -12</font> ");
} else if ( selectedChoice.name == "15") {
  popup("Você foi atingido pelo esqueleto.\nMantenha a calme e lembe-se do que fio aprendido ate agora.\n<font color=red>Vida -12</font> ");
} else if ( selectedChoice.name == "35") {
  popup("Você foi atingido pelo esqueleto.\nMantenha a calme e lembe-se do que fio aprendido ate agora.\n<font color=red>Vida -12</font> ");
}

if ( selectedChoice.name == "Esqueleto desafio 3 - 3") {
  changeLayer("Desafio 3-3.gif");
  popup("Esta é a última vez que nos enfrentamos.\n Espero que esteja preparado para o seu fim.\n");
}
if ( selectedChoice.name == "1") {
  changeLayer("4.gif");
  changePointVisibility("Pegar chave 2",2);
  popup("Antes que o esqueleto possa fazer qualquer movimento, você pula em direção a ele e o acerta com uma machadada com toda a sua força.");
} else if ( selectedChoice.name == "3") {
  popup("Você foi atingido pelo esqueleto.\nMantenha a calme e lembe-se do que fio aprendido ate agora.\n<font color=red>Vida -12</font> ");
} else if ( selectedChoice.name == "5") {
  popup("Você foi atingido pelo esqueleto.\nMantenha a calme e lembe-se do que fio aprendido ate agora.\n<font color=red>Vida -12</font> ");
} else if ( selectedChoice.name == "2") {
  popup("Você foi atingido pelo esqueleto.\nMantenha a calme e lembe-se do que fio aprendido ate agora.\n<font color=red>Vida -12</font> ");
}

if ( selectedChoice.name == "Chefe Cogumelo") {
  changeLayer("Boss 1-1.gif");
  popup("Você acha que pode me derrotar e escapar da dungeon? tente se for capaz, você ficara preso para sempre !!!");
}
if ( selectedChoice.name == "Variável Flutuante") {
  changeLayer("Boss 1-2.gif");
  popup("Antes que o boss possa fazer qualquer movimento, você pula em direção a ele e o acerta com uma machadada com toda a sua força, Você sente que a movimentação dele está mais fraca.");
} else if ( selectedChoice.name == "Variavel Boolean") {
  popup("Você foi atingido pelo boss.\nMantenha a calme e lembe-se do que fio aprendido ate agora.\n<font color=red>Vida -12</font> ");
} else if ( selectedChoice.name == "Variável Inteira") {
  popup("Você foi atingido pelo boss.\nMantenha a calme e lembe-se do que fio aprendido ate agora.\n<font color=red>Vida -12</font> ");
} else if ( selectedChoice.name == "Variável Double") {
  popup("Você foi atingido pelo boss.\nMantenha a calme e lembe-se do que fio aprendido ate agora.\n<font color=red>Vida -12</font> ");
}

if ( selectedChoice.name == "Menor") {
  changeLayer("Boss 1-3.gif");
  popup("Antes que o boss possa fazer qualquer movimento, você pula em direção a ele e o acerta com uma machadada com toda a sua força, Você sente que a movimentação dele está mais fraca.");
} else if ( selectedChoice.name == "Maior") {
  popup("Você foi atingido pelo boss.\nMantenha a calme e lembe-se do que fio aprendido ate agora.\n<font color=red>Vida -12</font> ");
} else if ( selectedChoice.name == "Nenhuma das alternativas") {
  popup("Você foi atingido pelo boss.\nMantenha a calme e lembe-se do que fio aprendido ate agora.\n<font color=red>Vida -12</font> ");
}

if ( selectedChoice.name == "10") {
  changeLayer("Boss 1-4.gif");
  popup("Antes que o boss possa fazer qualquer movimento, você pula em direção a ele e o acerta com uma machadada com toda a sua força, Você sente que a movimentação dele está mais fraca.");
} else if ( selectedChoice.name == "7") {
  popup("Você foi atingido pelo boss.\nMantenha a calme e lembe-se do que fio aprendido ate agora.\n<font color=red>Vida -12</font> ");
} else if ( selectedChoice.name == "8") {
  popup("Você foi atingido pelo boss.\nMantenha a calme e lembe-se do que fio aprendido ate agora.\n<font color=red>Vida -12</font> ");
} else if ( selectedChoice.name == "9") {
  popup("Você foi atingido pelo boss.\nMantenha a calme e lembe-se do que fio aprendido ate agora.\n<font color=red>Vida -12</font> ");
}

if ( selectedChoice.name == "Apresentará um erro") {
  changeLayer("Boss 1 - 5.gif");
  popup("Antes que o boss possa fazer qualquer movimento, você pula em direção a ele e o acerta com uma machadada com toda a sua força, Você sente que a movimentação dele está mais fraca.");
} else if ( selectedChoice.name == "Azul") {
  popup("Você foi atingido pelo boss.\nMantenha a calme e lembe-se do que fio aprendido ate agora.\n<font color=red>Vida -12</font> ");
} else if ( selectedChoice.name == "Azul Marinho") {
  popup("Você foi atingido pelo boss.\nMantenha a calme e lembe-se do que fio aprendido ate agora.\n<font color=red>Vida -12</font> ");
} else if ( selectedChoice.name == "Roxo") {
  popup("Você foi atingido pelo boss.\nMantenha a calme e lembe-se do que fio aprendido ate agora.\n<font color=red>Vida -12</font> ");
}

if ( selectedChoice.name == "A mensagem oi 10 vezes") {
  changeLayer("Mapa Boss - saida.png");
  popup("Antes que o boss possa fazer qualquer movimento, você pula em direção a ele e o acerta com uma machadada com toda a sua força, o boss cai no chão derrotado.");
} else if ( selectedChoice.name == "A mensagem oi 9 vezes") {
  popup("Você foi atingido pelo boss.\nMantenha a calme e lembe-se do que fio aprendido ate agora.\n<font color=red>Vida -12</font> ");
} else if ( selectedChoice.name == "A mensagem oi 11 vezes") {
  popup("Você foi atingido pelo boss.\nMantenha a calme e lembe-se do que fio aprendido ate agora.\n<font color=red>Vida -12</font> ");
} else if ( selectedChoice.name == "A mensagem oi 1 vez") {
  popup("Você foi atingido pelo boss.\nMantenha a calme e lembe-se do que fio aprendido ate agora.\n<font color=red>Vida -12</font> ");
}
