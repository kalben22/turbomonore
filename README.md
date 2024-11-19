# turbomonore

# Turbo Monorepo Starter

Ce dépôt est un monorepo configuré avec [Turbo](https://turbo.build/) pour gérer plusieurs packages et applications dans un même dépôt. Il permet de développer, de tester, et de déployer vos projets avec une structure optimisée.

## 🛠️ Prérequis

Avant de commencer, assurez-vous d'avoir les outils suivants installés sur votre machine :

- [Node.js](https://nodejs.org/) (v16 ou supérieur recommandé)
- [pnpm](https://pnpm.io/) ou [npm](https://www.npmjs.com/)
- [Git](https://git-scm.com/)

## 🚀 Installation

1. Cloner le projet :

   git clone <URL_DU_REPO>
   cd <NOM_DU_REPO>

2. Installer les dépendances :

   Si vous utilisez `pnpm` (recommandé) :

   pnpm install 

   Sinon, utilisez `npm` :

   npm install

## 🏃‍♂️ Lancer le projet

### Démarrer toutes les applications

Pour démarrer tous les packages et applications dans le monorepo :

```bash
pnpm turbo run dev
npm turbo run dev 
```

### Lancer une application spécifique

Naviguez dans le dossier de l'application que vous souhaitez démarrer, puis lancez :

```bash
pnpm run dev
npm run dev
```

### Construire le projet

Pour construire toutes les applications et packages dans le monorepo :

```bash
pnpm turbo run build
npm run build
```

### Tester les applications

Pour exécuter les tests dans tous les packages et applications :

```bash
pnpm turbo run test
```

