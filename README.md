# Dietetique Nutrition

## L'environnement de travail.

- Pc Windows10
- Composer
- GitHub
- Symfony CLI
- Editeur de code (Visual Studio Code)
- Navighatuer, Firefox, Chrome, Edge
- PHP 8.3.1
- Framwork Bootstrap
- Symfony 6.4
    
## Installation
Je ne vais pas détailler sur l'installation, mais je dois vérifier mon environnement de travailler avant de commencer à coder.

je vérifie la version de Composer installée sur mon système.
```bash
$ Composer -V
Composer version 2.6.6 2023-12-8 18:32:18
```
Puis la version de Git.

```bash
$ git -v
git version 2.43.0.windows.1
```
Ensuite la version de Symfony CLI.

```bash
$ symfony -v
Symfony CLI version 5.8.11 (c) 2021-2024 Fabien Potencier (2024-02-15T14:20:36Z - stable)
Symfony CLI helps developers manage projects, from local code to remote infrastructure
```
Et la version de PHP.

```bash
$ php -v
PHP 8.3.1 (cli) (built: Dec 20 2023 14:06:10) (ZTS Visual C++ 2019 x64)
Copyright (c) The PHP Group
Zend Engine v4.3.1, Copyright (c) Zend Technologies
```

Je vais maintenant vérifier si mon PC répond à toutes exigences.
```bash
$ symfony check:requirements
```
![](/public/Images/requirements.JPG)

Mon système est prêt, je peux créer mon application, toujours avec la documentation de Symfony.

```bash
$ symfony new mysfwebsite --version="6.4.*" --webapp
```
Une fois l'installation est terminée, j'initialise mon projet à GitHub.

![](/public/Images/Gitinit.JPG)

Aller vérifier sur mon compte GitHub, (c'est commit de la modification de Readme.md).

![](/public/Images/Modification%20sur%20Readme.md.JPG).

