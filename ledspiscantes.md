##Projeto led piscantes

este projeto foi desenvolvido dentrotikercard,na disciplina de internet das coisas(IOT),para a criação de leds piscantes nas cores pedidas.
CRIA UM CIRCUITO COM 2 LEDS VERDES , 2 LEDS VERMELHOS E 2 LES AZUIS.
- NO PRIMIRO MOMENTO DEVE SER ACESO 1 LED VERDE, 1 VEREMLHO, 1 AZUL.
- NO SEGUNDO MOMENTO DEVE SER ACESO 2 AZUIS E 2 VERDES
- NO TERCEIRO MOMENTO DEV SER ACESO 1 VERDE , 2 VERMELHOS E 1 AZUL.


#componetes usados

- 1 arduino uno
- 6 leds (2 verdes , 2 vermeho , 2 azul)

#montagem do circuito

![ledspiscantes](ledpiscantes.png)

##codigo

// variaveis do led
int ledVerde = 2/
int ledVermelho = 2/
int ledazul = 2/
void setup()
{ // definir leds como saida
  pinMode(ledverde,OUTPUT);
  pinMode(ledvermelho,OUTPUT);
  pinMode(ledazul,OUTPUT);
}
void loop()
{
  // ligar o led vermelho 
  digitalWrite(ledverde,HIGH);//ligar verde
  digitalWrite(ledvermelho,HIGH);//ligar vermelho
  digitalWrite(ledazul,HIGH);//ligar azul
  delay(5000); // espera 5 segundos
  digitalWrite(ledazul,HIGH);//ligar verde
  digitalWrite(ledvermelho,HIGH);//ligar vermelho
  digitalWrite(ledazul,HIGH);//ligar azul
  delay(5000); // espera 5 segundos]
  digitalWrite(ledVerde,HIGH);//ligar 1 led verdde
  digitalWrite(ledVermelho,HIGH);//ligar 2 vermelhos
  digitalWrite(ledAzul,HIGH);//ligar 1 azul
  delay(5000);


  
