# Plateforme Intégrée de Suivi et de Gestion des Opérations Électorales
## Écosystème Complet Next.js 14, React 18, TypeScript & Tailwind CSS

Cette application unifiée regroupe désormais les 3 composantes majeures du système :

1. **La Présentation Institutionnelle & Exécutive (17 Diapositives 16:9)** à la racine `/` :
   * Rigueur typographique suisse, zéro icône, zéro fond de texte, maillage 350 électeurs.
   * Navigation clavier (`←` / `→` / `Espace`), mode plein écran (`F`), export PDF 16:9 (`P`) et sommaire (`O`).
2. **Le Tableau de Bord Décisionnel Interactif** à l'URL `/dashboard` :
   * Conçu d'après la maquette de référence :
   * **Sidebar souveraine** (configurable en Rouge Carmin `#BF0302` ou Bleu Nuit `#0F1E36`).
   * **5 Cartes d'indicateurs (KPIs)** : Bureaux concernés (450), Résultats reçus (368 - 82%), En attente (52 - 12%), À vérifier (30 - 7%), Mandataires actifs (125).
   * **Couverture Territoriale d'Haïti** : Carte interactive stylisée (Département de l'Ouest, Delmas, Carrefour, Artibonite, Nord, Sud) avec repères de statut vert/orange/gris.
   * **Évolution des Transmissions** : Graphique d'avancement chronologique avec filtres temporels (7j, 30j, 90j).
   * **Résultats par Compétiteur** : Diagramme circulaire Donut (Compétiteur A : 48.5%, Compétiteur B : 32.7%, Compétiteur C : 18.8%).
   * **Fil d'Activité Récente en Direct** : Relevé minute par minute (Delmas, Carrefour, etc.).
   * **File des Incidents Juridiques** : Alerte de retard et problèmes matériels avec niveaux de sévérité.
3. **Le Portail de Connexion Sécurisé** à l'URL `/login` :
   * Vagues fluides institutionnelles, urne électorale 3D et carte de connexion avec emblème républicain.
   * Sélecteur de profil instantané (*Direction du Parti*, *Mandataire 350*, *Pôle Juridique*, *Super Admin*).

---

### Démarrage Rapide

Pour lancer l'application :
```bash
npm run dev
```
* **Présentation (17 slides) :** [http://localhost:3000](http://localhost:3000)
* **Tableau de Bord Exécutif :** [http://localhost:3000/dashboard](http://localhost:3000/dashboard)
* **Portail de Connexion :** [http://localhost:3000/login](http://localhost:3000/login)

Pour le build de production :
```bash
npm run build
npm start
```
