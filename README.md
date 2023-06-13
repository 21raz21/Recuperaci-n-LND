# Recuperacion-LND

Codigos pagina web con contenedores: 
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Examen de REC - LND</title>
    <link rel="stylesheet" href="index.css">
</head>
<body>
    <header>
        <h1>HEADER</h1>
    </header>
    <section>
        <nav>
            <a href="about.html" class="about">ABOUT</a>
            <a href="personal.html" class="personal">PERSONAL</a>
            <a href="#" class="productos">PRODUCTOS</a>
            <a href="#" class="contacto">CONTACTO</a>
        </nav> 
            <div class="contenido">
                <h3>Contenido</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Vero voluptatibus quisquam sapiente ipsum a impedit perspiciatis quibusdam reiciendis! Magnam eius in perspiciatis veniam tempora unde soluta repellat, necessitatibus nemo libero? Lorem ipsum dolor sit amet consectetur adipisicing elit. Facilis culpa deleniti libero nulla expedita obcaecati voluptatem, magni laudantium deserunt ab neque modi vel maiores maxime, asperiores velit voluptas iusto perferendis.</p>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Explicabo autem amet sint nisi aspernatur at architecto quae nemo numquam asperiores quisquam deserunt soluta laudantium ex sunt sapiente animi, inventore neque? Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda eveniet, praesentium officia error amet nam fugit ut, repellendus ad nisi minus ipsam numquam harum distinctio odio dolorem nulla, temporibus saepe?</p>
        <aside>
            <div class="widget">
                <p>WIDGET1</p>
            </div>
                
            <div class="widget">
                <p>WIDGET2</p>
                <img src="mozaico.png">
            </div>
        </aside>
    </section>
    <footer>
        FOOTER
        
    </footer>
</body>
</html>

Codigo Css:

body {

    background-color: rgba(128, 128, 128, 0.281);
    padding: 10px 50px;
}

header {
    font-family: 'Roboto';
    padding: 35px;
    text-align: center;
    color: white;
    background-color: #253a4e;
}

section{
    display: flex;
    background-color: white;
    margin: 5px;
}

.contenido{
    font-family: 'Roboto';
    margin: 5px;
    padding: 15px 20px;
    height: 350px;
}

nav {
    background-color: rgba(245, 185, 136, 0.562);
    display: flex;
    flex-direction: column;
    padding: 60px 50px ;
    height: 450px;
}

a{
    text-decoration: none;
}

nav .about{
    display: flex;
    color: rgb(255, 0, 43);
    border-bottom:5px solid rgba(255, 0, 43, 0.315);
    margin-bottom: 20px;
	padding-bottom:20px;
    margin-top: 25px;
}

nav .personal{
    display: flex;
    color: green;
    border-bottom:5px solid rgba(0, 128, 0, 0.445);
    margin-bottom: 20px;
	padding-bottom:20px;
    margin-top: 30px ;
}

nav .productos{
    display: flex;
    color: rgb(0, 102, 255);
    border-bottom:5px solid rgba(0, 102, 255, 0.39);
    margin-bottom: 20px;
	padding-bottom:20px;
    margin-top: 30px;
}

nav .contacto{
    display: flex;
    color: orange;
    border-bottom:5px solid rgba(255, 166, 0, 0.411);
    margin-bottom: 20px;
	padding-bottom:20px;
    margin-top:30px;
}

a:hover{
   color:azure ;
}
aside {
	display: inline-flex;
	flex-wrap:wrap;
    text-align: center;
}

aside .widget {
	background: #26a8ff;
    padding:50px;
    margin-right: 5px;
}

footer{
    font-family: 'Roboto';
    padding: 35px;
    color: white;
    background-color: #253a4e;
}

.widget img {
    width: 50%;
}
