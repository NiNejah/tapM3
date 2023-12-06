# DM3 

## vite bundling :

### Introduction to ViteJs :  
Avant que les modules ES ne soient disponibles dans les navigateurs, les développeurs ne disposaient d'aucun mécanisme natif pour créer du JavaScript de manière modulaire. C'est pourquoi nous sommes tous familiers avec le concept de "bundling" : l'utilisation d'outils qui explorent, traitent et concaténent nos modules sources dans des fichiers qui peuvent être exécutés dans le navigateur.

Cependant, à mesure que nous créons des applications de plus en plus ambitieuses, la quantité de JavaScript que nous utilisons augmente considérablement. Il n'est pas rare que des projets de grande envergure contiennent des milliers de modules. Nous commençons à nous heurter à un goulot d'étranglement en matière de performances pour les outils basés sur JavaScript : le démarrage d'un serveur de développement peut souvent prendre un temps d'attente déraisonnable (parfois jusqu'à plusieurs minutes !), et même avec le remplacement à chaud de modules (HMR), les modifications de fichiers peuvent prendre quelques secondes avant d'être répercutées dans le navigateur. La lenteur de la boucle de rétroaction peut grandement affecter la productivité et la satisfaction des développeurs.

Vite vise à résoudre ces problèmes en tirant parti des nouvelles avancées de l'écosystème : la disponibilité de modules ES natifs dans le navigateur et l'essor d'outils JavaScript écrits dans des langages de compilation natifs. [1]


<img src="./image1.svg" width="500">

<img src="./image2.svg" width="500">


## Références :  
[1] [vite.dev](https://vitejs.dev/guide/why.html), site officile de vite, consulté demain.
