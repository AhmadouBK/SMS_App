Cette application Android est conçue pour envoyer et recevoir des SMS entre émulateurs. Voici une brève description :

Fonctionnalités Clés :

Envoi de SMS : Les utilisateurs peuvent saisir un numéro de téléphone et un message dans l'application, puis envoyer le SMS à ce numéro.
Réception de SMS : L'application est capable de recevoir des messages SMS et de les afficher à l'utilisateur.
Composants Principaux :

MainActivity : L'activité principale de l'application qui offre une interface utilisateur pour envoyer des SMS et afficher les messages reçus.
SMSReceiver : Un BroadcastReceiver qui écoute les messages SMS entrants et les affiche dans l'application.
Gestion des Permissions :

L'application demande les permissions nécessaires pour envoyer et recevoir des SMS, conformément aux exigences de sécurité et de vie privée d'Android.
Interface Utilisateur :

L'interface comprend des champs de texte pour saisir le numéro de téléphone et le message, un bouton pour envoyer le SMS, et un TextView pour afficher les messages reçus.
Ciblage :

L'application cible Android 12 (API niveau 31) et supérieur, nécessitant des spécifications explicites dans le manifeste pour les composants exportés.
Ce projet est un excellent exemple d'application de messagerie de base, illustrant la gestion des permissions, la communication entre composants et l'interaction avec le système de messagerie SMS d'Android.
