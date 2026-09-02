---
title: Politique de confidentialité — Eukleia
---

# Politique de confidentialité — Eukleia

**Dernière mise à jour :** 2 septembre 2026


## 1. En résumé

Eukleia rassemble vos succès Steam, PlayStation et RetroAchievements, et vous aide à
choisir lesquels viser.

- **Aucune publicité, aucun pistage, aucune mesure d'audience.** L'application n'embarque
  aucun outil d'analytique, de suivi de plantages ou de profilage publicitaire.
- **Vous ne saisissez jamais le mot de passe d'une plateforme de jeu.** Ni Steam, ni
  PlayStation, ni RetroAchievements — voir la section 3.
- **Vos données sont hébergées dans l'Union européenne** (Francfort, Allemagne).
- **Vos données ne sont visibles par personne d'autre**, sauf par les amis que vous
  ajoutez vous-même, et jamais vos notes — voir la section 6.
- **Vous pouvez tout effacer depuis l'application**, définitivement, en deux touches.

## 2. Qui est responsable de ces données

**Lorenzo Basoli**, éditeur de l'application Eukleia, agissant en tant que personne
physique.

Contact pour toute question ou demande relative à vos données :
**contact@demoos.fr**

Aucune adresse postale n'est publiée ici. Toute demande relative à vos données — accès,
rectification, effacement, limitation ou opposition — se fait par cette adresse, et
recevra une réponse dans le délai d'un mois que prévoit le règlement.

## 3. La connexion

Vous vous connectez par **Apple**, par **Google**, ou par **adresse e-mail et mot de
passe**.

**Votre mot de passe n'est jamais vu par nous.** Avec Apple et Google, il ne quitte pas
leur écran de connexion et nous ne recevons qu'un jeton d'identité signé. Avec une
adresse e-mail, le mot de passe est confié directement à notre hébergeur, qui n'en
conserve qu'une empreinte cryptographique irréversible.

**Ce que la création de compte enregistre : votre identifiant, et rien d'autre.** Ni
votre nom, ni votre photo ne sont repris d'Apple ou de Google. Votre adresse e-mail est
conservée par le service d'authentification pour vous reconnaître et, le cas échéant,
vous permettre de réinitialiser votre mot de passe. Si vous utilisez « Masquer mon
adresse e-mail » d'Apple, nous ne voyons que l'adresse relais qu'Apple génère.

### Les trois plateformes de jeu sont des liens, pas des identités

Steam, PlayStation et RetroAchievements se **rattachent** à un compte existant. Aucune
des trois ne sert à se connecter, et vous pouvez n'en lier aucune.

**Steam** utilise Steam OpenID, le mécanisme officiel de Valve : votre mot de passe Steam
n'est jamais vu, ni transmis, ni stocké, et Steam ne nous renvoie que votre
**identifiant SteamID64** — un nombre de dix-sept chiffres, public.

**RetroAchievements** se lie par votre pseudo et une clé d'API que vous générez sur leur
site. Votre mot de passe RetroAchievements n'est jamais demandé.

**PlayStation** se lie par un jeton de session que vous récupérez vous-même depuis votre
navigateur. **Votre mot de passe PlayStation n'est jamais demandé, et nous vous
déconseillons formellement de le saisir où que ce soit dans l'application** — elle ne
vous le demandera jamais. Ce jeton n'est conservé que le temps de la synchronisation.

## 4. Ce qui est conservé, et pourquoi

Tout ce qui suit vient des plateformes que vous avez liées, ou de ce que vous saisissez
dans l'application.

