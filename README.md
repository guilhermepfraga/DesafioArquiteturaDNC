# DesafioArquiteturaDNC
Entrega Desafio 1

---------------------------------------------------------------------------------------------------------------------------

Link Planilha Sheet Monkey: 
https://docs.google.com/spreadsheets/d/1VZBPI5mxJvfa4muzcw_Yx0ZeQH2wWm4o8PypEv_Rl8U/edit#gid=0

---------------------------------------------------------------------------------------------------------------------------

Código do Index.html

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@100;200;300;400;500;600;700;800;900&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
    <title>Desafio 1 DNC</title>
</head>
<body>

<!--MENU SUPERIOR-->
<div id="menusuperior">
    <h1 id="titulo-menusuperior">Tradição em projetos de arquitetura</h1>
    <p id="texto-menusuperior">Arquitetura residencial e comercial. </p>
</div>

<!--MENU INFORMACIONAL-->
<div id="menuinformacional">
    <div id="menuinformativo1">
        <p class="textoinformativo">850</p>
        <p class="textoinformativo2">empreendimentos construídos</p>
    </div>
    <div id="menuinformativo2">
        <p class="textoinformativo">40</p>
        <p class="textoinformativo2">anos de mercado e experiência</p>
    </div>    
    <div id="menuinformativo3">
        <p class="textoinformativo">2,000,000</p>
        <p class="textoinformativo2">m² em projetos construídos</p>
    </div>
</div>

<!--MENU HISTÓRIA E EXPERIÊNCIA-->
<div id="menuhistoria">
    <div id="textoshistoria">
        <h1 id="titulohistoria">Arquitetos com História e Experiência.</h1>
        <p id="textohistoria">Nós realizamos desde 2002 projetos e gerenciamento de obras. <br>
        Com mais de 800 projetos e 2.000.000 de m² construídos, tendo <br> 
        como principal proposta transformar em realidade os sonhos de <br> 
        seus clientes, criando projetos personalizados, unindo a tradição <br> 
        e a modernidade em nossos projetos.</p>
    </div>
    <div id="imagemhistoria">
        <img src="imagens/foto.svg" alt="ERRO AO CARREGAR IMAGEM">
    </div>
</div>    

<!--FORMULÁRIO-->
<div id="formulario">
    <h1 id="titulo-formulario">Conheça mais sobre nossos serviços:</h1>
    <form action="https://api.sheetmonkey.io/form/2gihsea1se2f5hbrzHrjzC" method="post">
        <input type="text" placeholder="Nome" name="Name" required> <br>
        <input type="email" placeholder="Email" name="Email" required> <br>
        <input type="hidden" name="Created" value="x-sheetmonkey-current-date-time" />
    <button type="submit">Fale Conosco</button>
    </form>
</div>
</body>
</html>

-----------------------------------------------------------------------------------------------------

Código style.css

*{
    margin: 0px;
    font-family: 'inter';
}
#menusuperior{
    background-color: #303030;
    width: 1440px;
    height: 475px;
}
#titulo-menusuperior{
   color: #FFFFFF;
   font-size: 60px;
   padding-top: 206px;
   padding-left: 62px;
}
#texto-menusuperior{
    color: #FFFFFF;
    font-size: 20px;
    padding-top: 20px;
    padding-left: 62px;
}
#menuinformacional{
    background-color: #eaece5;
    width: 1440px;
    height: 229px;
    display: grid;
    grid-auto-flow: column;
    columns: auto;
}
.textoinformativo{
    color: #000000;
    font-weight: bolder;
    display: flex;
    align-items: center;
    font-size: 40px;
    padding-top: 90px;
    line-height: 28px;
}
.textoinformativo2{
    display: flex;
    align-items: center;
    font-size: 20px;
    line-height: 28px;
}
#menuinformativo1{
    padding-left: 120px;
}
#menuhistoria{
    width: 1440px;
    display: grid;
    grid-auto-flow: column;
    columns: auto;
    margin-top: 80px;
}
#textoshistoria{
    padding-top: 200px;
    padding-left: 77px;
}
#titulohistoria{
    font-size: 40px;
}
#textohistoria{
    font-size: 24px;
    padding-top: 40px;
}
#imagemhistoria{
    height: 605px;
    width: 510px;
    border-radius: 30px;
    margin-bottom: 80px;
}
#formulario{
    background-color: #303030;
    width: 1440px;
   text-align: center;
}
#titulo-formulario{
    font-size: 32px;
    padding-top: 80px;
    color: #FFFFFF;
}

input{
    width: 508px;
    height: 72px;  
    background-color: #eaece5;
    border: 0px;
    border-radius: 10px;
    padding-left: 20px;
    margin-top: 60px;
    font-size: 24px;
    font-family: 'Raleway';
    font-weight: bolder;
    color: #0000004D;

  }
  
  button{
      background-color:#c07212;
      width: 286px;
      height: 74px; 
      color: #FFFFFF;
      border: 0px;
      border-radius: 10px;
      margin-bottom: 80px;
      font-weight: bolder;
      margin-top: 80px;
      cursor: pointer;
      font-family: 'Raleway', sans-serif;
      font-size: 30px;
  }
  
  button:hover{
      background-color: #c07212;
      color: rgb(235, 221, 193);
      transform: translateY(-7px);
      transition-duration: 0.6s;
      box-shadow: 0px 15px 20px;
  }
