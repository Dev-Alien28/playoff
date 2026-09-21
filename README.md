# PLAY//OFF Studio Web V4

V4 responsive Vercel, montage complet dans le navigateur.

## Nouveautés
- Timecodes `00:50` → `01:51` (les secondes seules restent acceptées).
- Hook 2 lignes : première blanche, seconde violette.
- Typographie plus forte dans le hook et les paroles.
- Les paroles LRC utilisent les timecodes absolus de la vidéo source, puis l'extrait est découpé, pour conserver la synchro.
- Logo PLAY//OFF intégré au MP4 et légèrement animé jusqu'à la phase finale.
- Image finale intégrée sur les 2,7 dernières secondes.
- Export H.264 CRF 17, preset medium, AAC 256 kb/s pour réduire la perte de qualité.
- Erreurs de rendu plus explicites.

## Vercel
Framework: Vite
Build: npm run build
Output: dist

## Local
npm install
npm run dev

Note : FFmpeg WebAssembly peut être limité par la mémoire sur mobile pour les vidéos longues. Le rendu reste entièrement local au navigateur.
