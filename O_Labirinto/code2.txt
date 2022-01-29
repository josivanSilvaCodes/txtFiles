if ((SaÃºde) <= 0) {
  playSound("media/sounds/lose2.wav");
  popup("Sua saÃºde acabou, tome mais cuidado e preste atenÃ§Ã£o nos itens coletados.");
  changeLayer("VcMorreu");
  endGame();
} else if ((ForÃ§a) <= 0) {
  playSound("media/sounds/lose2.wav");
  popup("Oh no, vocÃª ficou sem forÃ§as e nÃ£o consegue continuar, irÃ¡ morrer no frio e no escuro.");
  changeLayer("VcMorreu");
  endGame();
} else if ((CansaÃ§o) >= 100) {
  playSound("media/sounds/lose2.wav");
  popup("VocÃª esta muito cansado e nÃ£o consegue continuar, lembre - se de descansar um pouco na biblioteca!!");
  changeLayer("VcMorreu");
  endGame();
}