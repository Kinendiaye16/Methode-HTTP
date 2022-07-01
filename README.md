# Methode-HTTP
Exercice 2
Lien de l'exercie "https://qkzk.xyz/docs/nsi/cours_premiere/ihm_web/http/"



1)exécuter une requête GET vers mon site, avec l’option -v en utilisant httpie
http -v get https://qkzk.xyz/docs/nsi/cours_premiere/ihm_web/http/



2)Donner
l’hôte de la requête: qkzk.xyz
User-Agent de la requête: HTTPie/3.2.1
code de la réponse: 200
longueur du contenu de la réponse :23633
type de contenu de la réponse: text/html; charset=utf-8
date de dérnière modification de la réponse : Tue, 28 Jun 2022 07:38:44 GMT
serveur de la réponse: GitHub.com

Exercice 3

1) Exécuter cette requête sur httpie

$ http -v POST https://httpbin.org/post hello=world bonjour=salut

2) La requête a-t-elle été exécutée correctement ? Comment le sait-on 

Oui la requete a été excécuté correctement parcequ'on obtient le code 200 qui indique que le document recherché par le client a bien été trouvé par le serveur

3)Le serveur transmet-il ce qu’il a reçu en retour ? Dans quel champ ?

Le serveur transmet ce qu'il a reçu dans le champ Host

4)La réponse de ce serveur est-elle un contenu html ?

Non la reponse n'est pas un contenu html

Exercice 4 :

Requête :curl -X POST http://docs.wave.com/business?shell#requests

Reponse: 

<html><head>
<meta http-equiv="content-type" content="text/html;charset=utf-8">
<title>411 Length Required</title>
</head>
<body text=#000000 bgcolor=#ffffff>
<h1>Error: Length Required</h1>
<h2>POST requests require a <code>Content-length</code> header.</h2>
<h2></h2>
</body></html>

