
# How to install

1. Installer le fichier sql dans votre bdd
2. Aller dans Model/bdd.php et modifier la ligne en mettant les informations de votre bdd

    $this->db = new PDO('mysql:host=localhost;dbname=my_spotify_db','user','password');
