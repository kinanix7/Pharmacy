
---

# 💊 Pharmacie REST API - Spring Boot

## 📌 Contexte du projet

Dans le cadre de l’ouverture d’une nouvelle pharmacie dans le quartier, une solution efficace de gestion de stock est indispensable. Ce projet consiste à développer une **API REST** avec **Spring Boot** pour permettre au fondateur de gérer facilement les produits en stock, avec les fonctionnalités de base (CRUD) : ajout, modification, suppression et consultation des produits.

---

## 🧾 Fonctionnalités

* ✅ **Ajouter** de nouveaux produits (nom, prix, quantité, description — identifiant généré automatiquement)
* ✅ **Modifier** les informations d’un produit existant
* ✅ **Supprimer** un produit de la base de données
* ✅ **Consulter** la liste des produits disponibles

---

## ⚙️ Stack Technique

* Java 17
* Spring Boot
* Spring Data JPA
* Hibernate
* MySQL / PostgreSQL
* Lombok
* Postman (pour les tests)

---

## 🛠️ Installation & Exécution

1. **Cloner le repository**

   ```bash
   git clone https://github.com/ton-utilisateur/pharmacie-api.git
   cd pharmacie-api
   ```

2. **Configurer la base de données**

   Dans `application.properties` :

   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/pharmacie_db
   spring.datasource.username=root
   spring.datasource.password=motdepasse
   ```

3. **Exécuter l’application**

   ```bash
   ./mvnw spring-boot:run
   ```

---

## 📬 Points d’entrée de l’API

| Méthode | Endpoint             | Description                 |
| ------- | -------------------- | --------------------------- |
| POST    | `/api/produits`      | Ajouter un produit          |
| GET     | `/api/produits`      | Lister tous les produits    |
| GET     | `/api/produits/{id}` | Consulter un produit précis |
| PUT     | `/api/produits/{id}` | Modifier un produit         |
| DELETE  | `/api/produits/{id}` | Supprimer un produit        |

---

## 🧪 Tests

* ✔️ Tous les endpoints sont testés avec **Postman**
* 👉 Voir la collection : [Lien vers la collection Postman](https://www.postman.com/...)

---

## 📅 Gestion de projet

* 📋 Planning Trello : [Lien vers Trello](https://trello.com/...)

---

## 🧠 Modalités pédagogiques

* Travail individuel (5 jours)
* Présentation : 20 minutes (10 min démo + 10 min Q/R)
* Livraison finale : 09/05/2025 à 23h59

---

## ✅ Critères de réussite

* Fonctionnalités CRUD complètes et opérationnelles
* Bonne utilisation de Spring Boot, JPA, Lombok
* Gestion propre des exceptions
* Tests avec Postman
* Livraison à temps

---

## 🙋‍♂️ Auteur

Développé par **Youness** dans le cadre de la formation « Développement Web - Simplon ».

---

