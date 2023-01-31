# 1. Polices de caractères

[Lien vers la page](https://cynthiaapura.github.io/portfolio_developer/)
## Liens utiles pour les polices caractères

* BDD de polices de caractères ; https://www.dafont.com/fr/theme.php?cat=603

* Générateur de polices de caratacères ; https://www.fontsquirrel.com/tools/webfont-generator 

## Étapes pour la mise en place d'une police de caractères 
- Télécharger une police de caractère sur Dafont (cf lien ci-dessus)
- Créer un dossier "font" dans le dossier du projet.
- Généré cette police choisi sur "fontsquirrel" (cf lien ci-dessus) et la placer dans le dossier "font" du projet
- Implémenter la police dans le HTML ou le CSS

### **Manière d'appliquer la police de caractère dans le projet en cours**


Pour le HTML ;
```HTML 
<link rel="stylesheet" href="./font/autography/stylesheet.css">
```
Pour le CSS ;
```CSS
/* theme */

@font-face { /* contenu du ficher stylesheet.css */
    font-family: '../font/autographyregular';
    src: url('../font/autography-webfont.woff2') format('woff2'),
         url('../font/autography-webfont.woff') format('woff');
    font-weight: normal;
    font-style: normal;

}
header h1{
    font-size: 8rem;
    font-family: '../font/autographyregular';
    line-height: 8.0rem;
    text-align: center;
}
```

# 2. Les icons

Pensez a toujours télécharger les icons en SVG pour quelles ne soient pas pleines de pixel/déformées lorsqu'on agrandi/reduit

Toujours les ranger dans le dossier asset.