| Donnée | Origine | Pourquoi |
|---|---|---|
| Votre adresse e-mail | Apple, Google, ou vous | Vous reconnaître d'une session à l'autre |
| Identifiant SteamID64 | Steam | Vous relier à votre bibliothèque |
| Pseudo PlayStation | PlayStation | Vous relier à vos trophées |
| Pseudo RetroAchievements | RetroAchievements | Vous relier à vos succès |
| Pseudo Steam et image de profil | Steam | Afficher votre identité dans l'application |
| Liste de vos jeux, temps de jeu, date de dernière partie | Les plateformes liées | Prioriser ce qu'il vous reste à viser |
| Vos succès débloqués et leur date | Les plateformes liées | Le cœur de l'application |
| Vos hauts faits obtenus et leur date | Calculé | Votre collection de récompenses |
| Votre progression sur les succès à compteur | Steam et votre saisie | Afficher les barres de progression |
| Vos succès épinglés, leur ordre, et vos **notes libres** | Vous | Votre liste de chasse |
| Identifiant de transaction d'un achat | Apple ou Google | Empêcher qu'un même reçu débloque plusieurs comptes — voir section 9 |
| Le jeu que vous désignez comme actif | Vous | L'onglet « Chasse en cours » |
| Si votre profil Steam est public | Déduit | Vous expliquer pourquoi la synchronisation échoue |
| Dates de synchronisation | Système | Éviter de solliciter Steam inutilement |

**Les notes que vous écrivez sont du texte libre.** Elles ne sont lues par personne
d'autre que vous, mais évitez d'y mettre quoi que ce soit de sensible : ce champ n'est
pas prévu pour ça.

Le catalogue des jeux et des succès (noms, descriptions, icônes, rareté) est **partagé
entre tous les utilisateurs** et ne contient aucune donnée personnelle.

### Données techniques de connexion

Deux tables servent uniquement à sécuriser la connexion. Elles ne contiennent que des
**empreintes cryptographiques**, jamais de valeur utilisable, et leurs lignes expirent
automatiquement — deux minutes pour les codes d'échange, quinze minutes pour les défis de
connexion. Elles sont purgées ensuite.

### Ce que nous ne collectons pas

Ni votre position, ni vos contacts, ni votre carnet d'adresses, ni l'identifiant
publicitaire de votre appareil, ni la liste de vos autres applications, ni aucune donnée
biométrique. L'application ne demande **aucune permission système**.

## 5. Sur votre appareil

L'application conserve localement :

- votre choix de langue ;
- votre choix d'affichage des libellés de la barre d'onglets ;
- les jetons de votre session, pour ne pas vous redemander de vous connecter.

Désinstaller l'application efface tout cela. Cela **n'efface pas** les données conservées
sur le serveur — voir la section 8.

## 6. Avec qui ces données sont partagées

**Personne, au sens commercial.** Vos données ne sont ni vendues, ni louées, ni
transmises à des annonceurs ou à des courtiers en données.

Deux prestataires techniques interviennent nécessairement :

**Valve Corporation (Steam).** L'application interroge l'API publique de Steam et lit la
page de succès de votre profil communautaire. Votre SteamID est donc transmis à Steam —
qui le connaît déjà, puisque c'est le vôtre. Aucune autre donnée ne part vers Steam.
Consultez la politique de confidentialité de Steam pour ce qu'il en fait.

**Sony Interactive Entertainment (PlayStation).** Interrogé uniquement si vous avez lié
un compte PlayStation, avec le jeton de session que vous avez fourni.

**RetroAchievements.** Interrogé uniquement si vous avez lié un compte, avec votre pseudo
et votre clé d'API.

**Apple et Google**, si vous vous connectez par l'un d'eux : ils savent que vous utilisez
Eukleia, comme pour toute application où l'on se connecte ainsi.

**Supabase.** Héberge la base de données et les fonctions serveur, dans sa région
`eu-central-1` (**Francfort, Allemagne**). Vos données ne quittent pas l'Union
européenne.

### Vos amis, si vous en ajoutez

C'est le **seul cas où une autre personne voit vos données**, et il n'existe que si vous
le déclenchez vous-même.

L'application permet d'ajouter des amis et de se comparer à eux. **Il n'y a aucun
annuaire : personne ne peut vous trouver.** Une amitié ne se noue que si l'un de vous
crée un code d'invitation et le transmet à l'autre, qui le saisit. Le code vaut sept
jours et ne sert qu'une fois.

**Une amitié est réciproque, et ce qu'elle ouvre est large.** Un ami peut voir votre
pseudo et votre image, votre liste de jeux et votre progression, vos succès débloqués,
vos hauts faits, et votre score au classement. **Vos notes libres ne sont jamais
partagées.**

