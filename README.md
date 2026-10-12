# TPS JEE - JPA / Hibernate

### 1. Création de la table
![Création de la table](screenshots/01_creation_table.png)

Génération et exécution automatique du script DDL par Hibernate pour la création de la table `Produit`.

---

### 2. Insertion des produits
![Insertion des produits](screenshots/02_insertion_produits.png)

Exécution des requêtes SQL `INSERT` par Hibernate et confirmation de l'insertion des produits en base de données.

---

### 3. Affichage et recherche des produits
![Affichage et recherche des produits](screenshots/03_affichage_produits.png)

Affichage de la liste des produits récupérés via JPQL et résultat de la recherche d'un produit spécifique par son identifiant (ID = 2).

---

### 4. Console H2
![Console H2](screenshots/04_console_h2.png)

Tentative d'accès à la table `PRODUIT` dans la console Web H2 après arrêt de l'application (la table a été supprimée suite à la fermeture de l'EntityManagerFactory configuré en `create-drop`).