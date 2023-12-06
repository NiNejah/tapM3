# DM3 

## vite bundling :

### Introduction to ViteJs :  

Vite est un outil de développement rapide pour la création d'applications web modernes, principalement associé au framework Vue.js. Il se distingue par sa rapidité exceptionnelle de construction et de développement, optimisant l'expérience du développeur tout en offrant des performances accrues pour les utilisateurs finaux. Conçu pour prendre en charge le développement par composants, Vite utilise une approche novatrice qui privilégie le chargement asynchrone et le découpage de code.

Avant, pour rendre notre code JavaScript modulaire, on utilisait des outils qui regroupaient tous nos morceaux de code. Mais à mesure que nos projets devenaient plus gros, cela prenait beaucoup de temps pour démarrer et voir nos changements. Vite résout ce problème en utilisant de nouvelles technologies, comme les modules ES natifs dans les navigateurs, pour rendre notre développement plus rapide et agréable [1].

Vite adopte une approche de "lazy loading" pour améliorer les performances des applications en chargeant les ressources de manière asynchrone lorsque cela est nécessaire.

<img src="./image1.svg" width="500">



### Lazy loading 

Le lazy loading, ou chargement différé, est une technique qui consiste à retarder le chargement de certaines parties d'une application jusqu'à ce qu'elles soient réellement nécessaires. 

Dans le contexte de Vite, le lazy loading est souvent utilisé pour charger les composants ou les modules de l'application uniquement lorsqu'ils sont demandés, plutôt que de les charger tous au démarrage. Cela peut être particulièrement bénéfique pour les applications volumineuses où charger tous les composants dès le départ peut entraîner des temps de chargement plus longs. Cette approche est particulièrement pertinente pour les composants, les modules, et même les routes d'une application Vue.js. En effet, elle contribue à réduire le temps de chargement initial de l'application en ne téléchargeant que les ressources essentielles au démarrage. 

<img src="./image2.svg" width="500">


### Application de lazy loading ? 

Pour illustrer ce mécanisme, nous allons utliser un projet qu'on a developpé en utilisant vueJS avec vite. 

On voit sur la première capture d'écran, 








## Références :  
[1] [vite.dev](https://vitejs.dev/guide/why.html), site officile de vite, consulté demain.
