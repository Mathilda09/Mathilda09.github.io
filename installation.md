CMS Cours 3

Création du répertoire "sites"
on se place dans /home/
puis on ouvre un terminal 
on tape pour créer le dossier sites= sudo mkdir sites

Changement des droits pour le répertoire "sites" 
pour récupérer tout les droits on tape = sudo chmod 777 sites
	Entrez le mot de passe de foot


Installation de Jekyll
pour installer "jekyll" = sudo apt-get install jekyll
Arret de l'installation => car demande d'autorisation => répondre o puis entrer

Vérification que l'installation c'est bien passé 
on tape = jekyll -v 
cela affiche = la version présente de Jekyll

Mise en route de Jekyll
commande = sudo jekyll new myblog 
puis = cd myblog 
pour vérifier => on tape dans la barre de recherche "localhost:4000"

Mise à jour de Jekyll 
il faut installer Ruby + rudy gens + rudy dev 
sudo apt-get install ruby ruby-dev make gcc nodejs
sudo gem install jekyll --no-rdoc –no-ri

GITHUB :
création d'un nouveau compte Github
puis créer un référentiel qui aura pour nom => username/username.github.io
choisir comme client « un terminal »
Retourner dans la machine virtuel ouvrir un terminal dans le dossier site 
puis on tape git clone https://github.com/username/username.github.io ce qui permet
de cloner ton référentiel
création d'un dossier au nom de ton username
création d'un index.html
dans le terminal taper cd username.github.io
echo "Hello World" > index.html
puis git add . Ce qui ajoute tout les fichiers
puis git status
git add --all
git commit -m "Initial commit"
git push -u origin master







