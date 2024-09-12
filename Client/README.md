# Overview of Wartune game clients
As the title suggests: Wartune is (still) a browser game, even in 2024 or any year into the future.<br> *(Galadrienne's a pathological- and paid- liar btw)*

## A quick history lesson
The game was originally played on a web browser with Adobe Flash plugins.

Since even the company called Adobe themselves, are pathological a$$holes : They pathologically engineered Adobe Flash to **suck**! As they're the type of lifeform that **must** at-all-times be their utmost pinnacle-a$$-self, `-Otherwise their own blood, genes and even the fabric of reality itself will disintegrate their existence-` ,  they are therefore at the mercy of their own existence to not allow Adobe Flash to ever improve. This bodily and existentially property of theirs, ultimately drove them to discontinue Adobe Flash, `-Which they obviously backed up with willful ignorant arguments-` , instead of open sourcing it.

As a result of Adobe = Adobe, the "online game" Wartune needed a dedicated web-application in order to run its own website.

## 7Road's game client - Mini client
Adobe and 7Road are ran by the same lifeform, thus they both "must" be their utmost a$$-self at all times, for the same reasons that are described in the previous paragraph. This existential reason drove 7Road into computer-engineering *the single worst* (Windows) web-application that mankind has ever seen, and probably "will ever see."

The Mini Client is a web application that...
- Has its (Windows UX) implementation <ins>destroy the maximize/restore</ins> button, as well as disable the resizability of its window through mouse cursor interaction.
- (and) Has engineered application crashes.

Suffice to say: The game is absolutely unplayable with this client.

## Brov Client (original)
TL;DR: This piece of software is what makes the game playable and here's how to get it:
1. Go to: https://brov.site/ with a Chromium-based browser, I'd recommend either Brave or hardened Thorium.
2. Use the Chromium-based browser's built-in translator to change the site from Polish to English. *(Firefox's extension "Simple Translate" can't translate the page, so that's why Chromium.)*
3. Scroll down his blog until the post from [August 22, 2023](https://brov.site/2023/08/alternatywny-klient-do-gry-22-sierpien-2023/) and download/execute `LegendOnline.MSVC_20230822_x64.exe`

How to configure:
- **E-mail:** For most normal 7Road accounts, you can input your username. Only some weird accounts require you to input the account's registered email instead, for reasons unknown to me.
- **Password:** Self-explanatory.
- **Platform:** A drop-down list for you to select the right server category
- **Server:** Another drop-down list for you to select the exact server number. *(If no drop-down list is shown, something has gone wrong with the client)*
- **Enable cache to reduce lag:** Keep on, or turn on if disabled
- **Disable Flash Player local storage:** Keep off
- **Quality:** low, because the game's ugly anyway.
- **WMode:** Keep "direct", or use "gpu" if you have a dedicated graphics card I suppose.

### Features
- Pressing F9 hides all loaded game windows.
- Dimension helper and Macro features don't work!
- Clicking the "Close" on a logged and loaded character will pop-up a dialogue with options "Yes", "No" and "Relog".
- The relog feature reloads the respective game window into the last logged in character. Example:
  - Brov instance 1 = Bob and Brov instance 2 = Robin. (Instance 2 has been logged and loaded at a later timestamp)
  - You reload Brov instance 1: Robin will be logged in, while instance 2 gets disconnected.

### Saving account // character details
- Can save up to an unknown large amount of account login details
- For each "platform" selection, (up to) 5 numbers can be remembered as "recent servers" up top of the drop-down list.
- Appending space(s) in front of the (example) username " googolplex", allows you to login the 7Road account "googolplex" like normal, but appears on your username drop-down list as separately saved entry. *(This can be helpful to relog multiple game windows with characters from the same 7Road account)*

### How to: Collect daily Mini Client rewards
1. Load your game in Brov like normal.
2. Login with the Mini Client, but then **close it as soon as you see the 7Road logo**!!
3. Open up Hot Events in your Brov client and collect the rewards.

This trick will bug your game instance from viewing in-game mail. Any mail that gets sent to your character will be invisible until you relog.

## Brov Client (Experimental)
A re-creation of the client which has pros and cons, and here's how to get it:
1. Same website: https://brov.site/
2. Look for the latest post that describes the "preview" client. At the time of writing, [January 07, 2024](https://brov.site/2024/01/alternatywny-klient-do-gry-7-styczen-2024-wersja-pogladowa/) is the latest.
3. Both original and preview clients can be installed on the same system btw, so just install it.

There are several differences...

### Pros
1. (For my experience) The game feels a little more responsive.
2. You can drag the window **<ins>without</ins> causing your next combat instance to be bugged**.<br> `Combat frame being sucked into the top-left corner, the rest of your window being blackscreen until you press the 'maximize/restore' button twice to fix`
3. The client depends on significantly less binaries, e.g. program files is less bloated.

### Cons
1. The user interface has been bloated with a proprietary "stylish" UX, which makes mouse cursor interactions such as resizing more annoying. *(The 3 added buttons on the titlebar don't work btw)*
2. The new caching implementation can...
     - Cause in-game pm'ing to freeze, after some time.
     - Get you bugged from logging in, either after some time or logging in too many different accounts // characters within a short period of time.
3. Sometimes with multiple windows open, your in-game mail will be unviewable in a similar fashion to using [this trick](#how-to-collect-daily-mini-client-rewards), as described above.
4. The "reload" feature loads the (server-side) most recently logged character, instead of the most recently logged character on the local system. *(Read the below section for more explanations)*

### Why the new reload is bad?
- If an account (with multiple characters) is shared between multiple players, they can log into each other's currently active characters, potentially ruin battles.
- This defeats the space(s) trick that could be applied to the original client, in order to separate game windows for flawless relogs.

## Playing with browser
This **is** in fact still possible:
1. Use the latest version of Firefox that still supported Adobe Flash, e.g. [Firefox 84.0.2](https://drive.google.com/file/d/10dXAqFaab4sBPQbyG81r90e-pEzSG7O-/view?usp=drive_link)
2. Install the latest usable Adobe Flash plugin to go along with it, e.g. `flashplayer32_0r0_371_winax.exe` from [this archive](https://drive.google.com/file/d/1zqN5mYkEvYvZbdT1DnYTwf4iTgmd6iXO/view?usp=drive_link).
3. Just play on 7Road's website.

If Brov's clients were to ever fail, this way of playing is ofc superior over the Mini Client.