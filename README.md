# JPA – Introduction et mise en œuvre

🔗 **Cours associé :**
[https://stahe.github.io/jpa-juin-2007/](https://stahe.github.io/jpa-juin-2007/)

---

## Présentation

Ce document propose une découverte des concepts fondamentaux de la **persistance de données avec l’API JPA (Java Persistence API)**.

Après étude et expérimentation des exemples proposés, le lecteur dispose des bases nécessaires pour utiliser JPA de manière autonome.

JPA est apparue avec **Java 5 (JDK 1.5)** et s’inscrit dans une architecture logicielle multi-couches.

---

## Architecture multi-couches

Le document s’appuie sur une architecture classique en trois couches :

* **[ui]** — Interface utilisateur (Swing, console, web)
* **[metier]** — Logique métier
* **[dao]** — Accès aux données persistantes
* **[JDBC]** — Accès bas niveau à la base de données

L’objectif de JPA est de standardiser et simplifier la couche **DAO**.

---

## ORM et standardisation

Avant JPA, des solutions comme **Hibernate** ou **Toplink** proposaient des mécanismes ORM (Object Relational Mapping).

JPA introduit une **spécification standard** :

* La couche DAO dialogue avec une **interface JPA**
* L’implémentation peut être Hibernate, Toplink, etc.
* Le code métier reste indépendant du fournisseur ORM

---

## Notions abordées

Le document traite notamment :

### 1️⃣ Mapping relationnel / objet

Configuration via annotations Java 5 pour gérer :

* Relations **un à un**
* Relations **un à plusieurs**
* Relations **plusieurs à plusieurs**

---

### 2️⃣ Environnement Java SE

* Applications console de test
* Manipulation directe de l’API JPA
* Découverte des principales méthodes (CRUD)

---

### 3️⃣ Architecture multi-couches avancée

Intégration de :

* **Spring**
* **JBoss EJB3**

Utilisation de :

* Pools de connexions
* Gestionnaires de transactions
* Injection de dépendances
* POJO annotés

---

### 4️⃣ Exemple d’application web

Le document se termine par une application web trois couches intégrant :

* Web
* Métier
* DAO
* JPA
* Implémentation ORM
* Infrastructure Spring

---

## Objectif pédagogique

Ce support vise à :

* Comprendre le rôle de JPA dans une architecture d’entreprise
* Maîtriser le mapping relationnel / objet
* Utiliser JPA en environnement SE et EE
* Comparer Spring et EJB3 pour la gestion des services techniques

---

## Public cible

Développeurs Java souhaitant :

* Comprendre les bases de la persistance avec JPA
* Structurer proprement une architecture multi-couches
* Préparer une montée en compétence vers Java EE

---

## Auteur

**Serge Tahé** – Juin 2007

---
