---
title:   L'ecosysteme
isChild: true
anchor:  the-ecosystem
---

## L'ecosystème {#the_ecosystem}

A minima, vous devez savoir utiliser Git](https://git-scm.com/){:target="_blank"} et [Composer](https://getcomposer.org/){:target="_blank"}. Bien que non requis, il est recommandé d'avoir un compte sur [GitHub.com](https://github.com/){:target="_blank"} puisque c'est là c'est la que tout le code est c'est dépendances sont hébergées.

Vous DEVEZ être a l'aise avec l'utilisation de la ligne de commande [Command Line Interface (CLI)](https://en.wikipedia.org/wiki/Command-line_interface){:target="_blank"}, en particulier le Shell Unix (sh, ksh, csh, tcsh, bash etc) puisque il est fortement utilisé pour des tache commune dans le travail avec Laravel

Pour le développement en local, vous devrez avoir au moins [Vagrant](https://www.vagrantup.com/){:target="_blank"} et [VirtualBox](https://www.virtualbox.org/){:target="_blank"} installé. C'est utilisé par [Homestead](https://laravel.com/docs/5.8/homestead){:target="_blank"} (une box vagrant dédiée au lancement d'applications Laravel). Bien que vous puissiez utiliser la stack traditionnelle WAMP/MAMP/XAMPP, ces dernière ne sont pas officiellement supporté, vous pourriez donc perdre du temps en chemin

Le cheminement classique de Laravel concernant le développement frontend peut semblé decourageant puisque il se compose d'une longue chaine de technologies. Vous pouvez utiliser au choix [Laravel Blade](https://laravel.com/docs/5.8/blade) qui est un moteur de template côté serveur ou créer un rendu côté client, qui a pour point de départ [Mix](https://laravel.com/docs/5.8/mix){:target="_blank"}, une sur-couche pour [Webpack](https://webpack.js.org/){:target="_blank"}. Webpack a ses dépendances gérée au travers de [npm](https://www.npmjs.com/), elles sont toutes des packages [NodeJS](https://nodejs.org/en/){:target="_blank"}.

CSS est géré sois avec [Sass](http://sass-lang.com/){:target="_blank"} ou [LESS](http://lesscss.org/){:target="_blank"}, alors que JavaScript peut etre fait a l'aide de Javascript simple, [ReactJS](https://reactjs.org/){:target="_blank"} et le plus commun des framework frontend utilisé avec Laravel : [VueJS](https://vuejs.org/){:target="_blank"}.

Pour la stack backend, au minimum, vous devez avoir un serveur web tel que [Nginx](http://nginx.org/){:target="_blank"}, un interpreteur PHP [PHP-FPM](http://php-fpm.org/){:target="_blank"} et une base de données [MySQL](https://www.mysql.com/){:target="_blank"}. D'autre composant optionnel de la stack sont [Memcached](http://memcached.org/){:target="_blank"}, [Redis](http://redis.io/){:target="_blank"} et [Beanstalkd](http://kr.github.io/beanstalkd/){:target="_blank"}.

Bien qu'il ne sois pas nécessaire de tous les comprendre directement, il est avantageux que vous soyez au moins familié avec et de vous renseigner sur ce qu'il font et quand les utiliser. Cela vous évitera des tas de confusions en lisant la documentation et des recommandation dans le futur.