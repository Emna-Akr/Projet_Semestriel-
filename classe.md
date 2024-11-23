Cette application permetde :

--> Centraliser et faciliter l’accès aux données.
--> Obtenir une fiabilité des données à travers des contrôles de saisie efficaces.
--> Suivre et évaluer les activités en matière de formation.
--> Avoir une application évolutive et maintenable.
--> Modèles del’application:


Cette application contient les classes suivantes :

● Participant
-->Matricule_participant
-->Nom
-->Prenom
-->Date_naissance (type date)
-->Profil (Informaticien, Gestionnaire, Juriste,….)

● Formateur
-->Code_formateur
-->Nom
-->Prenom
-->Domaine (Gestion, Informatique, Comptabilite, Infographie, Droit,…)
-->Email
-->N°_telephone

● Profil
-->Code_profil
-->Libelle

● Domaine
-->Code_domaine
-->libelle

● Formation
-->Code_formation
-->Intitulé
-->Domaine (Gestion, Informatique, Comptabilite, Infographie, Droit,…)
-->Nombre_jours
-->Annee
-->mois
-->Formateur
-->Nombre_participants

● Utilisateur
-->Code_utilisateur
-->Login
-->Password