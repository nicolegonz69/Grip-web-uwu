# Grip-web-uwu
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="cuadricula.css">
</head>
<body>
    <header>
        <div id="titulo">
            <h1 class="titule">My Little Pony</h1>
        </div>
        <table>
            <thead>
                <tr id="tumama">
                    <td class="mdr">Twighlight</td>
                    <td class="mdr">Pinky Pie</td>
                    <td class="mdr">Rarity</td>
                    <td class="mdr">AppleJack</td>
                    <td class="mdr">RainbowDash</td>
                    <td class="mdr">FlutterShy</td>
                </tr>
            </thead>
        </table>
    </header>
    <main>
        <section class="contenedor">
            <div id="head"> <p>principal</p></div>
            <div id="second">secundario</div>
            <div id="third"><p>extra</p></div>
            <div id="fourt"><p>extra </p></div>
        
        </section>
    </main>
</body>
</html>


LUEGO CSS

#titulo{
    display:flex;
    align-items: center;
    text-align: center;
    justify-content: center;
    background-color: pink;
    margin-right: auto;
    margin-left: auto;
    height: 150px;
    width: auto;
    
}
h1{
    display:flex;
    align-items: center;
    text-align: center;
    justify-content: center;
    color: white;
    font-size: xx-large;
    font-family: Georgia, 'Times New Roman', Times, serif;
}
tr{
    display:inline-block
    border-radius: 10%;
    margin-left: auto;
    margin-right: auto;
    align-items: center;
    justify-content:center;
    width: 1fr;
    height: 35px;
    margin: 15px;
    padding: 10px;

    background-color:#f8edeb;
}
td{
    text-align: center;
    width: auto;
    color: #faa2aa;
    font-size: larger;
    font-family: Georgia, 'Times New Roman', Times, serif;
}
.contenedor{
    margin: 5px;
    margin-top: 15px;
    border:10px;
    width:100%;
    height:800px;
    padding:20px;

    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-template-rows: 2fr 1fr 1fr;
    gap: 10px;

}
.contenedor>#head{
    background-color: #FADEE7;

    grid-column:1/3;
    grid-row: 1/2;

   

}
.contenedor>#second{

    background-color: #F8DDD4;
    grid-column: 1/2;
    grid-row:2/4;
}
.contenedor>#third{
    background-color: #F5C5C8;
    
    grid-column: 2/3;
    grid-row: 2/3;
}
.contenedor>#fourt{
    background-color: #F4CCCD;

    grid-column:2/3;
    grid-row: 3/4;
}ç

p{
    color:azure;
    font-size: xx-large;
    font-family: Georgia, 'Times New Roman', Times, serif;
    align-items: center;
    text-align: left;
}
