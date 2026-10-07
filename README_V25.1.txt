# BE STRONGER V25.1

## Installation GitHub Pages
1. Décompresse le ZIP.
2. Envoie **tous les fichiers et le dossier assets** dans ton dépôt GitHub.
3. Le fichier d'entrée est `index.html`.
4. Dans GitHub : Settings → Pages → Deploy from branch → `main` → `/root`.
5. Ouvre l'URL GitHub Pages.

## Ce qui est corrigé
- Plus besoin de Supabase pour démarrer.
- Espace Coach séparé de l'espace Client.
- Création du premier accès coach au premier lancement.
- Création de clients depuis l'espace Coach.
- Génération automatique d'un code client.
- Connexion client par code.
- Le client ne voit pas la liste des autres clients ni les fonctions coach.
- Programmes sur plusieurs semaines.
- Charges / reps / RPE côté client.
- Timer AMRAP / EMOM / FOR TIME / TABATA.
- Données conservées dans le navigateur via localStorage.

## Important
Cette V25.1 est une version **fonctionnelle sans backend**, destinée à remettre l'application en marche immédiatement.
Les données restent sur le navigateur utilisé. Donc un code client créé sur ton téléphone/ordinateur ne sera pas automatiquement connu sur un autre téléphone.

Pour une vraie version professionnelle multi-appareils, il faudra connecter Supabase avec :
- Project URL
- Publishable key uniquement
et mettre en place des règles RLS.

**Ne mets jamais une service_role/secret key dans l'application.**
