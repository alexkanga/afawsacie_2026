# 🚀 Déploiement Rapide sur Vercel

## Méthode 1 : Interface Vercel (Plus Simple)

### 1. Préparer le code
```bash
git add .
git commit -m "Prêt pour Vercel"
git push origin main
```

### 2. Déployer sur Vercel
1. Allez sur [vercel.com](https://vercel.com)
2. Cliquez "Add New..." → "Project"
3. Importez votre dépôt GitHub/GitLab/Bitbucket
4. Cliquez "Deploy"

### 3. C'est fini ! 🎉
Vercel détecte automatiquement Next.js et déploie votre app.

---

## Méthode 2 : Vercel CLI

### 1. Installer Vercel CLI
```bash
npm install -g vercel
```

### 2. Connecter et déployer
```bash
vercel login
vercel
vercel --prod
```

---

## ✅ Ce qui est déjà configuré

- ✅ `vercel.json` créé
- ✅ `next.config.ts` adapté pour Vercel
- ✅ Pas de variables d'environnement requises
- ✅ API KoboToolbox prête

---

## 🌐 Après le déploiement

Votre URL sera : `https://your-project-name.vercel.app`

Pour un domaine personnalisé :
1. Settings → Domains
2. Ajoutez votre domaine
3. Configurez les DNS

---

## 📊 Vérifier le déploiement

```bash
# Tester l'API
curl https://your-project-name.vercel.app/api/kpi
```

Devrait retourner les sessions : [1, 2, 3, 5, 6, 8, 10, 12, 14]
