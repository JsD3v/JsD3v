# Jean-Sébastien Christophe

**Développeur backend PHP / Symfony — applications métier, performance et mise en production**

Je développe des applications métier et e-commerce avec PHP et Symfony, avec une attention particulière à leur fonctionnement en production. Mon travail couvre aussi les intégrations de services, les traitements asynchrones, le déploiement et l’observabilité.

Je travaille actuellement chez [Agence DIX](https://www.agence-dix.fr/) et je développe en parallèle des projets personnels et open source. Je documente mes choix, mes essais et leurs limites sur [jschristophe.fr](https://www.jschristophe.fr/).

## Projets mis en avant

### UX Calendar Bundle

Bundle Symfony open source pour intégrer un calendrier sans imposer une bibliothèque front lourde. Il propose notamment des vues mois, semaine et jour, une utilisation headless et une API JSON optionnelle.

- Symfony 8 et PHP 8.4 minimum
- Turbo, Stimulus et AssetMapper
- CI publique sur la version 1.2.1 : [tests PHPUnit réussis](https://github.com/JsD3v/ux-calendar-bundle/actions/runs/33237163547) et [analyse PHPStan réussie](https://github.com/JsD3v/ux-calendar-bundle/actions/runs/33237163569)

[Dépôt GitHub](https://github.com/JsD3v/ux-calendar-bundle) · [Package Packagist](https://packagist.org/packages/jean-sebastien-christophe/ux-calendar-bundle) · [Retour de conception](https://www.jschristophe.fr/mon-premier-bundle-symfony-creation-de-ux-calendar-bundle-pour-symfony-8/)

### Kejja

Produit personnel en bêta privée consacré à la recommandation de films et de séries. J’y conçois le backend Symfony et un moteur de recommandation qui s’appuie sur les préférences, les retours d’usage et les embeddings. L’application iOS est en cours de développement.

[Découvrir Kejja](https://kejja.app/) · [Lire le retour d’expérience sur le moteur de recommandation](https://www.jschristophe.fr/moteur-de-recommandation-de-films-avec-symfony-kejja/)

### Diagnostic de performance avec FrankenPHP et k6

Retour d’expérience sur une campagne de charge menée avant un pic de trafic attendu. L’analyse a permis de distinguer une limite du générateur de charge d’une limite applicative, puis d’ajuster le dimensionnement des workers. Dans le scénario mixte documenté, le p95 de navigation est passé de 301 à 86 ms.

[Lire le retour d’expérience](https://www.jschristophe.fr/test-de-charge-frankenphp-ce-que-k6-a-vraiment-mesure/)

## Environnement de travail

- **Backend :** PHP 8, Symfony 7/8, API Platform, Doctrine
- **Données et asynchrone :** PostgreSQL, Redis, RabbitMQ, Symfony Messenger
- **Mise en production :** Docker, FrankenPHP, GitHub Actions, observabilité
- **Interface serveur :** Twig, Stimulus, AssetMapper, Turbo

## Me retrouver

- [Portfolio et articles](https://www.jschristophe.fr/)
- [Kejja](https://kejja.app/)
- [UX Calendar Bundle](https://github.com/JsD3v/ux-calendar-bundle)
- [Me contacter](mailto:hello@jschristophe.fr)
