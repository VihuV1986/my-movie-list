# My Movie List

A personal movie and series tracker. Search a title, add it in one tap, and keep track of your progress. It installs on Android, iPhone, Windows and Mac, works offline, and keeps your data private on your own device.

## Get started

1. Open the app link in your browser (for example `https://YOUR-USERNAME.github.io/my-movie-list/`).
2. Get a free TMDB API key (see below).
3. Paste the key into **Settings** and start searching.

Anime search works right away with no key. The key is only needed for **Movies and TV** search.

---

## 1. Get a free TMDB API key

TMDB (The Movie Database) provides the movie and TV data. The key is free and takes a few minutes.

1. Go to **https://www.themoviedb.org** and tap **Join TMDB** to create a free account. Confirm your email address.
2. Sign in, tap your profile picture (top right), and open **Settings**.
3. In the left menu, choose **API**.
4. Tap **Create** (or **Request an API key**) and choose the personal, non-commercial option.
5. Accept the terms and fill in the form:
   - **Application name:** anything, for example `My Movie List`
   - **Application URL:** your app link, or a placeholder such as `http://localhost`
   - **Application summary:** one line, for example "A personal watchlist tracker for my own use."
   - **Contact details:** your own name, email and address
6. Submit. Your keys now appear on the **API** page.

You will see two values. Either one works in the app:

| Value | What it looks like | Notes |
| --- | --- | --- |
| **API Key** | About 32 letters and numbers | Shorter and easier to copy. Recommended. |
| **API Read Access Token** | A very long string starting with `eyJ` | Also works, but easy to copy only part of it. |

TMDB's page layout changes from time to time. If a step looks different, look for the **API** section under your account settings.

---

## 2. Paste the key into the app

1. Open the app and tap the **Settings** tab.
2. Find the **TMDB API key** box.
3. Paste your API Key (or Read Access Token) into it. Tap **Show** if you want to check what you pasted.
4. Tap **Save key**.
5. Tap **Test key**. You should see **Key saved and working.**

Now go to the **Search** tab, choose **Movies and TV**, and type a title. Tap a result and it is added to your watchlist with the type, seasons, episodes and runtime filled in for you.

---

## Keep your key private

- Your key is stored only in your browser on your device. It is never uploaded to this app's files or to GitHub.
- Never paste your key into the code or share it publicly. If someone else uses the app, they should create their own free key.
- If a key is ever exposed, you can delete it and create a new one on the TMDB **API** page.

---

## Troubleshooting

| Problem | What to try |
| --- | --- |
| "Could not reach TMDB" | Open the app in a normal browser (Chrome, Safari, Edge) using the hosted link. It will not connect if opened inside another app's built-in preview. Also check your internet connection. |
| "TMDB rejected this key" | Copy the key again from the TMDB **API** page and make sure no spaces or characters are missing. |
| "Add your TMDB key in Settings" | The key box is empty. Paste and save it as described above. |
| No results | Check the spelling, try the other source (Movies and TV vs Anime), or use **Add it by hand**. |
| My list is empty on a new device | Lists are stored per device. Use **Export watchlist** in Settings on the old device and **Import watchlist** on the new one. |

---

## Install as an app

- **Android (Chrome):** menu (⋮), then **Install app**.
- **iPhone / iPad (Safari):** Share, then **Add to Home Screen**.
- **Windows (Chrome or Edge):** click the install icon in the address bar.
- **Mac (Chrome or Edge):** click the install icon in the address bar. In Safari, use File, then **Add to Dock**.

---

## Credits

Movie and TV data from [TMDB](https://www.themoviedb.org).

This product uses the TMDB API but is not endorsed or certified by TMDB.
