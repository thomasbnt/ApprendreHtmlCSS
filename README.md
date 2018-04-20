# Introduction

Apprendre les balises du HTML et du langage CSS avec des leçons, des exemples et des exercices.

HTML d'où son acronyme **Hyper Text Markup Language** , c'est un langage de balisage utilisé sur des sites web souvent accompagné du CSS pour le style.

CSS : **Cascading Style Sheet** est un langage qui ajoute du style pour vos pages web. Il ajoute donc couleurs et formes ainsi donner du volume.

# Les chapitres

#### Les outils pour développer chez soi

###### Il vous faut un éditeur de texte.
[Atom](https://atom.io), [Visual Studio Code](https://code.visualstudio.com) ou encore [Sublime Text](https://www.sublimetext.com) sont gratuits.
###### Un navigateur web
[Mozilla Firefox](https://www.mozilla.org/fr/firefox/new/), [Google Chrome](https://www.google.fr/chrome/index.html), [Opéra](https://www.opera.com/fr) etc.

#### Quelques bases du HTML

* [Un exemple d'un fichier HTML](exemples/exemple_fichier_html_basique.html)
  * Avec la balise `<html>` pour encadrer tout le code HTML
  * Avec la balise `<head>` pour l'entête de la page
  * Avec la balise `<title>` pour le titre de la page
  * Avec la balise `<body>` pour le corps de la page
  * Avec un `charset UTF-8` pour les accents visible

* [Un exemple des métas importants pour le référencement web et l'optimisation de votre page](exemples/exemple_metas_head.html)
  * Voir la leçon sur le référencement naturel (SEO)

* [Un exemple complet des différents balises dans le body](exemples/exemple_le_body.html)


#### Le référencement naturel (SEO)

Le référencement est une des clés importantes pour que votre site web soit visité constamment. Il suffit de quelques lignes de codes afin que votre page soit indexé sur Google, DuckDuckGo, Qwant et pleins d'autres moteurs de recherche.

Pour cela, à chaque page vous devez ajouter ces lignes si dessous et modifier selon vos conditions :

* Le titre
```html
<title>Voici mon titre de ma superbe page</title>
```
* La description
```html
<meta name="description" content="Voici la description de votre page. Elle doit être assez longue et bien compréhensible pour capter l’œil de votre visiteur.">
```
> ⚠ La description ne doit pas être très longue et ni très courte.

* Les mots clés
```html
<meta name="keywords" content="apprendre,html,css,français">
```
> ⚠ Chaque mot doit être séparé par une virgule.

* L'auteur
```html
<meta name="author" content="John Doe">
```

* L'indexation

Si vous voulez que votre page soit vu sur les moteurs de recherche :
```html
<meta name="robots" content="index, follow">
```
Sinon mettre le préfixe de `no` afin de le désactiver :

```html
<meta name="robots" content="noindex, nofollow">
```

Même chose pour le robot de Google :

```html
<meta name="googlebot" content="index, follow">
```
