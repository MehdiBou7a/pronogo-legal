---
layout: default
title: Politique de confidentialité — PronoGo
description: Comment PronoGo collecte, utilise et protège vos données personnelles.
---

# Politique de confidentialité — PronoGo

**Dernière mise à jour** : 19 mai 2026
**Version** : 1.0

[← Retour à l'accueil](../) · [English version](../privacy_en/)

---

## 1. Préambule

La présente politique de confidentialité (« Politique ») explique comment **PronoGo** (« nous », « notre application ») collecte, utilise et protège vos données personnelles lorsque vous utilisez l'application mobile PronoGo (« l'Application »).

L'éditeur de PronoGo est **Mehdi Bouhaouala**, dont les coordonnées de contact sont disponibles à la fin de cette Politique.

PronoGo est un jeu mobile de pronostics sportifs basé sur des **monnaies virtuelles** (tokens, pronocoins). **Aucun argent réel n'est mis en jeu, aucun gain monétaire n'est versé.** Voir nos Conditions Générales d'Utilisation pour plus de détails.

En utilisant l'Application, vous reconnaissez avoir pris connaissance et accepté cette Politique.

---

## 2. Données que nous collectons

### 2.1 Données fournies lors de la création du compte

- **Adresse email** : utilisée comme identifiant de compte et pour les communications transactionnelles.
- **Mot de passe** : stocké sous forme de hash sécurisé par Firebase Authentication (jamais en clair).
- **Pseudonyme (display name)** : affiché publiquement dans les classements, les ligues privées et le système d'amis.

### 2.2 Données générées par votre activité

- **Pronostics effectués** : matchs, types de paris, mises en tokens virtuels, résultats.
- **Cartes possédées** : collection, niveaux, évolutions, bonus.
- **Lineups deck** : compositions hebdomadaires.
- **Scores et classements** : weekly, monthly, season, lifetime.
- **Niveau XP, missions accomplies, défis Tribunal**.
- **Membres de ligues privées** et **liste d'amis**.

### 2.3 Données techniques

- **Identifiant unique Firebase** (UID).
- **Token FCM** (Firebase Cloud Messaging) pour vous envoyer des notifications push.
- **Adresse IP** : collectée par Firebase pour des raisons de sécurité (anti-abus) et de géolocalisation pays (compliance store).
- **Type d'appareil, OS, version de l'application**.
- **Logs d'erreurs anonymisés** pour le debug et l'amélioration.

### 2.4 Données que nous NE collectons PAS

- Numéro de téléphone, adresse postale, RIB, identité civile complète.
- Localisation GPS précise.
- Contacts du téléphone.
- Photos, microphone, calendrier.

---

## 3. Comment nous utilisons vos données

Vos données sont utilisées exclusivement pour :

1. **Fournir le service** : login, sauvegarde de votre progression, calcul des scores, résolution des pronostics via l'API football-data.org.
2. **Personnaliser l'expérience** : classements, recommandations, notifications de matchs et résultats.
3. **Système social** : afficher votre pseudo dans les ligues, gérer la liste d'amis, classements amis.
4. **Sécuriser le service** : détection d'abus, anti-cheat, rate limiting.
5. **Améliorer l'application** : analyse anonymisée d'usage, debug.

Nous **ne vendons jamais** vos données à des tiers. Nous **ne diffusons pas** de publicité ciblée dans la V1 de l'Application.

---

## 4. Partage de données avec des tiers

### 4.1 Sous-traitants techniques

- **Google Firebase** (Authentication, Firestore, Cloud Functions, Cloud Messaging, App Check, Analytics) — hébergement EU (région `europe-west9`), conformité RGPD.
- **football-data.org** — fournit les données des matchs (composition équipes, scores, résultats). Aucune donnée personnelle ne lui est transmise.

### 4.2 Pas de partage commercial

Nous ne partageons aucune donnée avec :
- Annonceurs publicitaires.
- Réseaux sociaux.
- Brokers de données.
- Sites de paris en ligne.

---

## 5. Durée de conservation

| Donnée | Durée |
|---|---|
| Compte utilisateur (users, user_scores, cards, predictions, lineups) | Tant que le compte est actif |
| Logs XP (xp_log) | 30 jours (TTL automatique) |
| Logs daily claims | 15 jours (TTL automatique) |
| Notifications inbox | 7 jours (TTL automatique) |
| Logs serveur Firebase | Selon la politique Google Firebase (~30 jours) |

À la **suppression du compte** (via Réglages → Supprimer mon compte), **toutes vos données sont effacées définitivement et immédiatement** côté Firebase, en conformité avec l'article 17 du RGPD.

---

## 6. Vos droits (RGPD)

Conformément au Règlement (UE) 2016/679, vous disposez des droits suivants :

- **Droit d'accès** : consulter les données que nous avons sur vous.
- **Droit de rectification** : modifier votre pseudo, email, etc.
- **Droit à l'effacement (« droit à l'oubli »)** : exercer via Réglages → Supprimer mon compte. Suppression immédiate et irréversible.
- **Droit à la portabilité** : demander un export de vos données par email à `support@fcpronox.com`.
- **Droit d'opposition** : refuser certains traitements (ex : notifications push, désactivable dans Réglages).
- **Droit d'introduire une réclamation** auprès de la CNIL (www.cnil.fr).

Pour exercer ces droits, contactez-nous à **support@fcpronox.com**.

---

## 7. Sécurité

Vos données sont protégées par :

- **Chiffrement en transit** : toutes les communications avec nos serveurs utilisent HTTPS/TLS.
- **Chiffrement au repos** : Firebase Firestore et Authentication chiffrent les données stockées.
- **Contrôle d'accès** : règles Firestore strictes empêchant un utilisateur d'accéder aux données d'un autre.
- **App Check** : protection contre les abus côté serveur.
- **Authentification renforcée** : Firebase Authentication.

Aucun système n'étant infaillible, nous ne pouvons garantir une sécurité absolue, mais nous mettons en œuvre les meilleures pratiques de l'industrie.

---

## 8. Mineurs

PronoGo n'est **pas destiné aux personnes de moins de 13 ans**. Si vous résidez dans l'Espace économique européen, l'âge minimum est de **16 ans** (sauf consentement parental conformément à votre droit national).

Si vous constatez qu'un enfant de moins de 13 ans (ou 16 ans dans l'UE) utilise PronoGo, contactez-nous à `support@fcpronox.com` — nous procéderons à la suppression du compte sans délai.

---

## 9. Cookies / stockage local

PronoGo stocke localement sur votre appareil :
- Token de session Firebase Authentication.
- Cache offline des données utilisateur (Firestore persistence).
- Préférences (langue, thème, opt-in notifications).
- Streak quotidien (SharedPreferences).

Aucun cookie tiers de tracking publicitaire n'est utilisé.

---

## 10. Modifications de cette Politique

Nous nous réservons le droit de modifier cette Politique. La date « Dernière mise à jour » sera mise à jour en haut du document.

En cas de modification substantielle, nous vous informerons par notification in-app ou par email avant que les changements n'entrent en vigueur.

---

## 11. Contact

Pour toute question ou demande :

- **Email** : support@fcpronox.com
- **Adresse** : Mehdi Bouhaouala, Courbevoie, France

---

*PronoGo est un projet indépendant. L'application est éditée par un particulier dans le cadre d'une activité non-commerciale (ou : précisez votre statut juridique réel — auto-entrepreneur, SAS, etc., à mettre à jour avant launch).*
