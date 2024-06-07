//variáveis da bolinha
let xBolinha = 300;
let yBolinha = 200;
let diâmetro = 20;
let raio = diâmetro / 2;

//velocidade da bolinha
let velocidadeXbolinha = 6;
let velocidadeYbolinha = 6;

//variáveis da raquete
let xRaquete = 5;
let yRaquete = 150;
let RaqueteComprimento = 10;
let RaqueteAltura = 90;

//variáveis do oponente
let xRaqueteOponente = 585;
let yRaqueteOponente = 150;
let velocidadeYOponente;

let colidiu = false;

//placar do jogo
let meusPontos = 0;
let pontosDoOponente = 0;

//sons do jogo
let raquetada;
let ponto;
let trilha;

function preload(){
  trilha = loadSound ("trilha.mp3");
  ponto = loadSound ("ponto.mp3");
  raquetada = loadSound ("raquetada.mp3");
}

function setup() {
  createCanvas(600, 400);
  trilha.loop();
}

function draw() {
  background(0);
  mostraBolinha();
  movimentaBolinha();
  verificaColisãoBorda();
  mostraRaquete(xRaquete, yRaquete);
  movimentaMinhaRaquete();
  //verificaColisãoRaquete();
  verificaColisãoRaquete(xRaquete, yRaquete);
  mostraRaquete(xRaqueteOponente, yRaqueteOponente);
  movimentaRaqueteOponente();
  verificaColisãoRaquete(xRaqueteOponente, yRaqueteOponente);
  incluiPlacar();
  marcaPonto();
}

function mostraBolinha(){
  circle (xBolinha, yBolinha, diâmetro);
}
function movimentaBolinha(){
  xBolinha += velocidadeXbolinha
  yBolinha += velocidadeYbolinha
}
function verificaColisãoBorda(){
  if (xBolinha + raio > width ||
     xBolinha - raio < 0){
    velocidadeXbolinha *= -1;
}
  if (yBolinha + raio > height ||
     yBolinha - raio < 0){
    velocidadeYbolinha *= -1;
  }
}

function mostraRaquete(x, y){
   rect(x, y, RaqueteComprimento, RaqueteAltura);
}

function movimentaMinhaRaquete(){
  if (keyIsDown(UP_ARROW)){
    yRaquete -= 10
  }
  if (keyIsDown(DOWN_ARROW)){
    yRaquete += 10
  }
}

function verificaColisãoRaquete(){
  if (xBolinha - raio < xRaquete + RaqueteComprimento && yBolinha - raio < yRaquete + RaqueteAltura && yBolinha + raio > yRaquete){
    velocidadeXbolinha *= -1;
    raquetada.play();
  }
}

function verificaColisãoRaquete(x, y){
  colidiu = collideRectCircle(x, y, RaqueteComprimento, RaqueteAltura, xBolinha, yBolinha, raio);
  if (colidiu){
    velocidadeXbolinha *= -1;
    raquetada.play();
  }
}

function movimentaRaqueteOponente(){
  if (keyIsDown(87)){
    yRaqueteOponente -= 10
  }
  if (keyIsDown(83)){
    yRaqueteOponente += 10
  }
}

function incluiPlacar(){
  stroke (255);
  textAlign (CENTER);
  textSize (16);
  fill (color (107,142,35))
  rect (150, 10, 40, 20);
  fill (255);
  text (meusPontos, 170, 26);
  fill (color (107,142,35))
  rect (450, 10, 40, 20);
  fill (255);
  text (pontosDoOponente, 470, 26);
}

function marcaPonto(){
  if (xBolinha > 590){
    meusPontos += 1;
    ponto.play();
  }
  if (xBolinha < 10){
    pontosDoOponente += 1;
    ponto.play();
  }
}




