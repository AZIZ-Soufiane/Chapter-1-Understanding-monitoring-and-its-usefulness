# 🗂️ Mini-Veille Technologique — Déploiement Web

## 🧩 Sujet exploré
**Déploiement d’applications web modernes**

---

## ❓ Découverte principale
Le déploiement web consiste à transférer une application d'un environnement de développement vers un serveur de production pour la rendre accessible aux utilisateurs. Cela implique de choisir une infrastructure adaptée (PaaS, VPS, ou Serverless), de configurer le réseau, et d'assurer la sécurité des données.

---

## 🛠️ Pourquoi ce sujet est utile
Comprendre le déploiement est crucial pour :
- **Rendre le code vivant** : Une application n'a de valeur que si elle est accessible.
- **Automatisation (CI/CD)** : Réduire les erreurs humaines lors des mises à jour.
- **Scalabilité** : Savoir adapter l'infrastructure à la montée en charge.
- **Performance** : Optimiser les temps de chargement via des serveurs proches des utilisateurs (Edge).

---

## 🚀 Meilleures plateformes et outils

### ⚡ Plateformes PaaS (Platform as a Service) - Idéal pour la rapidité
- **Vercel / Netlify** – Leaders pour le frontend et les architectures Jamstack/Serverless. Déploiement automatique via Git.
- **Railway / Render** – Excellents pour les applications backend (Node.js, Python, PHP) avec gestion simplifiée des bases de données.

### ☁️ Infrastructure Cloud & VPS - Idéal pour le contrôle
- **DigitalOcean** – VPS (Droplets) abordables et simples à configurer pour un contrôle total.
- **AWS / Google Cloud / Azure** – Pour les besoins complexes nécessitant une infrastructure massivement scalable.

### 🔄 DevOps & Automatisation
- **GitHub Actions / GitLab CI** – Pour automatiser les tests et le déploiement à chaque "push".
- **Docker** – Pour isoler l'application et garantir qu'elle fonctionne partout de la même manière.

---

## 💡 Bonnes pratiques
- **Variables d'environnement** : Ne jamais stocker de secrets (clés API, mots de passe) dans le code.
- **Zero Downtime Deployment** : Utiliser des techniques pour mettre à jour sans couper le service.
- **Monitoring** : Suivre l'état du serveur pour agir avant que les utilisateurs ne voient de crash.

---

## 🧪 Atelier pratique – Question de veille

| Étape | Ma réponse |
| :--- | :--- |
| **Thème** | Déploiement d'applications web |
| **Problème** | Choisir entre la rapidité des services managés (PaaS) et le contrôle/coût des serveurs dédiés (VPS). |
| **Résultat attendu** | Un guide de décision illustré par des tests de déploiement sur Vercel et DigitalOcean. |
| **Question finale** | **Comment choisir entre un hébergement PaaS et un VPS pour optimiser le ratio coût/performance d'un projet web ?** |

---

## 💼 Livrable attendu : Fiche "Question de veille"

- **Thème choisi** : Déploiement Web.
- **Question rédigée** : Comment choisir entre un hébergement PaaS et un VPS pour optimiser le ratio coût/performance d'un projet web ?
- **Résultat attendu** : Une synthèse comparative avec des critères de choix (coût, maintenance, scalabilité).
- **Première source** : [MDN Web Docs - Deploying a website](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/Publishing_your_website)

---

## ✍️ Phrase de synthèse
Le déploiement moderne s'oriente vers l'automatisation totale et l'abstraction de l'infrastructure via le Serverless et le PaaS, permettant aux développeurs de se concentrer sur le code plutôt que sur la gestion des serveurs.
