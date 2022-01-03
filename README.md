# Portfolio 


[voir portfolio](https://github.com/MDG-92/Portfolio.git "Voir le portfolio")

'''html
    <!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="css/style.css" rel="stylesheet" type="text/css">
    <title>Mandengue Njime</title>

    <link rel="icon" href="asset/iconconde.ico">
</head>

       

<body>
    <header>
        <h1>    
            <span>&#128110;&#127999;</span>
            MarDGelaa's Portfolio
        </h1>
    </header>
    <nav>
        <ul>
            <li><a href="#Compétences">Compétences</a></li>
            <li><a href="#Logiciels">Logiciels</a></li>
            <li><a href="#Expériences">Expériences</a></li>
            <li><a href="#Etudes">Etudes</a></li>
            <li><a href="#Loisirs">Loisirs</a></li>
        </ul>
    </nav>  



        <main>

            <section id = "Compétences">
                    <h2>Compétences </h2>
                    <p>Je possede des connaissance en programmation.<br>
                    Je connais le language java, css, javascript, html, python, C, php.<br>
                    Mais je pense me specialiser dans le reseau donc il est important que je sache bien maitriser cisco packet tracer.
                    </p>

            </section>

            <section id = "Logiciels">
                <h2>Logiciels</h2>
                    <div class="photo">
                        <img src="asset/adobe-logo.png" alt="image">
                        <img src="asset/Virtualbox_logo.png" alt="image">
                        <img src="asset/html5-logo-1-512x500.png" alt="image">
                    </div>  
            </section>

            <section id = "Expériences">
                    <h2>Expériences </h2>
                    <p><time datetime="2003-01-01">2003</time> :  Avec mon frère
                    nous avons monté une société de production de films cinématographiques et vidéos
                    en février 2020.<br>
                     Cette dernière m'a procuré un sens pour l'organisation et m'a obligé a
                    me discipliner.
                    </p>   
            </section>

            <section id = "Etudes">
                <h2>Etudes</h2>
                <p><time datetime="2000-01-01">2019</time> : BAC STMG.</p>
                <p><time datetime="2021-07-01">2021</time> : BTS : établissement supérieur </p>
            </section>

            <section id = "Loisirs">
                <h2> Loisirs </h2>
                <ol type="I"><!--liste activité-->
                    <li>Voyage</li> <!--display list-item-->  
                    <li>Cinéma</li>
                    <li>L'informatique</li>
                </ol>
            </section>
        </main>
        <!--footer-->
    <footer>
        <details>
            <summary>Info</summary>
            <p>&copy;Mandengue Njime Akwa Portfolio - 2021</p>
        </details>
    </footer>
</body>
</html>
'''

'''css
    html{
    font-size: 62.5% ;
    scroll-behavior: smooth;
    background-image: url(https://voyage-onirique.com/wp-content/uploads/2019/05/WallpaperStudio10-119390-landscape.jpg);
}

img {
	width: 100px;
	height: 100px;
    vertical-align:middle;
}

body{
    font: 1.6rem arial;
    margin: 0rem;
}


ol, ul, li{
    font-style: normal;
    color: rgb(255, 255, 255);
    text-align: center;
}

h2{
    color: rgb(255, 255, 255);
    margin: 30px;
    padding: 6px;
    list-style: none;
    text-align: center;
    background-color: rgb(0, 0, 0);
    color: rgb(255, 255, 255);
    border-bottom: 2px solid rgb(255, 255, 255);
}

p{
    color: rgb(255, 255, 255);
    margin: 30px;

    
}
/* theme */
header, h1{
    background-color: rgb(0, 0, 0);
    line-height: 6.5rem;
    font-weight: normal;
    color: rgb(255, 255, 255);

}

main{
    max-width: 130.0rem;
    margin: 5.0rem auto;
    overflow: hidden;
    background-color: rgba(48, 45, 47, 0.719);
}
main ul li img{
    display: block;
}

main ul{
    padding: 1.0rem;
}

.photo{
    text-align: center;
}

footer{
    text-align: center;
}
  
/*Reset CSS*/
*{
    margin: 0px;
    padding: 0px;
}

nav, ul{
    list-style-type: none;
}

nav, li {
    float: left;
}

nav ul ::after{
    content: "";
    display: table;
    clear: both;
}

nav li{
    float: left;
    width: 20%;
    text-align: center;
}

nav{
    width: 100%;
    margin: 0 auto;
}
nav a{
     display: block;
     text-decoration: none;
     color: rgb(0, 0, 0);
}

nav a :hover{
    color: rgb(255, 255, 255);
    border-bottom: 2px solid rgb(102, 255, 0);
}

nav a{
    display: block;
    text-decoration: none;
    color: rgb(255, 0, 0);
    border-bottom: 2px solid transparent;
}

nav a{
    display: block;
    text-decoration: none;
    color: rgb(0, 0, 0);
    border-bottom: 2px solid transparent;
    padding: 10px 0px;
}

nav a{
    color: rgb(255, 255, 255);
    border-bottom: 2px solid rgb(255, 255, 255);
}

nav{
    width: 100%;
    margin: 0 auto;
    background-color: rgb(0, 0, 0);
    position: sticky;
    top: 0px;
}

/*##############################################################*/
#cadre {
    border-radius: 10px;
  }


'''
