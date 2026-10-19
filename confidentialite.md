# Politique de confidentialité d'EasyDCA

*Dernière mise à jour : 19 octobre 2026. [English version](privacy.md)*

Cette politique explique quelles données l'application Android EasyDCA traite, pourquoi, où elles
sont conservées et comment exercer tes droits. Elle décrit l'appli telle qu'elle est : si elle
change, cette page sera mise à jour avant.

## 1. Qui est responsable

EasyDCA est éditée **à titre personnel, par un particulier**, responsable du traitement, joignable à l'adresse ci-dessous.
Contact pour toute question ou demande : **investisseurlogique@gmail.com**.

## 2. Ce qu'EasyDCA ne fait pas

- Pas de publicité, pas de revente ni de location de données, pas de profilage publicitaire.
- Pas d'outil de mesure d'audience ni de traceur publicitaire dans l'appli. Les seuls services
  tiers intégrés sont le suivi des plantages et l'envoi des notifications (Firebase, voir § 3 et § 6),
  sans aucune donnée d'usage. Le serveur **Discord** de la communauté est un service tiers
  **facultatif** : l'appli n'en propose qu'un lien et ne lui envoie aucune donnée (voir § 6).
- Aucune connexion à ta banque ou à ton courtier : EasyDCA ne voit ni tes comptes ni tes ordres.
  **Tous les montants sont ceux que tu saisis toi-même.**
- Pas de localisation, pas d'accès à tes contacts, photos, micro ou caméra.

## 3. Les données traitées

