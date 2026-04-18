# TARDES - Animacao 3D da TARDIS

Projeto front-end feito com HTML e CSS puro para recriar uma animacao 3D inspirada na TARDIS (Doctor Who), com rotacao continua, brilho e efeito de desaparecimento no hover.

## Preview

A pagina exibe o texto "Doctor" e "Who" nas laterais e, no centro, uma TARDIS 3D montada com elementos HTML (`span`) e transformacoes CSS 3D.

https://github.com/user-attachments/assets/2d16f1e8-7faa-4953-9934-b4970152350b



## Tecnologias

- HTML5
- CSS3 (transform, perspective, animation, keyframes)

## Estrutura do projeto

```text
|
| index.html
| style.css
└─ imgs/
    ├─ frente.png
    └─ lados.png
```

## Efeitos implementados

- Caixa 3D principal da TARDIS com 6 faces.
- Mini-cubo superior simulando a luz da TARDIS.
- Animacao de giro continuo com leve translacao.
- Efeito de pulsacao nos textos laterais.
- Efeito de fade das faces ao passar o mouse sobre o container.

## Personalizacao rapida

Voce pode ajustar no CSS:

- Tamanho da TARDIS: variaveis `--w`, `--h`, `--d` em `.tardis`.
- Velocidade de rotacao: duracao da animacao `giro`.
- Intensidade de brilho: `box-shadow` das classes `.face` e `.face2`.
- Distancia da camera: propriedade `perspective` em `.box`.


## Autor
Desenvolvido por Gabriel Izidoro para estudos de desenvolvimento web.

