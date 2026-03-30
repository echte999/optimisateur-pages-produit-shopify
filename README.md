# Optimisateur de Pages Produit Shopify

Workflow n8n qui optimise automatiquement les pages produit d'une boutique Shopify avec l'IA.

## Ce que fait ce workflow

1. Récupère la liste des produits Shopify
2. Pour chaque produit, génère via **Claude Sonnet 4** :
   - Un titre optimisé SEO
   - Une description HTML convaincante
   - Des balises (tags) pertinentes
3. Met à jour le produit directement dans Shopify

## Stack

- [n8n](https://n8n.io) — orchestration du workflow
- [Claude Sonnet 4](https://anthropic.com) (Anthropic) — génération de contenu IA
- Shopify API — lecture et mise à jour des produits

## Installation

1. Importer `workflow.json` dans votre instance n8n
2. Configurer les credentials :
   - **Shopify** : clé API de votre boutique
   - **Anthropic** : clé API Claude
3. Exécuter manuellement ou planifier selon vos besoins

## Auteur

[Jared](https://github.com/99Jared9) — Consultant automatisation & IA
