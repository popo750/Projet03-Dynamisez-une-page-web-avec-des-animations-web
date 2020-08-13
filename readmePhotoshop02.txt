Prélèvement de couleurs des maquettes
+ police du texte


Dans l'image planche-1b.png,
    body {
        background-color: #fff;
    }

    header,
    .prochainement,
    footer {
        background-color: #579c87;
        /* Titre : ohmyfood */
        color: #fdcb46;

        /* police du texte - header */
        font-family: Verdana Bold, Arial Black;

        
        /* police du texte - class prochainement */
        font-family: Arial Regular, Corbel Regular;

        /* police du texte - footer */
        font-family: Corbel Bold, Trebuchet MS Bold;
        font-weight: bold;
    }

    div class="box note-enchantee" {

        background-color: #fcdfdb;

        /* icone - couleur degrade */
        color: #ef475f, #f6916a;

        /* titre h2 / paragraphe */
        /* titre h1 menu */
        color: #3c1218;

        /* police du texte - titre h2 */
        /* police du texte - titre h1 menu */
        font-family: Forte Regular (seulement pour h2), Segoe Print (Bold et Regular), segoe Script Regular Comic Sans MS (Bold et italic);
        font-weight: bold;
    }

    div class="box chic-francaise" {

        background-color: #fff5fe;

        /* titre h2 / paragraphe - couleur degrade diagonale */
        color: #d8852e, #905bfd;
        /* ou */
        color: #d17e44, #935cf4;

        /* titre h1 menu */
        color: #c77412;

        /* police du texte - titre h2 - tire h1 menu */
        font-family: Georgia Bold, Garamond Bold, Book Antiqua Bold, Constantia Bold
        font-weight: bold;
    }

    div class="box delice-papilles" {

        background-color: #f9f9f9;

        /* titre h2 / paragraphe - couleur degrade */
        color: #0431df, #197af4;
        /* ou */
        color: #0235e1, #0889fb;

        /* titre h1 menu */
        color: #0887fb;

        /* police du texte - Titre h2 */
        font-family: Segoe Print Regular, Segoe Script Regular, Comic Sans MS
        font-weight: italic;

        /* police du texte - Titre h1 menu */
        font-family: Segoe Print Regular, Segoe Script Regular, Comic Sans MS
    }

    div class="box palette-gout" {

        background-color: #fdfffd;

        /* titre h2 / paragraphe - couleur degrade */
        color: #62b24e, #b3f579;
        /* ou */
        color: #5bab4a, #bafc7d; 
        /* ou */
        color: #43973d, #beff7f;

        /* titre h1 menu */
        color: #72bf56; 

        /* police du texte - Titre h2 */
        font-family: Mistral Regular, Forte Regular, Segoe Print Bold, Segoe Script Bold, Comic Sans MS (bold italic)
        font-weight: bold, italic;

        /* police du texte - Titre h1 menu */
        font-family: Segoe Print Regular, Segoe Script Regular, Comic Sans MS
    }
        

/****************************************************************************/
Dans l'image "planche-2.png" ,
    /* Pour le header et footer,
        color et font-family
        idem que dans l'image "planche-1.png" */

    body {
        color: black;
    }

    /* h3 dans le background-color Blanc */
    h3 {
        font-family: Arial Bold, Verdana Bold, Arial Black;
    }


/****************************************************************************/
Dans l'image "menu-1.png",

    body {
        background-color: #fcdfdb;
        color: black;
    }

    /* icone music - couleur degrade */
    color: #f15f62, #f6916a;

    /* Titre "La note enchantée" */
    font-family: Forte Regular, Segoe Print Bold, Segoe Script Bold, Comic Sans MS italic

    /* Titre des trois submenu */
    font-family: Segoe Print (Regular, Bold), Segoe Script Bold, Comic Sans MS (bold italic) 

    /* liste plats + prix ( en gras only price) */
    font-family: Curlz MT Regular, Harrington Regular

/****************************************************************************/
Dans l'image "menu-2.png",

    body {
        background-color: #fff5fe;
    }

    /* Titre "Le chic à la francaise" - couleur degrade */
    color: #db8528, #8f5bfe;
    font-family: Forte Regular, Segoe Print Bold, Segoe Script Bold, Comic Sans MS italic

    /* Titre des trois submenu */
    font-family: Georgia Bold, Book Antiqua Bold, Constantia Bold

    /* Titre submenu01 avec sa bordure - "Pour se mettre en appetit" 
        + liste plats + prix */
    color: #c67412;

    /* Titre submenu02 avec sa bordure - "Plaisir des papilles" 
        + liste plats + prix */
    color: #a56799;

    /* Titre submenu03 avec sa bordure - "Gourmandises sucrées" 
        + liste plats + prix */
    color: #6e4ccc;

    /* liste plats + prix */
    font-family: Modern No.20 Regular, Perpetua Titling MT Light, Copperplate Gothic Light Regular

/****************************************************************************/
Dans l'image "menu-3.png",

    body {
        background-color: #edefef;
        color: black;
    }

    /* Titre "Le delice des papilles" - couleur degrade */
    color: #023be3, #0889fb;

    /* Titre "Le delice des papilles" */
    font-family: Forte Regular, Segoe Print Bold, Segoe Script Bold, Comic Sans MS italic

     /* Titre des trois submenu */
    font-family: Segoe Print Regular, Segoe Script Regular, Comic Sans MS italic

    /* la bordure de - "Pour bien commencer" */
    color: #0228dd;

    /* la bordure de - "Pour bien continuer" */
    color: #0670f3;

    /* la bordure de - "Pour bien terminer" */
    color: #229df9;

    /* liste plats + prix */
    font-family: Copperplate Gothic Bold Regular, Arial Black

/****************************************************************************/
Dans l'image "menu-4.png",

    body {
        background-color: #edefef;
        color: black;
    }

    /* Titre "La palette du gout" - couleur degrade */
    color: #61b14d, #beff7f;

    /* Titre "La palette du gout" */
    font-family: Mistral Regular, Forte Regular, Segoe Print Bold, Segoe Script Bold, Comic Sans MS italic

     /* Titre des trois submenu */
    font-family: Copperplate Gothic Bold Regular, Copperplate Gothic Light Regular, Arial Black

    /* la bordure Gauche de - "Esquisse" */
    /* la bordure Gauche de - "Oeuvre de maitre" */
    /* la bordure Gauche de - "Au sommet de l'art" */
    color: #4a9d41, #7bc65b, #bff88b;

    /* la bordure Droite degrade de - "Esquisse" */
    /* la bordure Droite degrade de - "Oeuvre de maitre" */
    /* la bordure Droite degrade de - "Au sommet de l'art" */
    color: #bff88b, #7bc65b, #4a9d41;

    /* liste plats + prix */
    font-family: Copperplate Gothic Bold Regular, Copperplate Gothic Light Regular, Arial Black

/****************************************************************************/