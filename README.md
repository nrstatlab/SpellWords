# ✏️ SpellWords Challenge

A free, simple online game that teaches students the **spelling of English words**.
Everything is in **one file** (`index.html`). There is **no server, no database, no login and no storage plan** to pay for.

## How to play

1. Open `index.html` in any browser (phone, tablet, laptop or smart board).
2. Type your name (optional), then choose a **level** (Easy / Medium / Hard), a **game mode** and how many words to play.
3. Spell each word. You get **two tries**, and every word comes with its meaning, an example sentence and a memory tip.
4. At the end you see your score, stars, accuracy and a **"Words to practise"** list.

### Game modes

| Mode | What the student does | Skill it builds |
|---|---|---|
| 🔊 **Listen & Spell** | Hears the word (normal or slow) and types it | Sound-to-spelling, listening |
| 🧩 **Missing Letters** | Sees `g _ v e r _ m e _ t` and completes it | Visual memory of tricky letters |
| 🔀 **Unscramble** | Taps jumbled letter tiles into the right order | Letter order, pattern recognition |
| 🎲 **Mixed** | All three modes in turn | Keeps the class interested |

### Scoring

- Correct on the 1st try: **10 points**. Correct on the 2nd try: **5 points**.
- Streak bonus: **+2** after 2 correct answers in a row.
- Each hint costs **3 points**. A hint reveals the next correct letter.

## 👩‍🏫 Teacher tool: your own word list, with no storage

Click **Teacher**, type your words (one per line):

```
word | meaning | example sentence | memory tip
necessary | needed | Water is necessary for life. | One Collar, two Sleeves
```

Press **Create share link**. The whole word list is stored **inside the link**, after the `#` sign, so nothing is uploaded or saved anywhere.
Send the link on WhatsApp or Google Classroom, or show it as a QR code. Students who open it get your list.

## 🌐 Put it online free (GitHub Pages)

1. In this repository on GitHub, go to **Settings → Pages**.
2. Under *Source*, choose **Deploy from a branch**, then pick the branch and the `/ (root)` folder, and **Save**.
3. After a minute your game is live at `https://<your-username>.github.io/SpellWords/`.

You can also just copy `index.html` to a pendrive and open it offline. It works without the internet, except the spoken voice on some devices.

## ✅ Why this design is good for teaching

**For students**
- **Learning by doing.** They hear, see and type each word, so several senses work together.
- **Mistakes become lessons.** A wrong answer is never just "Wrong". The game shows the correct spelling, colours each letter (green = correct, underlined = missing, crossed = extra) and gives a memory trick.
- **A second chance builds confidence.** "Almost! Try once more" encourages careful checking instead of fear.
- **Meaning and usage, not just letters.** Every word comes with its meaning and an example sentence, which builds vocabulary too.
- **Motivating.** Points, streaks, stars and friendly praise make practice feel like a game.
- **Practise my mistakes.** One button replays only the words they got wrong, which is targeted revision.

**For teachers and the college**
- **Zero cost.** It needs no hosting fees, database, storage plan or app install. GitHub Pages hosting is free.
- **Privacy safe.** No accounts, no tracking and no student data leaves the device.
- **Custom lists in seconds.** Make a list for any lesson, subject (e.g. statistics terms) or exam and share it as a link.
- **Works everywhere.** Mobile-friendly, works on low-end phones, and has dark mode. It also works offline from a pendrive.
- **Printable results.** Students can print or save their result as a PDF for records or homework proof.
- **Easy to change.** The built-in word bank is a simple list at the top of the script in `index.html`. Anyone can add words.

## Technology

Plain HTML, CSS and JavaScript only, with no libraries. It uses the browser's built-in **Speech Synthesis** for pronunciation (Indian English voice preferred when available) and **Web Audio** for sound effects. If a device has no speech voice, Listen mode switches to Missing Letters automatically.
