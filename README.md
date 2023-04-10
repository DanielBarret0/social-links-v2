
# 🗒️ Sobre o projeto

| 🪧 Vitrine.Dev |  [Minha Vitrine Dev](https://cursos.alura.com.br/vitrinedev/danielbarreto)   |
| -------------  | --- |
| ✨: Nome        | Soacial Links | Modelo baseado na função do linktree.
| 🏷️ Tecnologias | <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"><img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
  | 🎇: Bibliotecas |  [IcoMoon](https://icomoon.io/), [gradient animator](https://www.gradient-animator.com/).
| 🚀: URL         | [Soacial Links](https://social-links-v2.bohr.io)
| :page_with_curl: Licença         | [<img src="https://img.shields.io/badge/LICENSE-MIT-green"/>](https://choosealicense.com/licenses/mit/) 


# 🖼️ Banner do VitrineDev
<div align="center">
<img src="https://github.com/DanielBarret0/social-links-v2/blob/main/assets/img/gif-desktop.gif#vitrinedev">
</div>

# Sobre o projeto
O objetivo dese projeto é ter uma pagina com as minhas principais redes de comunicação para faciliatar contato comigo de diversas formas, seja em rodapés de outros repositorios ou mesmo como link de cartão de visita virtual.


# Minha experiência

Projeto muito simples de ser feito porem extremamente útil!. Usei HTML e CSS isso já é suficiente para fazer funciona essa aplicação.

Utilizei algumas bibliotecas para ter um gradiente animado e outro para ter os ícones das redes sociais. Outra coisa bem legal que usei nesse projeto é animação com CSS para fazer o efeito fadeIn **(Efeito é demonstrado assim que abre o site ou recarrega página)** na entrada do site.

```CSS
@keyframes fadeIn {
    0% {
        opacity: 0;
    }

    100% {
        opacity: 1;
    }
}
```

Utilizei variáveis CSS para definir tempo de cada animação e facilitar manutenção caso eu precise mudar o tempo de animação.

```CSS
:root {
    --preto: #03061b;
    --azul: #1858b3;
    --verde: #03C988;
    --branco: #FFFFFF;

    --fonte: 'Inter', sans-serif;

    --animacao-1: fadeIn 2s;
    --animacao-2: fadeIn 3s;
    --animacao-3: fadeIn 4s;
    --animacao-4: fadeIn 5s;
    --animacao-5: fadeIn 6s;
    --animacao-6: fadeIn 7s;
}
```

Também usei a tag transition para definir o tempo geral da animação em todo a classe container(Bloco de conteudo) assim fazendo o efeito fica mais fluido e suave.

```CSS
transition: 500ms all;
```


## Layout mobile 
![Mobile 1](https://github.com/DanielBarret0/social-links-v2/blob/main/assets/img/gif-mobile.gif)

## Layout Tablet
![tablet 1](https://github.com/DanielBarret0/social-links-v2/blob/main/assets/img/gif-tablet.gif)

## Layout Desktop
![desktop 1](https://github.com/DanielBarret0/social-links-v2/blob/main/assets/img/gif-desktop.gif)

# Autor

José Daniel Aragão Barreto

[LinkedIn](https://www.linkedin.com/in/daniel-barreto-1b763216a/)
