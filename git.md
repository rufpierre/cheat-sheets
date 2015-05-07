403 accès interdit lors d'un push
---
Il se peut que lors s'un push sur un repo public en https, on ait l'erreur suivante, même si l'on est autorisé sur le repo : 

    error: The requested URL returned error: 403 Forbidden while accessing https://rufpierre@github.com/affini-tech/scalding-skeleton.git/info/refs

il faut bien sûr configurer le user et l'email, mais aussi le remote, de la manière suivante:

    git remote set-url origin https://Your-Github-UserNAme@github.com/Your-Github-UserNAme/REPO-NAME
    
il est essenciel que de mettre le username avant `@github.com` au lieu de `/github.com/`, ce qui est le cas par défaut.
