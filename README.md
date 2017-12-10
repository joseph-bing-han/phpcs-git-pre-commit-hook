# phpcs-git-pre-commit-hook

Git pre-commit hook which checking your changes by PHP_CodeSniffer 3.1.1, and then auto fixing them

The config file is specially adapted for Laravel framework

Usage:

1. create directory
2. fetch code:
git clone git@github.com:joseph-bing-han/phpcs-git-pre-commit-hook.git

3. (Linux) cd phpcs-git-pre-commit-hook; ./install.sh <your_target_project_directory><br>
(Other) Copy file "pre-commit" and directory "cs" to <your_target_project_directory>/.git/hooks

4. have fun :)