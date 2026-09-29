# Blackjack Academy — Firebase Hosting

Firebase project: `blackjack-academy-26648`

## Repository layout

- `public/index.html`: static app
- `firebase.json`: Hosting settings
- `.firebaserc`: Firebase project alias
- `.github/workflows/deploy.yml`: deploy on pushes to main or manual dispatch

## Required GitHub secret

Create a repository Actions secret named `FIREBASE_SERVICE_ACCOUNT_BLACKJACK_ACADEMY` containing the JSON for a dedicated Google Cloud service account with Firebase Hosting deployment permissions on this Firebase project. Never commit the JSON key to GitHub or share it in chat. Prefer short-lived credentials or workload identity federation when feasible.

After the secret is configured, push to `main` or run the workflow manually under GitHub Actions. Hosting URL: https://blackjack-academy-26648.web.app/
