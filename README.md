# Recursos para densenvolvimento da urna eletrônica do canal WDEV

Repositório complementar do canal [WDEV](https://youtube.com/wdevoficial) para desenvolvimento da urna eletrônica.

Nesse repositório você vai encontrar variáveis CSS, estilos globais, JSON com candidatos, arquivos de imagem e áudios necessários para a implementação do frontend.

__________________

## Variáveis CSS e estilos globais

Para facilitar a implementação das cores no projeto, seguem abaixo as variáveis CSS com o esquema de cores do front e reset de CSS:
```css
:root{
  --background-color: #333333;
  --ballot-box-background-color:#dcdde1;
  --ballot-box-keyboard-color:#2f3640;
  --ballot-box-screen-color:#e3eef9;
  --ballot-box-keyboard-button-color:#292e33;
  --ballot-box-white-button-color:#eeeeee;
  --ballot-box-correct-button-color:#ff841f;
  --ballot-box-confirm-button-color:#7daa44;
  --light-border-color:#cccccc;
  --dark-border-color:#444444;
  --light-text-color:#eeeeee;
  --dark-text-color:#333333;
}

html,body{
  margin: 0;
  padding: 0;
  width: 100%;
  height: 100%;
}

*{
  box-sizing: border-box;
  font-family: sans-serif;
}

button{
  border:0;
  cursor: pointer;
}

button:focus{
  outline: none;
}

button:active{
  opacity: 0.6;
}
```

___________________

## Candidatos

Segue abaixo JSON com candidatos para implementar no projeto:
```json
{
  "prefeito":{
    "01":{
      "nome": "Ash",
      "partido": "Pokemon",
      "imagem": "https://raw.githubusercontent.com/william-costa/wdev-urna-eletronica-resources/master/images/ash.png"
    },
    "08":{
      "nome": "Vegeta",
      "partido": "Dragon Ball",
      "imagem": "https://raw.githubusercontent.com/william-costa/wdev-urna-eletronica-resources/master/images/vegeta.png"
    }
  },
  "vereador":{
    "01234":{
      "nome": "Pikachu",
      "partido": "Pokemon",
      "imagem": "https://raw.githubusercontent.com/william-costa/wdev-urna-eletronica-resources/master/images/pikachu.png"
    },
    "08001":{
      "nome": "Goku",
      "partido": "Dragon Ball",
      "imagem": "https://raw.githubusercontent.com/william-costa/wdev-urna-eletronica-resources/master/images/goku.png"
    }
  }
}
```

___________________

## Áudios

Segue abaixo arquivo compactado contendo os dois arquivos de áudio necessários para o projeto.
https://raw.githubusercontent.com/william-costa/wdev-urna-eletronica-resources/master/audios/audios.zip
___________________

## Canal no YouTube
<img height="60" style="margin-bottom:10px;" src="https://raw.githubusercontent.com/william-costa/william-costa/master/assets/images/logo-wdev.png">

Canal de tecnologia com conteúdos sobre programação e super dicas para a galera que está começando no mundo dev.

Toda **quinta** às **20h** tem vídeo novo, então inscreva-se para não perder nenhuma novidade:

<a href="https://youtube.com/wdevoficial"><img height="30" src="https://raw.githubusercontent.com/william-costa/william-costa/master/assets/images/subscribe-youtube.png"></a>