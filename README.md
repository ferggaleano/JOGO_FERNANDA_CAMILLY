# Jogo do DinoDrado 

Este projeto é um simulador do jogo do Dinossauro do Google. Neste, o usuário tenta desviar pulando do obstáculo. Se caso não conseguir desviar, o usuário perde. 

*Não é para jogos oficiais*

## Tecnologias utilizadas
1. *HTML*: Permite inserir o conteúdo e estabelecer a estrutura básica de um website. 
2. *CSS*: Separa o conteúdo da representação visual do site. É focado no estilo (toda a estética de um site).
3. *JS*: É uma linguagem de programação de alto nível criada, a príncipio, para ser executada em navegadores e manipular comportamentos de páginas web. 

## Função principal
Aqui será apresentado apenas uma função no site criado. 

### Pular 
Nessa função é configurado para o personagem pular do obstáculo. 

function pular(){
    if(personagem.classList != 'animar'){
        personagem.classList.add('animar')
    }

    setTimeout(function(){
        personagem.classList.remove('animar')
    }, 500)
}

## Como rodar o código
> Basta, baixar o código, abra o arquivo *index.html* no navegador e se divirta jogando!

## Imagem da tela
![Primeira imagem do joguim](/jogo1.jpeg)
![Segunda imagem do joguim](/jogo2.jpeg)

### Referências 
* HTML: [HOMEHOST](https://www.homehost.com.br/blog/tutoriais/o-que-e-html/)
* CSS: [HOSTINGER](https://www.hostinger.com.br/tutoriais/o-que-e-css-guia-basico-de-css)
* JS: [KENZIE](https://kenzie.com.br/blog/javascript/)
* INSPIRAÇÃO DO JOGO: [YOUTUBE](https://www.youtube.com/watch?v=nHjSl0AXo2g)