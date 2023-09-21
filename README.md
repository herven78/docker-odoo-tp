### Odoo est le programme de gestion d'entreprise le plus évolutif et le plus installé au monde grâce à ses applications répondant à tous les besoins d'une entreprise, de la gestion de la relation client à la création de sites web et d'e-commerce, en passant par la production, la gestion d'inventaire, la comptabilité ..


# Dans ce tp nous allons déployer une web app "odoo" a l'aide d'un fichier docker-compose.yaml

# Preréquis : Installez docker-compose ainsi que ses dépendances.

## C'est parti !  

1- Creer un dossier dockercomposetp dans lequel nous allons bosser.

2- lancez la commande : "git clone https://github.com/herven78/docker-odoo-tp.git"  
tout en étant dans le dossier dockercomposetp pour recupéré le fichier docker-compose.yaml   

3- Dans le dossier dockercomposetp , Créez un fichier nommé "odoo_pg_pass" et 
Le contenu du fichier doit être le mot de passe PostgreSQL, en texte brut. Par exemple, si le mot de passe PostgreSQL est "Mypassword1234" , le fichier contiendra la ligne suivante : "Mypassword1234"

4- Une fois les étapes précedentes réalisées , assurez vous d'etre dans le dossier dockercomposetp.
 Lancez la  commande: " docker-compose up -d "


### Pour plus d'info rendez vous sur le site : https://hub.docker.com/_/odoo/

### @hv

