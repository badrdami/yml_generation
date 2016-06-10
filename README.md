# yml_generation
comment générer un fichier yml poire le reconnaissance de visage
Vous disposez des fonctions suivante pour générer l'yml
en utilisant la méthode de Eigen: 
    void eigenFaceTrainer();
en utilisant la méthode de fisher
    void fisherFaceTrainer();
en utilisant la méthode de LBPH:
    void LBPHFaceTrainer();
    
Vous disposez de la fonction suivante pour lancer une reconnaissance :
    int  FaceRecognition();
    vous pouvez la modifier pour changer de methode de reconnaissance. vous comprendrai lorsque vous verai les commentaires
Vous disposer d'autre fonction pour prendre des photos à parrtir d'une video temps réel afin d'ajouter une personne à la base de donnée


NB:
  Dans le dossier /Photo/fichier/ vous trouverai le fichier txt ou vous devais mettre le liens pour vos photos comme c'est donnée dans l'exemple
à savoir que chaque lien et suivi d'un label pour reconnaitre la personne à qui appartient l'image.
  le dossier orl_face à été utiliser pour ranger les photos de la base de donnée
  
