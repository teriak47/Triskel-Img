# Guide de Contribution / Contributing Guide

## Ajouter des images / Adding Images

### Règles / Rules

1. **Organisation** : Placez les images dans la catégorie appropriée
   - `screenshots/` : Captures d'écran d'applications ou d'interfaces
   - `logos/` : Logos officiels et variantes
   - `icons/` : Icônes et petites images graphiques
   - `banners/` : Bannières et images d'en-tête
   - `misc/` : Autres types d'images

2. **Nomenclature** : Utilisez des noms descriptifs en minuscules avec des tirets
   - ✅ Bon : `triskel-logo-dark.png`, `app-screenshot-2024.jpg`
   - ❌ Mauvais : `IMG_001.png`, `Image1.jpg`

3. **Taille** : Optimisez les images avant de les uploader
   - Utilisez des outils de compression sans perte
   - Limitez la taille des fichiers (recommandé : < 1MB)

4. **Format** : Choisissez le format approprié
   - PNG : Pour les logos, icônes, images avec transparence
   - JPG : Pour les photos et captures d'écran
   - SVG : Pour les graphiques vectoriels
   - GIF : Pour les animations simples
   - WebP : Pour une meilleure compression

### Processus / Process

1. Fork ce dépôt
2. Créez une nouvelle branche : `git checkout -b add-image-description`
3. Ajoutez votre image dans le dossier approprié
4. Committez : `git commit -m "Add [description] image"`
5. Push : `git push origin add-image-description`
6. Créez une Pull Request

### Bonnes pratiques / Best Practices

- Vérifiez que vous avez les droits d'utilisation de l'image
- N'uploadez pas d'images contenant des informations sensibles
- Testez l'URL de l'image avant de créer la PR
- Ajoutez une description claire dans votre PR

---

## Adding Images

### Rules

1. **Organization**: Place images in the appropriate category
   - `screenshots/`: Application or interface screenshots
   - `logos/`: Official logos and variants
   - `icons/`: Icons and small graphic images
   - `banners/`: Banners and header images
   - `misc/`: Other types of images

2. **Naming**: Use descriptive lowercase names with hyphens
   - ✅ Good: `triskel-logo-dark.png`, `app-screenshot-2024.jpg`
   - ❌ Bad: `IMG_001.png`, `Image1.jpg`

3. **Size**: Optimize images before uploading
   - Use lossless compression tools
   - Limit file size (recommended: < 1MB)

4. **Format**: Choose the appropriate format
   - PNG: For logos, icons, images with transparency
   - JPG: For photos and screenshots
   - SVG: For vector graphics
   - GIF: For simple animations
   - WebP: For better compression

### Process

1. Fork this repository
2. Create a new branch: `git checkout -b add-image-description`
3. Add your image in the appropriate folder
4. Commit: `git commit -m "Add [description] image"`
5. Push: `git push origin add-image-description`
6. Create a Pull Request

### Best Practices

- Verify you have usage rights for the image
- Don't upload images containing sensitive information
- Test the image URL before creating the PR
- Add a clear description in your PR
