# Challenge Hackathon 48h : **Family Snap - Créez vos souvenirs partagés !**

![Family Snap](https://i.pinimg.com/1200x/f2/de/c1/f2dec19b2158acd2edc4fba0b34b6580.jpg)

## **Contexte**

Les moments passés en famille sont précieux, mais ils sont souvent dispersés dans les galeries personnelles des différents membres. Il manque une solution simple et sécurisée pour centraliser ces souvenirs. C’est ici que votre mission entre en jeu !

## **Objectif**

Développer une **Progressive Web App (PWA)** qui permet de créer des événements photo familiaux. Chaque événement génère un **code unique** et un **QR code** pour que les membres puissent facilement rejoindre l’événement, partager leurs photos, et vivre l’instant en direct via un **slideshow en temps réel**.

---

## **Fonctionnalités attendues**

### 1. **Création d’un événement**

-   Un utilisateur (créateur de l’événement) peut créer un événement avec un titre, une description et une date.
-   Un code unique et un QR code sont générés automatiquement pour permettre aux participants de rejoindre l’événement.

### 2. **Participation à l’événement**

-   Les invités scannent le QR code ou saisissent le code pour accéder à l’événement.
-   Une interface simple pour capturer des photos directement depuis l’application ou en importer depuis leur galerie.

### 3. **Galerie privée d’événement**

-   Les photos sont stockées dans une galerie privée associée à l’événement.
-   (**BONUS**) Un slideshow en temps réel affiche les photos ajoutées par les participants.

### 4. **Gestion des permissions**

-   Le créateur peut modérer les photos (ajout/suppression).
-   Possibilité de limiter les téléchargements ou d’autoriser le partage de certaines photos.

### 5. **Optimisation PWA**

-   **(BONUS)Accès offline** : possibilité de consulter les photos téléchargées localement.
-   Fonctionnalité **"ajouter à l’écran d’accueil"**.
-   (**EXTRA CHALLENGE**) Notifications push pour alerter les participants (ex. "Nouvelle photo ajoutée !").

### 6. **Accessibilité**

-   Interface claire et intuitive.
-   Responsive pour s’adapter aux smartphones, tablettes.

---

## **Bonus facultatifs**

-   **Filtrage des photos** : Appliquer des filtres ou des stickers sur les photos avant de les partager.
-   **Mode collaboratif** : Ajouter des commentaires ou des réactions aux photos.
-   **Reconnaissance faciale** : Identifier automatiquement les membres de la famille dans les photos (via une intégration IA simple).
-   **Téléchargement groupé** : Option pour télécharger toutes les photos d’un événement sous forme d’archive ZIP.

---

## **Livrables**

1. Un prototype fonctionnel de la PWA, accessible via un navigateur (**Déployé**).
2. Une présentation de 5 minutes expliquant :
    - Le concept.
    - Les technologies utilisées.
    - Une démonstration en direct.
3. _(Optionnel)_ Une vidéo de démonstration rapide.

---

## **Critères d’évaluation**

1. **Originalité et utilité** : L’application répond-elle à un besoin réel de manière innovante ?
2. **UX/UI** : L’application est-elle simple, attractive et facile à utiliser ?
3. **Aspects techniques** : Optimisation pour PWA, qualité du code, et fonctionnalités en temps réel (slideshow, galerie).
4. **Impact en temps réel** : Fluidité et rapidité de l’expérience lors des ajouts de photos ou du partage.
5. **Présentation** : Clarté et impact de la démonstration.

---

## **Ressources mises à disposition**

-   **APIs suggérées** :
    -   [Firebase](https://firebase.google.com/) ou [Supabase](https://supabase.io/) : pour l’authentification, le stockage des photos et la base de données.
    -   [Socket.io](https://socket.io/) : pour le slideshow en temps réel.
    -   [QR Code Generator API](https://goqr.me/api/) : pour créer et afficher des QR codes.
-   **Kits de design** : UI libraries comme [Tailwind CSS](https://tailwindcss.com/) ou [Material UI](https://mui.com/).
-   Mentors techniques disponibles pour aider sur les questions de PWA et temps réel.

---

## **Ambiance et organisation**

-   **Travail en équipe** : 4 à 5 participants par groupe.
-   Présentation finale devant un jury.

---

Bonne chance à toutes les équipes et amusez-vous en créant une application mémorable ! 🎉
