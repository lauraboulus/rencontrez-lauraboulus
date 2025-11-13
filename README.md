# Portfolio Laura Boulus - Guide de mise en ligne

## 📁 Fichiers du portfolio

Votre portfolio contient :
- `index.html` - Page principale avec toutes les sections
- `contact.html` - Page de contact avec formulaire
- `photo_linkedin.png` - Votre photo de profil
- `timeline.png` - Image de votre parcours (référence)

## 🚀 Options de mise en ligne GRATUITES

### Option 1 : Netlify (RECOMMANDÉ - Le plus simple)

1. **Créer un compte sur Netlify**
   - Allez sur https://www.netlify.com
   - Créez un compte gratuit

2. **Déployer votre site**
   - Cliquez sur "Add new site" → "Deploy manually"
   - Glissez-déposez TOUS vos fichiers (index.html, contact.html, photo_linkedin.png)
   - Votre site sera en ligne en quelques secondes !

3. **Personnaliser l'URL**
   - Dans les paramètres du site, cliquez sur "Domain settings"
   - Changez le nom du site en "rencontrez-lauraboulus" (ou similaire)
   - Votre URL sera : `rencontrez-lauraboulus.netlify.app`

### Option 2 : GitHub Pages

1. **Créer un compte GitHub**
   - Allez sur https://github.com
   - Créez un compte gratuit

2. **Créer un nouveau repository**
   - Cliquez sur "New repository"
   - Nommez-le : `rencontrez-lauraboulus`
   - Cochez "Public"
   - Créez le repository

3. **Upload vos fichiers**
   - Cliquez sur "Add file" → "Upload files"
   - Glissez tous vos fichiers HTML et images
   - Commit les changements

4. **Activer GitHub Pages**
   - Allez dans Settings → Pages
   - Source : "Deploy from a branch"
   - Branch : "main" → Folder : "/ (root)"
   - Votre site sera à : `votre-username.github.io/rencontrez-lauraboulus`

### Option 3 : Vercel

1. **Créer un compte sur Vercel**
   - Allez sur https://vercel.com
   - Créez un compte gratuit

2. **Déployer**
   - Cliquez sur "Add New" → "Project"
   - Importez depuis GitHub ou glissez-déposez vos fichiers
   - Le site sera déployé automatiquement

## 🎨 Personnalisation du portfolio

### Modifier les couleurs
Dans `index.html` et `contact.html`, section `<style>`, modifiez :
```css
:root {
    --navy: #1a3a52;      /* Bleu marine principal */
    --light-navy: #2c5f7f; /* Bleu marine clair */
    --beige: #f5f1e8;      /* Beige */
    --cream: #faf8f3;      /* Crème/fond */
    --gray: #4a4a4a;       /* Gris texte */
}
```

### Ajouter des projets
Dans `index.html`, section "Réalisations", dupliquez un bloc `<div class="project-card">` et modifiez le contenu.

### Modifier les informations de contact
Dans `contact.html`, modifiez les sections `.info-item` avec vos nouvelles coordonnées.

## 📱 Fonctionnalités du portfolio

✅ Design responsive (mobile, tablette, desktop)
✅ Navigation fluide entre les pages
✅ Animations au scroll et au hover
✅ Formulaire de contact fonctionnel (ouvre le client email)
✅ Timeline interactive de votre parcours
✅ Sections : Vision, Parcours, Valeurs, Ambition, Réalisations, Compétences
✅ Palette de couleurs sobre : gris, bleu marine, beige, crème
✅ Typographie élégante (Playfair Display + Inter)

## 🔧 Support et modifications

Pour toute modification :
1. Éditez les fichiers HTML avec un éditeur de texte (VS Code, Sublime Text, etc.)
2. Sauvegardez les changements
3. Re-uploadez sur votre plateforme d'hébergement

## 📊 Statistiques attendues

- Temps de chargement : < 2 secondes
- Score Google PageSpeed : 90+
- Compatible tous navigateurs modernes
- 100% responsive

## 🎯 Prochaines étapes

1. Téléchargez tous les fichiers
2. Choisissez votre plateforme d'hébergement (Netlify recommandé)
3. Uploadez vos fichiers
4. Partagez votre portfolio : `votre-url-choisie`

Bon succès avec votre portfolio ! 🚀
