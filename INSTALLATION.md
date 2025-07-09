# 🚀 Guide d'Installation - Clavier Arabe Universel pour Blogger

## Installation en 5 minutes ⏱️

### Étape 1 : Télécharger les fichiers
1. Téléchargez tous les fichiers du projet
2. Hébergez-les sur votre serveur web (avec HTTPS de préférence)
3. Notez l'URL de base (ex: `https://monsite.com/clavier/`)

### Étape 2 : Choisir votre version
- **Widget standard** : `blogger-widget.html` (pour articles principaux)
- **Widget compact** : `blogger-widget-compact.html` (pour barres latérales)

### Étape 3 : Intégrer dans Blogger
1. Allez dans **Blogger** → **Mise en page**
2. Cliquez sur **"Ajouter un gadget"**
3. Sélectionnez **"HTML/JavaScript"**
4. Collez le code d'intégration (voir ci-dessous)
5. **Sauvegardez**

### Étape 4 : Code d'intégration

#### Pour widget standard :
```html
<div style="width: 100%; max-width: 800px; margin: 20px auto; text-align: center;">
    <h3 style="color: #333; margin-bottom: 15px;">🌟 Clavier Arabe Universel</h3>
    <iframe 
        src="https://VOTRE-DOMAINE.com/blogger-widget.html" 
        width="100%" 
        height="600" 
        frameborder="0" 
        scrolling="no"
        style="border: 2px solid #e0e0e0; border-radius: 12px;">
    </iframe>
</div>
```

#### Pour widget compact :
```html
<div style="width: 100%; max-width: 300px; margin: 10px auto;">
    <iframe 
        src="https://VOTRE-DOMAINE.com/blogger-widget-compact.html" 
        width="100%" 
        height="450" 
        frameborder="0" 
        scrolling="no"
        style="border: 1px solid #e0e0e0; border-radius: 8px;">
    </iframe>
</div>
```

### Étape 5 : Remplacer l'URL
⚠️ **Important** : Remplacez `https://VOTRE-DOMAINE.com` par l'URL réelle où vous avez hébergé les fichiers.

## 🎯 Installation rapide sans hébergement

Si vous n'avez pas de serveur, vous pouvez utiliser des services gratuits :

### Option 1 : GitHub Pages (Gratuit)
1. Créez un compte GitHub
2. Créez un nouveau repository public
3. Uploadez tous les fichiers
4. Activez GitHub Pages dans les paramètres
5. Utilisez l'URL fournie : `https://votre-nom.github.io/nom-repo/`

### Option 2 : Netlify (Gratuit)
1. Créez un compte sur Netlify
2. Glissez-déposez le dossier du projet
3. Utilisez l'URL générée automatiquement

### Option 3 : Vercel (Gratuit)
1. Créez un compte sur Vercel
2. Connectez votre repository GitHub
3. Déployez automatiquement

## 🔧 Personnalisation rapide

### Changer la langue par défaut
Éditez le fichier `blogger-widget.html` ligne ~200 :
```javascript
this.currentLanguage = 'fr'; // Pour français
this.currentLanguage = 'ar-ma'; // Pour darija
```

### Adapter les couleurs à votre thème
Ajoutez ce CSS dans votre widget :
```html
<style>
.widget-header {
    background: linear-gradient(135deg, #VOTRE-COULEUR1, #VOTRE-COULEUR2) !important;
}
</style>
```

## 📱 Test de fonctionnement

Après installation :
1. Visitez votre blog
2. Vérifiez que le widget s'affiche
3. Testez la saisie dans différentes langues
4. Vérifiez sur mobile et desktop

## ❓ Problèmes courants

### Le widget ne s'affiche pas
- ✅ Vérifiez que l'URL est correcte et accessible
- ✅ Assurez-vous que votre hébergement supporte HTTPS
- ✅ Vérifiez les paramètres de sécurité de Blogger

### Le clavier ne fonctionne pas
- ✅ Vérifiez la console JavaScript (F12)
- ✅ Assurez-vous que JavaScript est activé
- ✅ Testez dans un autre navigateur

### Affichage incorrect sur mobile
- ✅ Ajustez la hauteur de l'iframe
- ✅ Utilisez `width="100%"` au lieu d'une largeur fixe

## 🎉 Félicitations !

Votre clavier arabe universel est maintenant installé ! Vos lecteurs peuvent désormais taper en 5 langues directement depuis votre blog.

## 📞 Besoin d'aide ?

- 📖 Consultez le README.md complet
- 🧪 Utilisez la page de démonstration pour tester
- 💬 Contactez le support si nécessaire

---

**Installation réussie ?** Partagez votre expérience et aidez d'autres utilisateurs ! 🌟

