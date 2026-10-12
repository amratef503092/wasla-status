# Wasla status

Every 5 minutes GitHub Actions checks https://wasla.amratef.dev (API health, website, login).
If anything is down 3 times in a row, an issue labelled `down` is opened and assigned to the owner (email + GitHub app notification); it closes itself when the site is back.
