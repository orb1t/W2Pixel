# W2Pixel
JavaScript plugin for pixelated drawings.

Plug-in JavaScript para desenhos pixelizados.

<img src="w2p.png"/>

v2.5.0

![visitors](https://visitor-badge.glitch.me/badge?page_id=samuelllr/W2Pixel)
![GitHub repo size](https://img.shields.io/github/repo-size/samuelllr/W2Pixel?color=red)
![GitHub](https://img.shields.io/github/license/samuelllr/W2Pixel)
![Twitter Follow](https://img.shields.io/twitter/follow/Samuelllr_htcod?style=social)

************

W2Pixel, a plugin developed for pixel drawings in the browser, made in JavaScript, with it you draw, using in your HTML code and running in your browser, so the drawing is formed in pixelated format. W2Pixel, is fast and practical, simple to learn in just 1 day.

W2Pixel, um plugin desenvolvido para desenhos em pixel no navegador, feito em JavaScript, com ele você desenha, utilizando em seu código HTML e executando em seu navegador, assim o desenho é formado no formato pixelado. W2Pixel, é rápido e prático, simples de aprender em apenas 1 dia.

************

************

What's new in the new version 2.5.0?

New code wDiamond ( ); To create pixel lozenges.


O que há de novo na nova versão 2.5.0?

Novo código wDiamond( ); Para criar Losangos em pixel.

-------------------------------------------------------------------------------------------------------------------------------------

What's new in the new version 2.4.0?

Now with the shortcut CTRL+M you generate a BASE64 drawing to use as you like as well as turning your drawing into an image.


O que há de novo na nova versão 2.4.0?

Agora com o atalho CTRL+M você gera uma BASE64 de desenho para usar como quiser assim como transformar seu desenho em uma imagem.

************
************

Static drawing example:
<br><br>
Exemplo de desenho estático:

<img src="ex.png"/>

<code><pre>

    <script>

        w2pixel( 400 , 400 , 19 , 19 , false );

        wDeform( 2 , 2 );

        wFill( "#ff0" );

        wRect( 5 , 5 , 8 , 8 );
        wRect( 3 , 3 , 1 , 3 );
        wRect( 4 , 5 , 1 , 5 );
        wRect( 8 , 4 , 2 , 1 );
        wRect( 13 , 5 , 1 , 3 );
        wRect( 5 , 13 , 3 , 1 );

        wFill( "#f20" );

        wRect( 5 , 10 , 2 , 2 );
        wRect( 10 , 7 , 2 , 2 );
        wRect( 5 , 3 , 1 , 2 );
        wPoint( 6 , 4 );

        wFill( "#783c00" );

        wLinePath([
            6,15,8,15,8,14,10,14,10,13,11,13,
            11,12,12,12,12,11,13,11,13,10,
            14,10,14,8,15,8,15,6
        ]);

        wFill( "#000" );
        wLinePath([
            4,13,4,10,3,9,3,6,2,5,2,2,5,2,6,3,9,3,
            10,4,13,4,14,5,16,5,16,8,15,9,15,10,
            9,15,5,16,5,14,7,14,9,13,13,8,14,6
        ]);
        wPointPath([
            10,6,1,0,1,1,0,1,-1,1,-1,0,-1,-1,0,-1,
            -5,-4,0,1,3,0,-1,1,-1,0,
            0,4,1,0,1,1,0,1,-1,1,-1,0
        ]);


    </script>

</pre></code>

************

site : https://shamky.000webhostapp.com/

Current version : 2.5.0 .
<br>
Versão atual : 2.5.0 .

data/date : 25/02/2020.