**Vous pouvez retirer un ami à tout moment**, depuis l'écran Amis. L'accès est coupé
immédiatement et **dans les deux sens** : vous ne voyez plus ses données, il ne voit plus
les vôtres.

N'ajoutez donc que des personnes à qui vous acceptez de montrer votre activité de jeu.

## 7. Notifications

L'application **n'envoie aucune notification** et ne collecte aucun jeton de notification.

Rien dans la base ne peut en stocker : la table qui l'aurait permis existait sans qu'aucun
code ne l'écrive ni ne la lise, et elle a été supprimée le 18 août plutôt que laissée à
dormir.

## 8. Vos droits, et comment les exercer

Le RGPD vous donne un droit d'accès, de rectification, d'effacement, de limitation, et
d'opposition.

**L'effacement est immédiat et intégral, depuis l'application** : Profil → Réglages →
« Supprimer mon compte ». Une confirmation est demandée, puis tout est supprimé — votre
profil, votre bibliothèque, vos succès, votre liste de chasse, vos notes, vos hauts faits
et vos amitiés. **C'est irréversible et il n'existe aucun export préalable.**

**Vos amitiés partent dans les deux sens** : vous disparaissez aussi des classements de
ceux qui vous avaient ajouté, sans qu'ils aient rien à faire.

Vos succès restent évidemment sur Steam, PlayStation et RetroAchievements ; nous n'y
touchons pas, et supprimer votre compte Eukleia n'a aucun effet sur eux.

Se déconnecter n'efface rien : cela ferme seulement la session sur l'appareil.

Pour l'accès, la rectification ou toute autre demande, écrivez à
**contact@demoos.fr**.

Vous pouvez également introduire une réclamation auprès de la CNIL (www.cnil.fr).

## 9. Combien de temps ces données sont conservées

Tant que votre compte existe. Elles sont supprimées **immédiatement** lorsque vous
supprimez votre compte, sans période de rétention ni copie de sauvegarde conservée à
cette fin.

Les données techniques de connexion (section 4) expirent en quelques minutes.

### La seule exception : les identifiants de transaction d'achat

Si vous achetez le déblocage à vie, nous conservons l'**identifiant de transaction**
émis par Apple ou Google — jamais votre reçu, jamais un moyen de paiement, que nous ne
voyons à aucun moment. Cette ligne **survit à la suppression de votre compte**, mais
elle en est **détachée** : le lien vers votre compte est effacé, et il ne reste qu'un
identifiant émis par le magasin, qui ne désigne plus personne dans notre base.

**Pourquoi cette exception existe.** Un reçu d'achat est un jeton au porteur : le
vérifier auprès d'Apple prouve qu'il est authentique, pas qu'il vous appartient. Si
nous effacions cette ligne avec votre compte, le même reçu pourrait être présenté par
un autre compte — ou par vous-même après avoir recréé le vôtre — et débloquer
l'application autant de fois qu'on le voudrait. La suppression de compte deviendrait un
outil de fraude.

**Conséquence à connaître, et nous préférons l'écrire :** si vous supprimez votre compte
puis en recréez un, **votre achat ne pourra pas être restauré ici**. Nous ne savons pas
distinguer un ancien acheteur d'un tiers présentant son reçu, et nous avons choisi de
nous tromper du côté du refus. Un achat perdu de cette façon se règle avec Apple ou
Google, qui eux savent qui a payé.

La base légale de cette conservation est l'**intérêt légitime** à prévenir la fraude,
que le RGPD reconnaît expressément.

## 10. Enfants

L'application n'est pas destinée aux enfants de moins de 13 ans et ne collecte
sciemment aucune donnée les concernant.

Aucun compte de plateforme de jeu n'est nécessaire pour l'utiliser. Les conditions d'âge
qui s'appliquent sont donc celles du moyen de connexion que vous choisissez — Apple,
Google ou une adresse e-mail — et, si vous les liez, celles de Steam, PlayStation et
RetroAchievements.

## 11. Modifications

Toute modification substantielle de ce document sera signalée par la mise à jour de la
date en tête de page. Ce document est publié à l’adresse https://demoosx.github.io/eukleia-legal/.
