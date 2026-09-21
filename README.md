# PLAY//OFF Studio Web

## Local
npm install
npm run dev

## Vercel
Importe ce dossier dans GitHub puis importe le repo dans Vercel. Framework preset: Vite. Build: `npm run build`. Output: `dist`.

## Fonctionnement
- Responsive ordinateur/mobile
- Import vidéo et LRC local
- Séquences avec hook indépendant
- Aperçu 9:16 avec hook, paroles, logo animé et frame finale
- Export MP4 1080x1920 via FFmpeg WebAssembly dans le navigateur

Note: l'export navigateur est gourmand en mémoire. Sur mobile, privilégier des séquences courtes. La V1 exporte le recadrage vidéo MP4; l'aperçu affiche les overlays. Pour incruster les overlays dans le MP4 final de manière robuste sur tous navigateurs, une V2 serveur de rendu est recommandée.
