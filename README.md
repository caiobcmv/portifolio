<header>
    <div class="interface">
     <div class="logo">
     <a href="#"></a>
     <img src="images/portifolio_caio_resized.png" alt="logo">
     </a>
     </div> 
     <nav calss="menu-desktop">
        <ul>
            <li><a href="#">inicio</a></li>
            <li><a href="#">especialidades</a></li>
            <li><a href="#">sobre</a></li>
            <li><a href="#">projetos</a></li>
        </ul>
     </nav>
     <div class="caio-contatos">
        <a href="#">
            <button>contatos</button>
        </a>
     </div>
</header>

CSS
/* o estilo geral */
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    
}


body{
    background-color: #000;
    height:100vh;
    font-family: 'Roboto', sans-serif;
}

.interface{
     max-width: 1280px;
     margin: 0 auto;
    
}

/*estilo do cabercalho*/
header{
    padding: 40px 4%;
    
}

header>.interface{
    display: flex;
    align-items: center;
    justify-content:space-between;
}
header a{
    color: #5c5c5c;
    text-decoration: none;
    display: inline-block;
    transition: .2s;
}
header a:hover{
    color: #fff;
    transform: scale(1.05);
}
header nav ul{
list-style-type: none;

}
header nav ul li {
    display: inline-block;
    padding: 0 40px;
}

header .caio-contatos button{
    padding:10px 40px;
    font-size:18px;
    font-weight:600;
    background-color:#fff;
    border:0;
    border-radius: 30px;
    cursor: pointer;

}
header .caio-contatos button:hover{
    box-shadow:0px 0px 8px #bc5a5a;
}
