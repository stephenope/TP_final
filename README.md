**Sujet de TP : Déploiement d'un projet Quarkus "Superhero" sur OpenShift à l'aide de Docker Compose**

---

### **Contexte**
Vous allez travailler sur le déploiement du projet **"Superhero"** basé sur Quarkus. Ce projet doit être déployé sur un cluster **OpenShift** en utilisant **Docker Compose** comme point de départ pour la configuration des conteneurs `deploy/docker-compose/native.yml`.

L'objectif de ce TP est d'apprendre à transformer une application fonctionnant localement avec Docker Compose pour qu'elle fonctionne sur une plateforme cloud-native telle qu'OpenShift. Vous devrez adapter les fichiers de configuration, créer les ressources nécessaires sur OpenShift et assurer la portabilité de l'application.

---

### **Objectifs pédagogiques**
- Comprendre les différences entre le déploiement local avec Docker Compose et le déploiement sur OpenShift.
- Créer et adapter des **manifests OpenShift (YAML)**.
- Convertir un **docker-compose.yml** en **ressources OpenShift (Deployment, Services, Routes, Secrets, ConfigMaps, etc.)**.
- Déployer une application Quarkus sur OpenShift.
- Gérer les **volumes persistants**, les **routes** et la **gestion des secrets**.
- Exposer l'application via une URL publique.

---

### **Prérequis**
- Connaissance de base de **Quarkus**, **Docker Compose** et **OpenShift**.
- Outil **oc (OpenShift CLI)** installé.
- Accès à un cluster **OpenShift**.
- Dossier du projet **Superhero** fourni par l'utilisateur.

---

### **Matériel fourni**
- Le dossier du projet **Superhero** contenant le code source et le fichier **docker-compose.yml**.
- Les instructions d'accès au cluster OpenShift.
- L'accès au fichier de modèle de **Dockerfile** (si nécessaire).

