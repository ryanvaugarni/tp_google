# Cours sur la page principale de Google
## Je vous présente une partie de mon code utilisé pour la réalisation du site
Ce dépôt sert à apprendre à gérer les propriétés html et css pour créer une page web Google

### Exemple de code html :
```html
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Mon Portfolio...">
    <title>Google</title>
    <link rel="apple-touch-icon" sizes="180x180" href="./asset/apple-touch-icon.png">
    <link rel="icon" type="image/png" sizes="32x32" href="./asset/favicon-32x32.png">
    <link rel="icon" type="image/png" sizes="10x10" href="./asset/favicon-10x10.png">
    <link rel="manifest" href="/site.webmanifest">
    <link rel="stylesheet" href="./css/style.css">
</head>
<body>
    <header>
        <div class="right">
          <p>Gmail</p>
          <p>Images</p>
          <img src="./asset/onglet.png">
            
            <button> <a href="https://accounts.google.com/ServiceLogin/identifier?continue=https%3A%2F%2Fwww.google.com%2F&sacu=1&passive=1209600&hl=fr&acui=0&flowName=GlifWebSignIn&flowEntry=ServiceLogin&cid=1&TL=AM3QAYYMaRvY9MGrX-RpGM-k9iut70K1nO1XeN6q7MPqd8b4yN1vKmkEh4my9nUz">Connexion</a></button>
        </div>
      </header>
    <main>
        <section>
            <h2>
            <img  src="./asset/logo.png" alt="google">
            </h2>
             
            <form action="https://www.google.com/search">
                <input type="text" name="q" placeholder="Recherche" aria-required="true">
            </form>
            <div class="buttons">
              <button>Recherche google</button>
              <button>J'ai de la chance</button>
            </div>
            <br>
            <a href="https://www.google.com/setprefs?sig=0_kldkvB3NSB5dmF7LLKtfTMFSfB8%3D&hl=en&source=homepage&sa=X&ved=0ahUKEwj_z666kbbzAhXGPsAKHRSHAtMQ2ZgBCA4">Google disponible en : English</a>
          </section>
    <footer>
        <p>France</p>
        <hr>
        <p>Neutre en carbone depuis 2007</p>
    </footer>
    </main>
</body>
</html>
```
### Partie de mon code CSS

```css
@import url('https://fonts.googleapis.com/css2?family=Arimo&display=swap');
/* reset css */
html{
    font-size: 70%;
    scroll-behavior: smooth;
    /*background: #fff url(https://img.freepik.com/vecteurs-libre/fond-abstrait-blanc_23-2148806276.jpg?size=626&ext=jpg)no-repeat fixed center center / cover;*/
    background-color: #fff;
    }
    body{
        font: 1.6rem 'Arimo', sans-serif;
        margin: 0;
        padding: 0;
        
    }
    h1,h2,h3,h4,h5,h6,p,figure,ul,ol{
        margin: 0;
        padding: 0;
        list-style: none;
    }
    a{
        color: #222;
        text-decoration: none;
    }
    *{
        box-sizing: border-box;
    }
    :root{
        --color-default: #1e201f;
        --color-primary: #2b7dc0;
        --color-warning: #e23131;
        --color-success: #4db32e;
        --color-border: #b3b5b6;
    }
```


