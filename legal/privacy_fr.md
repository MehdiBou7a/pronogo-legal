---
layout: default
title: Politique de confidentialité — PronoGo
description: Comment PronoGo collecte, utilise et protège vos données personnelles.
---

# Politique de confidentialité — PronoGo

**Dernière mise à jour** : 19 août 2026
**Version** : 1.3

[← Retour à l'accueil](../../) · [English version](../privacy_en/)

---

## 1. Préambule

La présente politique de confidentialité (« Politique ») explique comment **PronoGo** (« nous », « notre application ») collecte, utilise et protège vos données personnelles lorsque vous utilisez l'application mobile PronoGo (« l'Application »).

L'éditeur de PronoGo est **Mehdi Bouhaouala**, entrepreneur individuel (auto-entrepreneur) immatriculé en France, dont les coordonnées de contact sont disponibles à la fin de cette Politique.

PronoGo est un jeu mobile de pronostics sportifs basé sur des **monnaies virtuelles** (tokens, pronocoins). **Aucun argent réel n'est mis en jeu, aucun gain monétaire n'est versé.** L'Application est gratuite à l'usage et se finance par des **achats intégrés optionnels** (via Google Play et l'App Store) et de la **publicité** (Google AdMob). Voir nos Conditions Générales d'Utilisation pour plus de détails.

En utilisant l'Application, vous reconnaissez avoir pris connaissance et accepté cette Politique.

---

## 2. Données que nous collectons

### 2.1 Données fournies lors de la création du compte

Vous pouvez créer votre compte de trois façons :

- **Email + mot de passe** : l'adresse email sert d'identifiant de compte et aux communications transactionnelles (dont l'email de vérification d'adresse). Le mot de passe est stocké sous forme de hash sécurisé par Firebase Authentication (jamais en clair).
- **Connexion Google** : nous recevons de Google votre adresse email, votre nom d'affichage et, le cas échéant, votre photo de profil. Nous ne recevons jamais votre mot de passe Google.
- **Connexion Apple** : nous recevons d'Apple votre adresse email (ou une adresse relais privée si vous choisissez « Masquer mon adresse email ») et votre nom d'affichage. Nous ne recevons jamais votre mot de passe Apple.

Dans tous les cas :

- **Pseudonyme (display name)** : affiché publiquement dans les classements, les ligues privées et le système d'amis.

### 2.2 Données générées par votre activité

- **Pronostics effectués** : matchs, types de paris, mises en tokens virtuels, résultats.
- **Cartes possédées** : collection, niveaux, évolutions, bonus.
- **Lineups deck** : compositions hebdomadaires.
- **Scores et classements** : weekly, monthly, season, lifetime.
- **Niveau XP, missions accomplies, mini-jeux, cartes mythiques**.
- **Membres de ligues privées** et **liste d'amis**.
- **Messages de discussion de ligue** : le texte que vous publiez, votre pseudonyme et la date de publication. Ils sont visibles par les autres membres de la ligue concernée (voir CGU, section 5.3).
- **Signalements** : lorsque vous signalez un message ou le profil d'un joueur, nous enregistrons un dossier de modération qui contient **votre identifiant de signalant ET celui de la personne signalée**, la ligue et le message concernés, le motif que vous saisissez, et — pour un signalement de profil — le **pseudonyme public de la personne signalée** au moment du signalement. Un dossier de signalement porte donc des données sur **deux** personnes.
- **Liste des joueurs que vous avez bloqués** : pour chaque joueur bloqué, son identifiant et le **pseudonyme qu'il portait au moment du blocage** (50 au maximum). Cette liste n'est visible que par vous.
- **Parrainage (code ami)** : si vous saisissez le code d'un parrain (ou si quelqu'un saisit le vôtre), le lien parrain/filleul est enregistré et votre **pseudonyme est visible par votre parrain** (et réciproquement) dans son suivi de parrainage. Aucune autre donnée personnelle n'est partagée via le parrainage.

### 2.3 Données techniques

