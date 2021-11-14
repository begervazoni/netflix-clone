# netflix-clone
Project made with Html, css, javascript and some Jquery

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style/main.css">
    
    <!--responsivo-->
    <link rel="stylesheet" href="style/responsive.css">


    <!-- owl css-->

    <link rel="stylesheet" href="style/owl/owl.carousel.min.css">
    <link rel="stylesheet" href="style/owl/owl.theme.default.min.css">
    <title>Netflix Clone</title>
</head>
<body>
    <header>
        <div class="container">
            <h2 class="logo">Netflix</h2>
            <nav>
                <a href="#">Inicio</a>
                <a href="#">Séries</a>
                <a href="#">Filmes</a>
                <a href="#">Documentários</a>
            </nav>
        </div>
    </header>

    <main>
        <div class="filme-principal">
            <div class="container">
                <h3 class="titulo">HOUSE OF CARDS</h3>
                <p class="descricao">Um mundo político recheado de ganância, corrupção e luxúria na capital Washington.</p>
            </div>
            <div class="botoes">
                <button role="button" class="botao">                    
                <i class="fas fa-play" aria-hidden="true"></i>
                    ASSISTIR AGORA    
                </button>
                
                <button role="button" class="botao">                    
                <i class="fas fa-info-circle" aria-hidden="true"></i>  
                    MAIS INFORMAÇÕES
                </button>
            </div>
        </div>
    </main>

    <div class="carrosel-filmes">
        <div class="owl-carousel owl-theme">
            <div class="item">
                <img src="img/mini1.jpg"class="box-filme" alt="">
            </div>
            <div class="item">
                <img src="img/mini2.jpg"class="box-filme" alt="">
            </div>
            <div class="item">
                <img src="img/mini3.jpg"class="box-filme" alt="">
            </div>
            <div class="item">
                <img src="img/mini4.jpg"class="box-filme" alt="">
            </div>
            <div class="item">
                <img src="img/mini5.jpg"class="box-filme" alt="">
            </div>
            <div class="item">
                <img src="img/mini6.jpg"class="box-filme" alt="">
            </div>
            <div class="item">
                <img src="img/mini7.jpg"class="box-filme" alt="">
            </div>
            <div class="item">
                <img src="img/mini8.jpg"class="box-filme" alt="">
            </div>    
            <div class="item">
                <img src="img/mini9.jpg"class="box-filme" alt="">
            </div>
            <div class="item">
                <img src="img/mini10.jpg"class="box-filme" alt="">
            </div>


        </div>

    </div>


    <script src="https://kit.fontawesome.com/2c36e9b7b1.js"></script>
    <script src="js/owl/jquery.min.js"></script>
    <script src="js/owl/owl.carousel.min.js"></script>
    <script src="js/owl/setup.js"></script>
</body>
</html>
