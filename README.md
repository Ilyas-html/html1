<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="utf-8">
<title> Exercice 15  </title>
<link rel="stylesheet" href="style.css">
<script src="script.js"></script>
</head>

<body>
    <h1 align="middle" >Exemple de formulaires</h2> 
    <p>Reproduire les éléments de formulaire suivants</p>
    <input type="text">

    <h2>Cases à cocher</h2>
    <input type="checkbox">case 1 <br/>
    <input type="checkbox"  checked >case 2 pré cochée <br/> 
    <input type="checkbox" >case 3   <br/> 

    <h2>Boutons radio</h2>
    <input type="radio"> salé 
    <input type="radio"> sucré 
    <input type="radio"> sans saveur

    <h2> Envoyer un fichier...</h2>
    <input type="file" name="attach">

    <h2>Champ de saisie de mot de passe</h2>
    <input type="password">

    <h2>Soumettre un formulaire</h2>
    <input type="submit" value="Envoyer" name="file">

    <h2>Ou le remettre a zéro ! </h2>
    <input type="text">
    <input type="reset" value="Mettre a zéro"> <br/>  <br/> <br/> <br/> 

    <h1> Champ de saisie long</h1>
    <TEXTAREA name="nom" rows=4 cols=40></TEXTAREA>

    
    <h2>Format par défaut</h2>
    <select id="Selection fromage">
            <option value="">--Choissisez une option--</option>
            <option value="beaufort">beaufort</option></select>
    
            <h2>On raffine un peu</h2>

            <select id="Selection fromage" size="4">
                    <option value="">--Choissisez une option--</option>
                    <option value="saint nectaire">saint nectaire</option>
                    <option value="camembert">camembert</option>
                    <option value="beaufort">beaufort</option>
                    <option value="beaufort">saint nectaire</option></select>

    <h2>Un exemple combinant plusieurs types de champs</h2>

    <p>Votre adresse de courrier électronique</p>
    <input type="email" id="email" pattern=".+@gmail.com" name="user_email" size="30" required>

    <p>Tapez ici votre commentaire: </p>
    <TEXTAREA name="Votre commentaire" rows=4 cols=40></TEXTAREA> <br/> <br/>

    <input type="submit" value="Envoyer" name="Fichier">
    <input type="reset" value="Annuler" name="Efface">

    


</body>   
    
    
            
            
            

    
