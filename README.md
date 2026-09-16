# Cours IA souveraine

Support de cours pour comprendre l'IA, installer un poste de travail multi-modèle et ne jamais dépendre d'un seul fournisseur.

Deux documents autonomes, sans dépendance ni build : il suffit d'un navigateur.

## Contenu

| Fichier | Rôle |
|---|---|
| [`index.html`](index.html) | **Diaporama** — 68 slides. Comprendre l'IA (poids, entraînement, distillation, tokens, contexte), les 4 briques d'un agent (`.md`, skills, hooks, MCP), le garde-fou (tests, ADR), Obsidian, Graphify, OpenCode, OpenDesign et la revue multi-IA. |
| [`guide-installation.html`](guide-installation.html) | **Guide d'installation** — commandes pas à pas pour Windows, Linux et macOS, configurations, prompts prêts à copier-coller et checklist finale. |

## Utilisation

Ouvrir directement dans le navigateur :

```bash
# Windows (PowerShell)
start index.html

# macOS
open index.html

# Linux
xdg-open index.html
```

Ou servir le dossier localement :

```bash
python -m http.server 8000
# puis http://localhost:8000/index.html
```

Le guide est complémentaire au diaporama : chaque section correspond à une partie du cours.

### Navigation dans le diaporama

- `→` ou `Espace` : slide suivante · `←` : slide précédente
- `Home` ou `R` : revenir au début · `End` : dernière slide
- Clic sur la moitié gauche / droite de l'écran : naviguer
- Points en bas de page : accès direct à une slide

## Périmètre couvert

Obsidian · Graphify · Ollama (modèles locaux) · OpenCode (CLI + Desktop) · agent « auto » · MCP Obsidian · [ai-native-dev-stack](https://github.com/Rwanbt/ai-native-dev-stack) · OpenDesign

## Sources

- ai-native-dev-stack — <https://github.com/Rwanbt/ai-native-dev-stack>
- OpenCode — <https://opencode.ai>
- Obsidian — <https://obsidian.md>

Les noms de modèles, prix, quotas et commandes évoluent vite : les chiffres cités reflètent l'état relevé fin août 2026 et doivent être revérifiés avant une session collective.
