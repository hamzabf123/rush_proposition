# Spécifications de Prestations (PRD) - Projet RU$H

## 1. Énoncé du Problème
Les fast-foods indépendants, les snacks et les petits acteurs de la restauration rapide sont actuellement mal desservis par le marché de la digitalisation. Ils se retrouvent souvent coincés entre deux extrêmes :
- Des solutions globales (type Bill-App ou usines à gaz) qui sont trop complexes, coûteuses et imposent un cycle de vente long et inadapté.
- Des solutions "low-cost" trop simplistes qui n'offrent ni fiabilité ni accompagnement humain.
Ces petits acteurs ont un besoin vital de moderniser leur prise de commande (bornes, click & collect) de manière **simple, accessible et extrêmement rapide**, sans transformer de fond en comble leur organisation.

## 2. Objectifs et Indicateurs de Succès (KPIs)

### Objectifs Commerciaux et Produit
- **Acquisition rapide :** Transformer le site web en une véritable machine de conversion pour capter le trafic issu des réseaux sociaux (TikTok, Instagram).
- **Simplicité de l'offre :** Proposer un "Bundle" standardisé (Borne de commande + Web App + Fidélité) sans les modules lourds (ex: drive ou caisse complète).
- **Raccourcissement du cycle de vente :** Permettre une décision et une souscription rapides, sans nécessiter de longs rendez-vous commerciaux.

### Indicateurs de Succès (KPIs)
- **Taux de conversion global :** Transformer au moins 5% du trafic qualifié en souscription.
- **Temps de checkout (Friction UX) :** Moins de 3 minutes pour finaliser le processus de facturation et de souscription en ligne.
- **Vitesse du site (Performance) :** Temps de chargement (LCP) inférieur à 2 secondes (essentiel pour le trafic mobile TikTok/Insta).
- **Time-to-Value (Déploiement) :** Installation physique de la solution chez le client en moins d'une semaine après souscription.

## 3. Personas Cibles

### 👤 Persona 1 : Samir, "L'Exploitant Pressé"
- **Profil :** Gérant de snack, les mains dans le cambouis tous les jours. N'a pas le temps pour les réunions techniques.
- **Besoin :** Une borne prête à l'emploi qui marche immédiatement, un prix fixe sans surprise, et un support humain qui décroche s'il y a un souci.
- **Critère de décision :** Clarté de l'offre et rapidité d'installation.

### 👤 Persona 2 : Léa, "La Nouvelle Entrepreneuse"
- **Profil :** Lance son premier concept de fast-food. Elle cherche des solutions modernes sur les réseaux sociaux. Budget calculé, elle a besoin d'un fort retour sur investissement (ROI) rapide.
- **Besoin :** Augmenter son ticket moyen avec une borne et une web app sans investir le budget d'une grande franchise.
- **Critère de décision :** Le rapport qualité/prix et la modernité de la solution.

## 4. Exigences Fonctionnelles Détaillées

### 4.1. Landing Page et Interface (Machine d'Acquisition)
- **Mobile First :** Le site doit être parfaitement optimisé pour les smartphones (90% du trafic cible).
- **Hero Section Impactante :** Une proposition de valeur lisible en moins de 3 secondes avec un Call-To-Action (CTA) bien visible (ex: "Déployer ma borne").
- **Simulateur de Rentabilité / Bundle :** Un module interactif simple permettant à l'utilisateur de sélectionner l'offre (SaaS seul ou Bundle complet) et de voir le tarif final.
- **Preuve Sociale et Rassurance :** Présence du badge "powered by Bill-App" et d'avis clients pour asseoir la crédibilité sans alourdir le message.

### 4.2. Processus de Facturation Principal (Checkout)
- **Étape 1 - Sélection :** Résumé clair de ce qui est inclus et exclus dans l'abonnement.
- **Étape 2 - Informations :** Formulaire raccourci (auto-complétion de l'adresse du restaurant via API, SIRET, etc.).
- **Étape 3 - Paiement :** Intégration d'un module de paiement fluide (ex: Stripe) pour la mise en place de l'abonnement SaaS.
- **Transparence totale :** Aucun frais caché, le prix d'installation et l'abonnement mensuel doivent être affichés clairement avant l'étape de paiement.

### 4.3. Espace Post-Achat & Onboarding
- **Confirmation immédiate :** Message de succès rassurant validant la commande.
- **Prise de Rendez-vous Automatisée :** Module permettant de bloquer un créneau directement en ligne avec un technicien pour la livraison/installation.

### 4.4. Exigences Techniques et Performances
- **Stack Technologique :** Utilisation de **Tailwind CSS** pour l'interface afin de garantir un code modulaire, léger et une identité visuelle moderne.
- **Accessibilité :** Respect des normes d'accessibilité (contrastes, tailles de police) pour assurer une navigation sans effort à des professionnels pressés.
- **Tracking :** Intégration des pixels de conversion (TikTok, Meta) pour remonter les événements d'achat (checkout) aux campagnes publicitaires.
