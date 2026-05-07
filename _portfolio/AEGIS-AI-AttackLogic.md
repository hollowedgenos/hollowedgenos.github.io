---
title: "AEGIS AI Attack Logic"
excerpt: "The AI attack logic designed for the melee and ranged enemies in AEGIS."

gallery:
  - url: /assets/images/portfolio-images/gallery/aegis-ai-logic/AEGIS_BP_Projectile&Melee.png
    image_path: /assets/images/portfolio-images/gallery/aegis-ai-logic/AEGIS_BP_Projectile&Melee.png
    alt: "Screenshot of Blueprint Actors (Part 1)"
    title: "Blueprint Classes for the Projectile & Melee-based enemies (Part 1)"
  - url: /assets/images/portfolio-images/gallery/aegis-ai-logic/AEGIS_BP&GO_Projectile&Melee2.png
    image_path: /assets/images/portfolio-images/gallery/aegis-ai-logic/AEGIS_BP&GO_Projectile&Melee2.png
    alt: "Screenshot of Blueprint Actors (Part 2)"
    title: "Blueprint Classes for the Projectile & Melee-based enemies (Part 2)"
  - url: /assets/images/portfolio-images/gallery/aegis-ai-logic/AEGIS_COMPONENTS.png
    image_path: /assets/images/portfolio-images/gallery/aegis-ai-logic/AEGIS_COMPONENTS.png
    alt: "Screenshot of Component Blueprints"
    title: "Component classes for the Range & Melee Enemy Attacks"
  - url: /assets/images/portfolio-images/gallery/aegis-ai-logic/AEGIS_COMP_HitAttack.png
    image_path: /assets/images/portfolio-images/gallery/aegis-ai-logic/AEGIS_COMP_HitAttack.png
    alt: "Screenshot of Event Graph "
    title: "Event Graph for the Melee Attack Component"
  - url: /assets/images/portfolio-images/gallery/aegis-ai-logic/AEGIS_COMP_RangeAttack.png
    image_path: /assets/images/portfolio-images/gallery/aegis-ai-logic/AEGIS_COMP_RangeAttack.png
    alt: "Screenshot of Event Graph "
    title: "Event Graph for the Range Attack Component"
  - url: /assets/images/portfolio-images/gallery/aegis-ai-logic/AEGIS_ENEMIES.png
    image_path: /assets/images/portfolio-images/gallery/aegis-ai-logic/AEGIS_ENEMIES.png
    alt: "Screenshot of Enemy Blueprints"
    title: "Blueprint Classes for the Range & Melee Enemies (Models: Stone Golem - buxoided, Paragon: Sevarog - Epic Games)"
  - url: /assets/images/portfolio-images/gallery/aegis-ai-logic/AEGIS_EXO_MeleeEnemy.png
    image_path: /assets/images/portfolio-images/gallery/aegis-ai-logic/AEGIS_EXO_MeleeEnemy.png
    alt: "Screenshot of Enemy Event Graph"
    title: "Event Graph for the Melee Enemy Class"
  - url: /assets/images/portfolio-images/gallery/aegis-ai-logic/AEGIS_EXO_RangedEnemy.png
    image_path: /assets/images/portfolio-images/gallery/aegis-ai-logic/AEGIS_EXO_RangedEnemy.png
    alt: "Screenshot of Enemy Event Graph"
    title: "Event Graph for the Ranged Enemy Class"
  - url: /assets/images/portfolio-images/gallery/aegis-ai-logic/AEGIS_EnemyShield_EventGraph.png
    image_path: /assets/images/portfolio-images/gallery/aegis-ai-logic/AEGIS_EnemyShield_EventGraph.png
    alt: "Screenshot of Enemy Shield Event Graph"
    title: "Event Graph for the Ranged Shield"
  - url: /assets/images/portfolio-images/gallery/aegis-ai-logic/AEGIS_EnemyShield_ConstructionScript.png
    image_path: /assets/images/portfolio-images/gallery/aegis-ai-logic/AEGIS_EnemyShield_ConstructionScript.png
    alt: "Screenshot of Enemy Shield Construction Script"
    title: "Construction Script for the Ranged Shield"

header:
  overlay_image: 
  teaser: /assets/images/portfolio-images/AEGIS-COMP-HitAttack.png
  overlay_filter: 0.5

project_brief: "The general AI Attack logic for the Ranged and Melee enemies of the AEGIS project, created in Unreal Engine 5. "
project_role: "Responsible for creating base classes for the ranged and melee enemies as well as the components comprising their specific attack logic."
project_tools: "None"
project_date: "2026"
---

## Specifics
Besides creating the base enemy classes, the creation of logic each enemy type could utilize was implemented.

Melee enemies were fitted with actor components which dictated the logic of their melee attack. 

Ranged enemies had two actor components, a ranged projectile attack which could draw from multiple different projectile patterns and a shield that blocked a limited amount of damage.

Each of these components interfaced into the AI's behavior tree as a task. 

## External Assets & Libraries
- None

---

### Resources
- [AEGIS Attack Logic Github](https://github.com/hollowedgenos/UC_AEGIS_AI_Attack_Logic)
- [AEGIS Project](https://jaydenyounger.itch.io/aegis)

---

### Gallery

{% include gallery %}