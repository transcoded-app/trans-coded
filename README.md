<p align="center"><img src="leaf.svg" width="156" alt="A pixel maple leaf in the trans flag's colours"></p>

<h1 align="center">Trans Coded</h1>

<p align="center"><b>Your DVDs and Blu-rays, freed from their plastic prisons.</b></p>

Put a disc in. Press Start. Go make popcorn.

Trans Coded works out what the disc is, shrinks it to a sensible size, names it properly and files it in a Library you can watch from any Mac in the house. No more renaming files by hand at 1 a.m. like some kind of raccoon.

*Made by a trans person in Canada.* Yes, the leaf is the trans flag. Yes, it's pixelated on purpose. No, we will not be taking questions.

## Get it

On the Mac your disc drive plugs into, open **Terminal** (press ⌘ Space, type Terminal, press Return) and paste this:

```
curl -fsSL https://github.com/transcoded-app/trans-coded/releases/latest/download/get-trans-coded.sh | bash
```

Answer a few quick questions. That's it. That's the setup. No accounts, no keys, no sign-ups, and about three minutes start to finish.

It fetches the free tools straight from the people who make them (HandBrake, MakeMKV and VLC), asks where your movies and shows should live, and opens the dashboard when it's done. Run the same line again any time to update. Your settings stay put, like a cat on a warm laptop.

## What you get

- **A dashboard that pays attention.** Put a disc in and it tells you what it sees ("Oh! A Blu-ray. You don't say!"), ticks the right titles, and rips with one press.
- **Proper names, every time.** *Movie (Year)*. *Show S01E05*. Checked against TheMovieDB and IMDb. Nothing gets guessed: if Trans Coded isn't sure, it asks you instead of making something up.
- **Smaller files, fast.** Shrunk with HandBrake on your Mac's own video hardware, so a movie takes minutes, not your whole evening.
- **Your own Library.** Posters, search, and one-click play in VLC or right in the browser. Already use Plex, Jellyfin, Emby or Kodi? It files everything the way they like it, too.
- **Pick your size.** One Quality button: smaller files, balanced, or the sharpest picture, plus the biggest a movie can be. It can slim down movies already in your library too, one at a time, originals set aside (never deleted).
- **Tidy names in one click.** Real episode titles instead of "rides", and movie files named after their folders instead of "WEBDL-720p-GRP-whatever". You see every change first. Nothing is overwritten, ever.
- **It knows its languages.** Each title on a disc shows its audio languages, so the German-commentary copy doesn't sneak into your library dressed as the movie.
- **The Waiting Room.** Calm scenes, music, trivia about whatever you're ripping, and a quiz. Because staring at a progress bar is a crime against joy.

## What you need

- A Mac on macOS 12 (Monterey) or newer. Apple silicon or Intel, it's not picky.
- A DVD or Blu-ray drive. A plain USB one is perfect.
- Room for your collection: roughly 5 GB a movie. An external drive makes a lovely home.

## Something weird happened?

Press **Send feedback** at the bottom of the dashboard. It goes straight to the person who made this, with a tech report you can read (and edit) first. Your name, folders and keys are blanked out automatically.

Bugs, strange discs, a sentence that made no sense: send it all. Trans Coded gets better every time someone does.

## Uninstall

```
curl -fsSL https://github.com/transcoded-app/trans-coded/releases/latest/download/uninstall.sh | bash
```

It moves Trans Coded to the Trash (not deleted) and asks before touching HandBrake, MakeMKV or VLC. Your movies and shows are never touched. We're not monsters.

## The fine print

Trans Coded doesn't contain any decryption of its own: it organizes free tools that you install from their makers. Laws about copying discs vary by country, so check yours. How you use it is up to you.

Information courtesy of IMDb ([imdb.com](https://www.imdb.com)), used with permission for personal, non-commercial use. This product uses the TMDB API but is not endorsed or certified by TMDB.
