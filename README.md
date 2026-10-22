# Celestria — Realmforge prototype

Based on your working document **Skies of Destiny: The Titan's Descent**.

## Features in this build
- Procedural Three.js miniature 3D atlas for Aetheria, Ironpeak, Sylvanor and Sky's End.
- Glowing skyway connections between the four floating regions.
- Underlands view with Morthos, the Abyssal Chasm, Temple of the Ancients, Luminous Glades, Lost City of Eternia, Necropolis of Shades and Enchanted Forest.
- Aetherion capital-city view with stylised walls, streets, houses, royal citadel and skyport.
- Clickable landmarks, directory, location descriptions, isometric/free camera controls and prototype DM secrets.
- Mobile-friendly layout.

## Run locally
Extract the ZIP, open a terminal in the folder and run `python -m http.server 8000`. Visit `http://localhost:8000`. Do not open `index.html` directly because it uses JavaScript modules.

## Host online with GitHub Pages
1. Create a repository at https://github.com/new.
2. Upload `index.html`, `style.css`, `app.js`, and `README.md` to the repository root.
3. Go to **Settings → Pages**; choose **Deploy from a branch**, `main`, `/(root)`, then Save.
4. Open the published URL on your phone.

## Honest limitations
This is a runnable prototype, not a finished VTT. City interiors, saved campaigns, player accounts, live multiplayer sync, secure server-side DM permissions, editable map authoring and true fog-of-war painting are not implemented yet. DM mode is only a client-side demo and must not be used to protect secrets online. Three.js is loaded from a CDN, so internet access is needed. The document uses both “Eternia” and “Atlantis” for the lost city; this build uses Eternia and leaves the naming decision to you. The document also has differing royal/NPC naming in places; this prototype uses the region descriptions and secret details without trying to reconcile every inconsistency.
