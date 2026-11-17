# Waxi — parle dès le 1er jour

Application web pour apprendre une langue **à voix haute** : anglais (parcours complet A1 → A2), portugais du Brésil et espagnol.

**Essayer : https://waxi-app.vercel.app** (de préférence dans Chrome ou Edge, pour le micro et la voix)

## Fonctionnalités

- **Parcours d'anglais** : 30 unités, 300 phrases, 90 leçons, avec une astuce de grammaire en français par unité
- **6 types d'exercices** : parler au micro, traduire, écouter, remettre les mots dans l'ordre, associer des paires, dictée
- **Correction de prononciation** mot par mot (vert / rouge)
- **Révision espacée** : les phrases reviennent après 1, 3, 7, 14, 30 et 60 jours
- **Conversations guidées** : café, rencontre, taxi, marché, aéroport
- **Arcade** : 40 secondes pour trouver un maximum de traductions
- Série de jours, objectif quotidien, XP, mode sombre

## Technique

- Un seul fichier `index.html` : HTML, CSS et JavaScript sans framework ni étape de build
- Voix : Web Speech API (`speechSynthesis` pour la lecture, `SpeechRecognition` pour le micro)
- Progression enregistrée dans le navigateur (`localStorage`)
- Hébergé sur Vercel : chaque `git push` sur `main` met le site à jour automatiquement

## Lancer en local

Ouvrir `index.html` dans Chrome ou Edge. Rien à installer.
