# Création de variable

Nous avons créer des variables afin de pouvoir concevoir des thèmes simplement et efficacement.  
On a placé tous les aspects importants du design dans des variables de manière à pouvoir manipuler tout cela très facilement par la suite.  

Voici un aperçu des variables par défaut : 

```scss
// Fonts Family

$fontRoboto: 'Roboto', sans-serif;
$fontRobotoMono: 'Roboto Mono', monospace;
$fontVerdana: 'verdana';
$fontAmatic: 'Amatic SC', Cursive;

// Background Fog Colors && First Color Charte

$bgDorothyImg: "../../img/bg-doro5.png";

$backgroundColor1: #978EFF; // <== base color / ref color
$backgroundColor2: #63A9FF;
$backgroundColor3: #667cbe;
$backgroundColor4: #d47fa5;
$backgroundColor5: #b97cbf;
$backgroundColor6: #7F49DD;

$bodyColor: rgba(255, 255, 255, 1); // base fontColor for the body

// loading page - call to action

$fontColorCallToAction: white;
$backgroundCallToAction: #7968ff;
$backgroundCallToAction2: white;
$backgroundCallToActionHover: #6bfff4; 
$backgroundLogoCallToAction: white; // <== background color logo google

// Interface

$fontColorDateTime: rgba(255, 255, 255, 0.9); 
$fontColorMenuTheme: rgba(255, 255, 255, 0.9);

$colorWelcomeMessage: $bodyColor;
$colorWelcomeMessageHover: lightgrey;
$fontSizeWelcomeMessage: 25px;

// Terminal

$fontColorDorothyAnswer: #81ffff; 

// Modal

$fontColorModal: white; // Global font color for modal

$fontColorModalCreators: lightgray; 
$colorBoxShadowModal: #0D1321;
$underlineProfileInput: 1px solid black;

$logoutButton: $fontColorModal;
$logoutButtonHover: #e17474;
$fontColorTooltip: $fontColorModal;
$backgroundColorTooltip: #555;

$borderStyleModal: 2px solid $fontColorModal; // "Save" button
$colorSaveButton: $fontColorModal;
$colorSaveButtonHover: #232323;
$backgroundSaveButtonHover: $fontColorModal;


// Ball Menu

$colorBall1: #8ee7db; 
$colorBall2: #abddff; 
$colorBallHover1: #a69df0; 
$collorBallHover2: #6896b5; 
$colorBallDiffusion: 100px; //shadow-in diffusion
$colorBallDiffusionHover: 100px;

$backgroundBallItem: rgba(255, 255, 255, 0.12); // Ball Menu - Icones Periph 
$backgroundBallItemHover: #645ea0;
$borderColorBallItem: white;
$colorLogoBallItem: white;
$unavailableBallCalendar: lightgrey;
```
