# TP-14-Client-Soap-Android-Kotlin-avec-KSOAP


📌 Objectif
Ce projet consiste à développer une application Android en Kotlin permettant de gérer des comptes bancaires (création, affichage, suppression) en consommant un service Web SOAP à l’aide de la bibliothèque ksoap2.

🏗️ Fonctionnalités
- Afficher la liste des comptes bancaires
- Créer un nouveau compte (courant ou épargne)
- Supprimer un compte existant
- Consommer un service SOAP via ksoap2
- Interface moderne basée sur RecyclerView + Material Design

🛠️ Technologies utilisées
Outil / Lib        Rôle
Kotlin             Langage principal
Android Studio     IDE
RecyclerView       Affichage des listes
Material Components Interface utilisateur
ksoap2-android     Consommation du service SOAP

🚀 Création du projet
Créer un projet Empty Activity avec :

Nom : SOAPCompteApp
Package : ma.projet.soapclient
Langage : Kotlin
Min SDK : API 21

Vérifier que le SDK Android est installé et configuré.

📦 Dépendances Gradle
Dans build.gradle (Module: app) :

implementation 'com.google.android.material:material:1.4.0'
implementation 'com.google.code.ksoap2-android:ksoap2-android:3.6.4'
