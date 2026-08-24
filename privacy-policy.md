# Politique de confidentialité — FacturePro

**Version 1.0 — Août 2026**

---

## 1. Présentation

FacturePro est une application de bureau (logiciel installé localement sur votre ordinateur) destinée à la gestion de la facturation des auto-entrepreneurs soumis au régime BNC (Bénéfices Non Commerciaux).

Cette politique de confidentialité décrit la nature des données traitées par l'application, leurs conditions de stockage et vos droits.

---

## 2. Responsable du traitement

L'application FacturePro est un outil autonome. Le responsable du traitement des données est **l'utilisateur lui-même**, qui installe et exploite l'application sur son propre matériel informatique.

---

## 3. Données traitées

### 3.1 Données saisies par l'utilisateur

L'application traite uniquement les données que vous saisissez volontairement :

| Catégorie | Exemples |
|-----------|----------|
| **Données de l'entreprise** | Nom ou raison sociale, adresse, SIRET, téléphone, email |
| **Données clients** | Nom, adresse postale, téléphone (personnes morales ou physiques) |
| **Données de facturation** | Références de factures et devis, descriptions de prestations, montants, dates |

### 3.2 Données NON collectées

FacturePro **ne collecte, ne transmet et ne partage aucune donnée** :

- ✗ Aucune connexion à internet (sauf pour le chargement initial de la librairie PDF)
- ✗ Aucun serveur distant, aucun compte utilisateur
- ✗ Aucune télémétrie, aucun suivi d'utilisation
- ✗ Aucune publicité, aucun cookie
- ✗ Aucune donnée envoyée à un tiers

---

## 4. Lieu de stockage des données

Toutes les données sont stockées **exclusivement sur votre ordinateur**, dans un fichier local :

- **Windows** : dans le dossier d'installation de l'application (`data.json`)
- **macOS** : dans le dossier d'installation de l'application (`data.json`)

Ce fichier n'est accessible que par vous et les personnes ayant accès à votre session Windows.

**Aucune sauvegarde automatique n'est effectuée dans le cloud.** Il vous appartient de sauvegarder ce fichier régulièrement.

---

## 5. Durée de conservation

Les données sont conservées tant que l'application est installée sur votre ordinateur. Elles sont supprimées :

- Lorsque vous désinstallez l'application (si vous choisissez de supprimer les données lors de la désinstallation)
- Lorsque vous supprimez manuellement le fichier `data.json`

---

## 6. Base légale du traitement (RGPD)

Le traitement de données dans FacturePro repose sur :

- **L'exécution d'un contrat** (art. 6.1.b du RGPD) : la facturation est nécessaire à l'exercice de votre activité professionnelle
- **L'obligation légale** (art. 6.1.c du RGPD) : la conservation des factures est imposée par le Code de commerce (10 ans) et le Code général des impôts

---

## 7. Données des clients et tiers

Si vous saisissez dans l'application des données relatives à vos clients (personnes physiques), vous êtes vous-même responsable du traitement de ces données au sens du RGPD.

À ce titre, vous êtes tenu :

- D'informer vos clients de l'utilisation de leurs données à des fins de facturation
- De ne pas conserver leurs données au-delà des durées légales
- De répondre à leurs demandes d'accès, de rectification ou d'effacement

---

## 8. Sécurité

Les données stockées dans `data.json` ne sont pas chiffrées. Il est recommandé de :

- Protéger votre session Windows par un mot de passe
- Chiffrer votre disque dur (via BitLocker sur Windows)
- Sauvegarder régulièrement le fichier `data.json` dans un emplacement sécurisé

---

## 9. Vos droits (RGPD)

Conformément au Règlement Général sur la Protection des Données (UE 2016/679), vous disposez des droits suivants sur vos données :

- **Droit d'accès** : vos données sont directement accessibles dans l'application et dans le fichier `data.json`
- **Droit de rectification** : vous pouvez modifier vos données à tout moment dans l'application
- **Droit à l'effacement** : vous pouvez supprimer vos données directement dans l'application ou en supprimant `data.json`
- **Droit à la portabilité** : le fichier `data.json` est au format JSON standard, lisible et exportable

Ces droits s'exercent directement dans l'application, sans intermédiaire.

---

## 10. Librairie tierce — jsPDF

Pour la génération des documents PDF, l'application utilise la librairie open source **jsPDF** (licence MIT), chargée depuis le réseau CDN cdnjs.cloudflare.com lors du premier lancement.

- Cette librairie ne collecte aucune donnée de votre facturation
- Elle fonctionne entièrement dans votre navigateur/application locale
- Après le premier chargement, aucune connexion n'est nécessaire

---

## 11. Modifications de cette politique

Cette politique peut être mise à jour lors des nouvelles versions de l'application. La date de version figure en en-tête du document.

---

## 12. Contact

Pour toute question relative à cette politique de confidentialité, contactez le développeur de l'application via la page de téléchargement sur laquelle vous avez obtenu FacturePro.

---

*FacturePro — Application locale de facturation pour auto-entrepreneurs BNC*
*Aucune donnée ne quitte votre ordinateur.*
