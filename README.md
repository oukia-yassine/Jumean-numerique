# 🚀 Projet Génie Logiciel Agile — Application Java

Projet réalisé dans le cadre du module de **Génie Logiciel & Gestion de Projet Agile** à l'**ENSICAEN** (Spécialité Informatique).

---

## 📌 Présentation

Ce projet consiste en la conception et l'implémentation d'une application Java développée en équipe (7-8 ingénieurs) selon une méthodologie **Agile itérative et incrémentale** structurée en deux itérations majeurs (MVP 1 et MVP 2).

### 💡 Points Forts & Méthodologie
- **Gestion Agile / Scrum :** Organisation en 2 itérations de 3 séances, suivi des tâches via **GitLab Kanban** et carnets d'itérations (*Sprint Backlog*).
- **Conception Rigoureuse :** Analyse préalable des risques, diagrammes de cas d'utilisation UML et modélisation du domaine (diagramme de classes métier).
- **Qualité du Code & DevOps :** Respect des principes *Clean Code*, développement en *Pair Programming*, intégration continue via GitLab CI, revues de code strictes et couverture de tests unitaires ($\ge 30\%$).

---

## 🛠️ Roles au sein de l'Équipe

Le projet a été mené par une équipe plurisdisciplinaire :
- **Chef de Projet :** Coordination des activités, suivi Kanban, relation client.
- **Architecte Logiciel :** Conception UML, découpage en paquets et choix d'architecture.
- **Développeurs :** Implémentation des fonctionnalités métier et tests unitaires.
- **Responsable de Version / DevOps :** Intégration continue GitLab, garant du respect des tests et des revues de code.

---

## 🛠️ Stack Technique

- **Langage :** Java (JDK 17+)
- **IDE :** IntelliJ IDEA (Pair programming avec *Code With Me*)
- **Tests & Qualité :** JUnit / Mockito, Couverture de code
- **Forge & CI/CD :** GitLab (Kanban, Wiki, CI/CD pipelines, Code Reviews)
- **Modelisation :** UML (Cas d'utilisation, Diagramme de classes)

---

## 🔧 Structure du Dépôt

```text
.
├── src/
│   ├── main/java/       # Code source de l'application
│   └── test/java/       # Tests unitaires (JUnit)
├── docs/                # Maquettes, diagrammes UML & analyse des risques
├── .gitlab-ci.yml       # Pipeline d'intégration continue
└── README.md