| Données | D'où elles viennent | À quoi elles servent |
|---|---|---|
| **Compte** : adresse e-mail et nom de ton compte Google, identifiant technique du compte | la connexion avec Google | te connecter, retrouver tes données sur un autre téléphone |
| **Plan d'investissement** : objectifs, montant visé, horizon, répartition par classe d'actifs et par actif, versions successives, motif d'un changement (et sa précision libre, privée) | ta saisie | afficher et suivre ton plan, ton historique « Mon parcours » |
| **DCA** : périodicité, date de début, part du revenu et/ou montant mensuel (facultatifs), rappel, versions et motifs | ta saisie | calculer tes échéances et tes rappels |
| **Journal** : échéances validées (réalisées ou non, à l'heure ou en retard), XP, niveau, série, jokers, jalons datés | tes validations | ta progression, Pépite, les succès |
| **Valeur du portefeuille** : montants que tu notes à la main (total et, si tu veux, par classe d'actifs) | ta saisie | la courbe de valeur et le rééquilibrage par les flux |
| **Online** (seulement si tu l'actives) : pseudo, code ami, amis et demandes, comptes bloqués, parrainage (parrain, filleuls), équipe (nom, membres, invitations), encouragements, partages de ton plan ou de ton DCA avec des amis choisis (montants seulement si tu les coches) | tes actions dans Online | amis, classement du mois, équipe, parrainage |
| **Limites anti-abus** : nombre d'essais de code ou de demandes d'ami | tes actions dans Online | éviter le spam et la recherche de comptes au hasard |
| **Sur ton téléphone seulement** : jeton de session, copie locale de tes données (pour que l'appli marche hors ligne), modifications pas encore envoyées, langue, succès et accessoires de Pépite, rappels programmés, données du widget d'écran d'accueil | l'appli | fonctionner hors connexion, rappels et widget |
| **Rapports de plantage** (Firebase Crashlytics) : quand l'appli plante ou rencontre une erreur, la trace technique (fichier et ligne du code en cause, type d'erreur, message débarrassé des e-mails, nombres, montants et identifiants), le modèle et la version d'Android du téléphone, la version de l'appli, un identifiant d'installation aléatoire de Firebase | l'appli, automatiquement (version publiée seulement) | trouver et corriger les plantages ; jamais ton e-mail, ton identifiant de compte, tes montants ni ton plan |
| **Jeton de notification** (Firebase Cloud Messaging) : identifiant d'installation de l'appli pour les notifications, type de téléphone (Android), fuseau horaire du téléphone, date de mise à jour | l'appli, après ta connexion | t'envoyer tout de suite une notification (demande d'ami, partage, invitation ou nouvelle d'équipe, encouragement) et, le soir à 18 h dans ton fuseau, un rappel si l'échéance du jour n'est pas validée et que tes rappels sont activés ; effacé à la déconnexion et à la suppression du compte |
| **Liaison Discord** (seulement si tu lies ton compte) : identifiant numérique de ton compte Discord, date de la liaison, trace du bonus d'XP (date, 50 points) ; code de liaison temporaire | ta demande de code dans l'appli, puis la commande « /lier » que tu tapes sur le serveur Discord | te donner le rôle « Membre vérifié » sur le serveur et le bonus de 50 XP une seule fois ; jamais ton e-mail, tes montants ni ton plan, et rien n'est envoyé à Discord par l'appli |
| **Lien d'installation** (Google Play Install Referrer) : le code ami contenu dans un lien d'invitation | Google Play, au premier lancement | pré-remplir le code de ton parrain ; il n'est envoyé au serveur que si tu valides ce code |

Les **rappels** (veille, jour J, jours suivants, « Revoir dans 7 jours ») sont des notifications
programmées sur ton téléphone. En plus, le serveur peut réveiller l'appli par **Firebase Cloud
Messaging** (Google) : le message ne contient que son type (par exemple « encouragement » ou
« rappel »), jamais un pseudo, un montant ni ton plan ; l'appli relit alors les nouveautés et affiche
elle-même la notification. Une tâche de fond interroge aussi le serveur de temps en temps, en filet de
sécurité. Tu peux couper les notifications dans les réglages d'Android ou les rappels dans ton DCA.

La **carte de partage de Pépite** est une image fabriquée sur ton téléphone ; elle ne part que vers
l'application que tu choisis dans la feuille de partage d'Android.

## 4. Qui voit quoi

- **Toi seul** : ton e-mail, ton plan, ton DCA, tes montants, ta valeur de portefeuille, tes
  motifs, ton journal.
- **Tes amis** (si Online est activé) : ton pseudo, ta Pépite, ton niveau et ton XP, ta série si tu
  la partages, ta place au classement du mois ; ton plan et/ou ton DCA seulement pour les amis à qui
  tu les partages, et les montants seulement si tu les coches.
- **Tes coéquipiers** : ton pseudo, ta Pépite, ton niveau, ton XP, ta série si tu la partages, si tu
  as fait ton DCA de la période ; jamais ton plan, ton DCA ni un montant.
- **Personne d'autre**. L'éditeur peut accéder à la base pour l'administrer (corriger un problème,
  supprimer un compte sur demande) ; il ne s'en sert pas à d'autres fins.

## 5. Bases légales

- **Exécution du contrat** (les conditions d'utilisation) : compte, plan, DCA, journal, progression,
  valeur du portefeuille, fonctionnement hors ligne.
- **Consentement**, que tu peux retirer à tout moment : Online (désactivable dans les réglages
  Online), chaque partage (révocable), les notifications (réglages d'Android).
- **Intérêt légitime** : limites anti-abus, sécurité du service, rapports de plantage (corriger les
  erreurs de l'appli).

## 6. Où sont les données, qui les héberge

Les données du serveur sont hébergées par **Supabase** (base de données et authentification), région
**Union européenne, Paris (AWS eu-west-3)**. La connexion
passe par **Google** (compte Google). Les rapports de plantage et les notifications passent par
**Google Firebase** (Crashlytics et Cloud Messaging, Google Ireland Limited) : rapports de plantage
gardés 90 jours par Firebase. Ces prestataires agissent comme sous-traitants. Si des données
sont transférées hors de l'Union européenne, c'est avec les garanties prévues par le RGPD (clauses
contractuelles types du prestataire). Toutes les communications sont chiffrées (HTTPS).

Les données ne partent pas dans la sauvegarde Google du téléphone : elles reviennent depuis le
serveur quand tu te reconnectes.

**Discord (service tiers facultatif)** : l'appli propose de rejoindre le serveur Discord de la
communauté EasyDCA (tutos, entraide, salons d'équipe). Discord (Discord Inc.) est un service
indépendant, avec ses propres conditions et sa propre politique de confidentialité, qui s'appliquent
à ce que tu y publies. L'appli n'intègre aucun outil de Discord et ne lui envoie aucune donnée : le
lien s'ouvre simplement dans Discord ou dans ton navigateur. Si tu lies ton compte (« Lier mon
compte Discord »), la liaison est faite par le serveur d'EasyDCA quand tu tapes ton code sur Discord :
seul l'identifiant numérique de ton compte Discord est alors conservé dans Supabase, sans ton pseudo
Discord ni tes messages.

**Alertes internes d'exploitation** (intérêt légitime : suivre le bon fonctionnement du service) :
l'éditeur, et lui seul, reçoit dans un salon privé de son serveur Discord de courtes alertes (nouveau
compte avec son numéro d'ordre, premier versement validé avec ton pseudo s'il existe, premier
utilisateur ou première équipe à atteindre un palier, erreurs techniques, chiffres agrégés de la
semaine). Elles ne contiennent jamais ton e-mail, tes montants ni ton plan.

## 7. Combien de temps

- Tant que ton compte existe, pour tout ce qui sert à l'appli.
- Encouragements d'équipe : 30 jours au plus ; invitations d'équipe : 7 jours ; limites anti-abus :
  environ un jour ; rappels du soir déjà envoyés (date de l'échéance) : 60 jours.
- Liaison Discord : jusqu'à ce que tu délies ton compte (Profil et réglages) ou que tu supprimes ton
  compte ; code de liaison : 15 minutes au plus, effacé dès qu'il sert ; trace du bonus d'XP (pour
  ne pas le verser deux fois) : jusqu'à la suppression du compte.
- Jeton de notification : jusqu'à la déconnexion, la suppression du compte, ou dès que Firebase
  l'indique comme périmé (appli désinstallée). Rapports de plantage : 90 jours chez Firebase.
- À la **suppression du compte**, tout est effacé immédiatement et définitivement (voir
  [Supprimer ton compte](suppression-du-compte.md)). Seule exception : l'XP déjà gagnée par ton
  parrain grâce à toi reste sur son compte, sans lien avec le tien.
- Sur ton téléphone : jusqu'à la déconnexion, la suppression du compte ou la désinstallation.

## 8. Tes droits

Tu peux à tout moment **accéder** à tes données, les **rectifier**, les **effacer**, en
**demander une copie** (portabilité), **t'opposer** à un traitement ou en demander la
**limitation**, et retirer ton consentement. La plupart se font dans l'appli (modifier ton plan ou
ton DCA, désactiver Online, révoquer un partage, supprimer ton compte). Pour le reste, écris à
**investisseurlogique@gmail.com** depuis l'adresse de ton compte Google : réponse sous
un mois au plus.

Tu peux aussi adresser une réclamation à la CNIL ([cnil.fr](https://www.cnil.fr)).

## 9. Âge minimal

EasyDCA s'adresse aux personnes de **18 ans et plus**. Elle ne vise
pas les enfants.

## 10. Changements

Si cette politique change de façon importante, l'appli ou cette page te le dira avant que le
changement s'applique.
