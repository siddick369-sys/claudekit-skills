# CLAUDE.md - Skills Reference

Ce projet contient des skills ClaudeKit pour Claude Code. Voici les skills recommandees par domaine.

## Developpement Web (Frontend + Backend)

- **web-frameworks** - Next.js (App Router, RSC, SSR, SSG, ISR), Turborepo, RemixIcon
- **frontend-development** - React/TypeScript, Suspense, lazy loading, TanStack Router, MUI v7
- **frontend-design** - Interfaces production-grade avec design distinctif
- **ui-styling** - shadcn/ui, Tailwind CSS, Radix UI, dark mode, design systems
- **aesthetic** - Principes de design, hierarchie visuelle, micro-interactions
- **threejs** - Applications 3D avec Three.js (WebGL/WebGPU), shaders, VR/XR
- **backend-development** - Node.js, Python, Go, Rust, NestJS, FastAPI, Django, REST/GraphQL/gRPC
- **databases** - MongoDB, PostgreSQL, schemas, migrations, optimisation
- **better-auth** - Authentification TypeScript (OAuth, 2FA, passkeys, multi-tenancy)
- **web-testing** - Playwright, Vitest, k6 (E2E, unit, load, a11y, visual)
- **chrome-devtools** - Automatisation navigateur, screenshots, scraping avec Puppeteer

## Developpement Mobile

- **frontend-development** - Patterns React applicables a React Native
- **ui-styling** - Tailwind CSS (via NativeWind pour mobile), composants accessibles
- **backend-development** - APIs backend pour apps mobiles (REST, GraphQL, auth)
- **web-testing** - Tests cross-platform et mobile gestures
- **payment-integration** - Integration paiements (Stripe, Paddle) pour apps mobiles

## DevOps & Deploiement en ligne

- **devops** - Cloudflare (Workers, R2, D1, Pages), Docker, GCP (Cloud Run, GKE, Compute Engine), Kubernetes, CI/CD, GitOps
- **databases** - PostgreSQL/MongoDB en production, replication, sharding, backups
- **backend-development** - Docker, Kubernetes, CI/CD pipelines, monitoring, securite OWASP

## Developpement Agent IA

- **context-engineering** - Architecture d'agents IA, gestion du contexte, optimisation tokens, memoire, multi-agent
- **google-adk-python** - Google Agent Development Kit, orchestration multi-agents, workflows (sequentiel, parallele, boucle)
- **ai-multimodal** - Google Gemini API pour audio, images, videos, documents (contexte 2M tokens)
- **claude-code** - Guide complet Claude Code (hooks, plugins, MCP, skills)
- **mcp-builder** - Creation de serveurs MCP en Python (FastMCP) ou TypeScript
- **mcp-management** - Gestion des serveurs MCP, decouverte d'outils, execution
- **sequential-thinking** - Raisonnement systematique etape par etape pour problemes complexes

## Creation de documents Word et PDF

- **document-skills/docx** - Creation/edition de documents Word, suivi des modifications, commentaires, mise en forme
- **document-skills/pdf** - Extraction texte/tableaux, creation PDF, fusion/separation, formulaires (pypdf)
- **document-skills/pptx** - Presentations PowerPoint, layouts, animations, notes
- **document-skills/xlsx** - Tableurs Excel, formules, analyse de donnees, visualisation

## Generation d'images et multimedia

- **ai-multimodal** - Generation d'images (text-to-image, editing, composition) via Google Gemini API
- **media-processing** - FFmpeg (video/audio), ImageMagick (manipulation images, conversion, effets, batch)
- **aesthetic** - Principes de design pour creer des visuels de qualite
- **mermaidjs-v11** - Diagrammes (flowcharts, sequence, ER, Gantt, architecture) en Mermaid.js v11
- **threejs** - Visualisations 3D, scenes interactives, rendus WebGL

## Outils complementaires

- **debugging** - Frameworks de debugging systematique (root cause, defense-in-depth, verification)
- **problem-solving** - Techniques de resolution (inversion, patterns, simplification)
- **code-review** - Revue de code, validation avant completion
- **docs-seeker** - Recherche de documentation technique (llms.txt, GitHub, Repomix)
- **repomix** - Packaging de repos en fichiers AI-friendly
- **skill-creator** - Creation de nouveaux skills personnalises
- **shopify** - Apps, extensions et themes Shopify
- **payment-integration** - SePay, Polar, Stripe, Paddle, Creem.io

## Installation rapide

```bash
# Via le marketplace (recommande)
/plugin marketplace add mrgoonie/claudekit-skills

# Installer par categorie
/plugin install web-dev-tools@claudekit-skills
/plugin install devops-tools@claudekit-skills
/plugin install ai-ml-tools@claudekit-skills
/plugin install document-processing@claudekit-skills
/plugin install media-tools@claudekit-skills
/plugin install backend-tools@claudekit-skills
/plugin install platform-tools@claudekit-skills
/plugin install debugging-tools@claudekit-skills
/plugin install problem-solving-tools@claudekit-skills
/plugin install specialized-tools@claudekit-skills
```