- **Identifiant unique Firebase** (UID).
- **Token FCM** (Firebase Cloud Messaging) pour vous envoyer des notifications push.
- **Adresse IP** : collectée par Firebase pour des raisons de sécurité (anti-abus) et de géolocalisation pays (compliance store).
- **Type d'appareil, OS, version de l'application**.
- **Rapports de crash (Firebase Crashlytics)** : en cas de plantage, un rapport technique est envoyé (modèle d'appareil, version OS et app, état de l'application au moment du crash, traces techniques). Ces rapports servent uniquement à corriger les bugs.
- **Identifiant publicitaire** (Android Advertising ID / Apple IDFA) : utilisé par Google AdMob pour la diffusion publicitaire, selon votre consentement (voir section 4).

### 2.4 Données de transaction (achats intégrés)

Si vous effectuez un achat intégré (monnaie virtuelle, pack de cartes, lot de bienvenue), la transaction est **entièrement traitée par Google Play ou l'App Store**. Nous **ne voyons jamais et ne stockons jamais** votre numéro de carte bancaire ni vos coordonnées de paiement.

Nous recevons et conservons uniquement : l'identifiant du produit acheté, un jeton/identifiant de transaction fourni par la plateforme (pour vérifier l'achat et créditer votre compte), la date et l'état de la transaction. 

### 2.5 Données que nous NE collectons PAS

- Numéro de carte bancaire, RIB, coordonnées de paiement (gérés exclusivement par Google Play / App Store).
- Numéro de téléphone, adresse postale, identité civile complète.
- Localisation GPS précise.
- Contacts du téléphone.
- Photos, microphone, calendrier.

---

## 3. Comment nous utilisons vos données

Vos données sont utilisées exclusivement pour :

1. **Fournir le service** : login, sauvegarde de votre progression, calcul des scores, résolution des pronostics via l'API api-football.com.
2. **Personnaliser l'expérience** : classements, recommandations, notifications de matchs et résultats.
3. **Système social** : afficher votre pseudo dans les ligues, gérer la liste d'amis, les classements amis et le parrainage.
4. **Traiter vos achats intégrés** : vérifier les transactions auprès de Google Play / App Store, créditer les éléments achetés, prévenir la fraude, et satisfaire nos obligations comptables et fiscales.
5. **Sécuriser le service** : détection d'abus, anti-cheat, rate limiting.
6. **Améliorer l'application** : analyse anonymisée d'usage (Firebase Analytics), correction des bugs (Crashlytics).
7. **Monétisation par publicité** : affichage de publicités via Google AdMob (native ads et rewarded video volontaires). Voir section 4 pour le consentement.

Nous **ne vendons jamais** vos données à des tiers. Les publicités diffusées via AdMob sont **filtrées** : nous bloquons les catégories sensibles (paris en argent réel concurrents, contenu adulte, dating, politique, religion, etc.).

---

## 4. Publicité et consentement

L'Application affiche des publicités via **Google AdMob** : publicités natives intégrées à l'interface et vidéos « rewarded » que vous choisissez volontairement de regarder en échange de récompenses virtuelles.

**Consentement (EEE / Royaume-Uni / Suisse)** : avant toute publicité personnalisée, une **fenêtre de consentement Google UMP** (User Messaging Platform) vous est présentée. Vous pouvez accepter ou refuser la publicité personnalisée ; en cas de refus, des publicités **non personnalisées** (contextuelles) sont diffusées. Vous pouvez modifier votre choix à tout moment depuis les Réglages de l'Application.

Si vous consentez, AdMob peut utiliser votre **identifiant publicitaire** (Android Advertising ID / Apple IDFA) pour personnaliser les annonces. Vous pouvez aussi réinitialiser cet identifiant ou désactiver la personnalisation depuis les Réglages de votre appareil → Confidentialité → Publicités.

L'Application ne propose actuellement **aucun abonnement** : tous les achats intégrés sont des achats uniques.

---

## 5. Partage de données avec des tiers

### 5.1 Sous-traitants techniques

