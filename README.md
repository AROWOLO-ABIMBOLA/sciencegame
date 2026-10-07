# Wonder Buddies

Fun science for Nigerian children aged 2 to 12:

- **Little Explorers** (ages 2 to 4): picture-and-sound science games with no reading needed.
- **Science Arcade** (ages 5 to 12): nine worlds (Space, Living Planet, My Amazing Body, Tiny World, Matter Lab, Forces and Machines, Energy and Power, Light and Sound, Earth and Weather). Each world has 6 levels with read-aloud lessons, hands-on "Try it" activities, tests, and 54 science legends to meet, from Nigeria, Africa and the world.
- **School Science**: Basic Science (Primary 1 to 3) and Basic Science and Technology (Primary 4 to 6), class by class and term by term. Every topic has Learn, Try, Practice and a safe "Try it at home" activity. Children win term badges, then take a 30-question final challenge for a printable certificate. **Primary 1, 2 and 3 are open now**, and more classes are coming.

Made by **Dr. Arowolo Ayoola**.

---

## Live link

**https://arowolo-abimbola.github.io/sciencegame/**

Published from the `sciencegame` repository: <https://github.com/AROWOLO-ABIMBOLA/sciencegame>

## Switching on GitHub Pages (once)

1. Open <https://github.com/AROWOLO-ABIMBOLA/sciencegame/settings/pages>
2. **Source:** Deploy from a branch. **Branch:** `main`, folder `/ (root)`. Click **Save**.
3. Wait 1 to 2 minutes. Watch <https://github.com/AROWOLO-ABIMBOLA/sciencegame/actions> for a green tick, then open **https://arowolo-abimbola.github.io/sciencegame/**

## Updating the game later

Open <https://github.com/AROWOLO-ABIMBOLA/sciencegame/upload/main>, drag in the new `index.html` (it replaces the old one) and commit. Children get the new version the next time they open the game with internet. Their progress is not affected.

---

## For parents: how it works

**Progress is saved on the device your child plays on.** There are no accounts and nothing is sent to a server.

- **Install it like an app.** On Android (Chrome), tap **Install app** at the top of the home screen, or use the browser menu **⋮ → Add to Home screen / Install app**. On iPhone or iPad (Safari), tap **Share**, then **Add to Home Screen**. The game then has its own icon and works without internet after the first visit.
- **Please install it on iPhones and iPads.** Safari may clear website data if a site is not opened for 7 days. Games added to the Home Screen keep their progress.
- **Sound:** lessons and questions are read aloud by the device's own voice. Turn the volume up.
- **Certificates:** after the final challenge, your child types their name, and you can print the certificate (landscape) or save it as a PDF from the print screen.
- **Coming soon:** a Parent corner with several children per device, voice messages and backups.

## What's in this folder

| File | What it does |
|---|---|
| `index.html` | The whole game |
| `manifest.webmanifest` | Lets phones install it as an app with its own name and icon |
| `sw.js` | Lets the game open without internet after the first visit |
| `icons/` | App icons and the link-preview picture |
| `.nojekyll` | Tells GitHub to publish the files exactly as they are |

Storage on the device uses the `sci.` prefix and the offline cache `wonder-buddies-v1`, so it never mixes with Number Buddies or the other games on the same web address.
