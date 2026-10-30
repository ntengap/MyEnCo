MY ENGLISH COMPANION — SEO / GITHUB PAGES

1. Publier TOUS les fichiers de ce dossier à la racine du dépôt GitHub ntengap/MyEnCo (branche de publication GitHub Pages).
2. Conserver exactement le chemin et la casse /MyEnCo/.
3. Attendre le déploiement, puis ouvrir https://ntengap.github.io/MyEnCo/ et vérifier les fichiers /MyEnCo/sitemap.xml, /MyEnCo/robots.txt, /MyEnCo/og-image.png et /MyEnCo/llms.txt.
4. Google Search Console : ajouter la propriété « Préfixe d’URL » https://ntengap.github.io/MyEnCo/ ; suivre une méthode de validation proposée par Google (par exemple un fichier HTML à déposer à la racine du projet), puis envoyer sitemap.xml. Ce kit ne peut pas vérifier Search Console à votre place.
5. HTTPS : GitHub Pages sert déjà ce domaine github.io en HTTPS ; les URLs SEO utilisent HTTPS. Aucune règle de redirection serveur n’est possible via un simple fichier dans GitHub Pages.
6. Recharger la PWA après le déploiement : le service worker change de version pour rafraîchir le cache.
7. Pas de pages artificielles : l’application est une SPA à une URL publique. Sitemap = une seule URL canonique.
8. llms.txt est un document informatif, pas un chatbot LLM ni une garantie d’indexation.
9. Audit externe non effectué : aucun score Lighthouse / Core Web Vitals réel, aucune validation Search Console, aucun contrôle exhaustif de tous les liens dynamiques.
10. Images : les PNG d’icônes sont déjà petits ; l’image Open Graph est compressée. Pas d’images HTML existantes exigeant des attributs alt.