- **Google Firebase** (Authentication, Firestore, Cloud Functions, Cloud Messaging, App Check, Analytics, Crashlytics) — hébergement EU (région `europe-west9`), conformité RGPD.
- **Google Play / Apple App Store** — traitement des achats intégrés. Ces plateformes traitent vos données de paiement selon leurs propres politiques de confidentialité ([Google](https://policies.google.com/privacy), [Apple](https://www.apple.com/legal/privacy/)).
- **Google AdMob** — diffusion de publicités dans l'Application. Reçoit, selon votre consentement, votre identifiant publicitaire et des données techniques (IP, type de device, langue) pour le ciblage publicitaire. Aucune donnée personnelle nominative (email, nom) n'est transmise.
- **api-football.com** — fournit les données des matchs (composition équipes, scores, résultats, statistiques). Aucune donnée personnelle ne lui est transmise.

### 5.2 Limites du partage commercial

Nous ne partageons aucune donnée avec :
- Réseaux sociaux.
- Brokers de données.
- Sites de paris en ligne.
- Annonceurs concurrents (bookmakers FR explicitement bloqués dans AdMob).

---

## 6. Durée de conservation

| Donnée | Durée |
|---|---|
| Compte utilisateur (users, user_scores, cards, predictions, lineups) | Tant que le compte est actif |
| Notifications inbox | 7 jours (TTL automatique) |
| Logs daily claims | 15 jours (TTL automatique) |
| Logs XP (xp_log) | 30 jours (TTL automatique) |
| Logs techniques et de sécurité (serveur) | Jusqu'à 90 jours |
| Justificatifs d'achats intégrés (transactions IAP) | Durée légale applicable (obligations comptables, fiscales et anti-fraude), y compris après suppression du compte |
| Messages de discussion de ligue | **30 jours au maximum**, et seuls les **200 derniers messages** de chaque ligue sont conservés (purge automatique quotidienne) |
| Liste des joueurs que vous avez bloqués | Tant que votre compte existe, ou jusqu'à ce que vous leviez le blocage |
| Dossiers de signalement | **90 jours**, par purge automatique. Cette durée n'est pas arbitraire : le dossier sert de verrou contre les signalements répétés, et le message qu'il vise vit au maximum 30 jours — trois fois cette durée laisse le temps de l'examen sans conserver une trace devenue invérifiable. Un dossier que vous avez déposé est en outre supprimé lorsque vous supprimez votre compte, et un signalement visant votre profil l'est lorsque vous supprimez le vôtre |

À la **suppression du compte** (via Réglages → Supprimer mon compte), vos données personnelles sont **effacées de façon irréversible** côté Firebase, conformément à l'article 17 du RGPD : compte, cartes, pronostics, compositions, amis, messages privés, progression et historiques.

**Six exceptions, et nous préférons vous les dire :**

| Ce qui subsiste | Pourquoi | Combien de temps |
|---|---|---|
| Les **justificatifs d'achat** | Obligation comptable et fiscale — l'article 17.3(b) du RGPD prévoit expressément ce cas | Durée légale de conservation |
| Vos **messages déjà publiés dans une ligue qui continue sans vous** | Les effacer trouerait la conversation des autres membres | Purge automatique à 30 jours |
| Votre **ligne de classement dans une ligue encore en cours** | La retirer fausserait le résultat des autres participants. Elle est **anonymisée en « Compte supprimé »** | Jusqu'à la fin de cette ligue |
| Votre **place au palmarès d'une saison terminée** | C'est l'histoire commune du jeu ; la réécrire changerait le classement des autres joueurs. Seules des informations **déjà publiques** y figurent (pseudonyme, hauteur atteinte, palier) | Conservé |
| Des **statistiques agrégées et anonymisées** | Elles ne sont plus rattachables à vous | Conservé |
| Les **dossiers de signalement portant sur un message que vous aviez publié** | Ils documentent le traitement d'un signalement déposé par un autre joueur. Le message lui-même a déjà disparu (purge à 30 jours) ; il ne subsiste que la trace de modération | Conservé comme trace de modération |

Tout le reste part. Voir notre page dédiée : [Suppression de compte](../delete_account_fr/).

---

## 7. Vos droits (RGPD)

Conformément au Règlement (UE) 2016/679, vous disposez des droits suivants :

- **Droit d'accès** : consulter les données que nous avons sur vous.
- **Droit de rectification** : modifier votre pseudo, email, etc.
- **Droit à l'effacement (« droit à l'oubli »)** : exercer via Réglages → Supprimer mon compte. La suppression est irréversible ; les six exceptions sont listées en section 6 ([instructions détaillées](../delete_account_fr/)).
- **Droit à la portabilité** : demander un export de vos données par email à `pronogo.dev@gmail.com`.
- **Droit d'opposition** : refuser certains traitements (ex : notifications push, désactivables dans les Réglages).
- **Droit de retirer votre consentement** : à tout moment, notamment pour la publicité personnalisée (Réglages de l'Application ou Réglages de votre appareil).
- **Droit d'introduire une réclamation** auprès de la CNIL (www.cnil.fr).

Pour exercer ces droits, contactez-nous à **pronogo.dev@gmail.com**.

---

## 8. Sécurité

Vos données sont protégées par :

- **Chiffrement en transit** : toutes les communications avec nos serveurs utilisent HTTPS/TLS.
- **Chiffrement au repos** : Firebase Firestore et Authentication chiffrent les données stockées.
- **Contrôle d'accès** : règles Firestore strictes empêchant un utilisateur d'accéder aux données d'un autre.
- **App Check** : protection contre les abus côté serveur.
- **Authentification renforcée** : Firebase Authentication, avec vérification d'adresse email.
- **Vérification serveur des achats** : chaque achat intégré est validé auprès de Google Play / App Store avant d'être crédité.

Aucun système n'étant infaillible, nous ne pouvons garantir une sécurité absolue, mais nous mettons en œuvre les meilleures pratiques de l'industrie.

---

## 9. Mineurs

PronoGo est destiné aux personnes **âgées d'au moins 16 ans**. Cette restriction s'applique mondialement (RGPD Europe : article 8 ; aux États-Unis et au Royaume-Uni : conformité COPPA et UK-GDPR par alignement).

Lors de la création de votre compte, vous déclarez explicitement avoir au moins 16 ans en validant la case de consentement.

Si vous constatez qu'un mineur de moins de 16 ans utilise PronoGo, contactez-nous à `pronogo.dev@gmail.com` — nous procéderons à la suppression du compte sans délai.

---

## 10. Cookies / stockage local

PronoGo stocke localement sur votre appareil :
- Token de session Firebase Authentication.
- Cache offline des données utilisateur (Firestore persistence).
- Préférences (langue, thème, opt-in notifications, choix de consentement publicitaire).
- Streak quotidien et compteurs publicitaires (SharedPreferences).

Le SDK Google Mobile Ads (AdMob) peut utiliser des identifiants techniques pour le ciblage publicitaire, selon votre consentement (voir section 4). Vous pouvez réinitialiser votre identifiant publicitaire ou désactiver la personnalisation depuis les Réglages de votre appareil → Confidentialité → Publicités.

---

## 11. Modifications de cette Politique

Nous nous réservons le droit de modifier cette Politique. La date « Dernière mise à jour » sera mise à jour en haut du document.

En cas de modification substantielle, nous vous informerons par notification in-app ou par email avant que les changements n'entrent en vigueur.

---

## 12. Contact

Pour toute question ou demande :

- **Email** : pronogo.dev@gmail.com
- **Adresse** : Mehdi Bouhaouala, Courbevoie, France

---

*PronoGo est édité par **Mehdi Bouhaouala**, entrepreneur individuel (auto-entrepreneur), domicilié à Courbevoie, France. L'application est gratuite à l'usage, avec des achats intégrés optionnels (monnaies virtuelles et lots de jeu via Google Play / App Store, tous consommables — aucun abonnement) et de la publicité (Google AdMob — native ads et rewarded video volontaires). Cette Politique sera mise à jour si le statut éditeur évolue (société) ou si de nouvelles fonctionnalités payantes sont introduites.*
