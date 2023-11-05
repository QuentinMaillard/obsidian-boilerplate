---
up:
  - "[[• Accueil]]"
---
# 😌 Intention

Cet *espace* est dédié à **contenir mes projets, rangés par domaine d'activités de mon quotidien (freelance, projets scolaire, voyage, etc).**

Il m'aide à **garder une vision claire des choses que j'ai à faire.**

# 👀 Projets en cours
- [[200 Activités/220. Projets scolaires/Méthodologie de veille • Article à écrire/• Index|Article de veille]]
- [[200 Activités/210. Dev/Freelance • E-commerce random/• Index|E-commerce]]

# ✅ Détection des tâches
```dataview
TASK
WHERE contains(file.folder, this.file.folder) AND !fullyCompleted
GROUP BY file.folder
```
