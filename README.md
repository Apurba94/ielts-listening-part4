# Part 4 Lectures

Listen to short academic lectures and complete the notes with one word only, as in Part 4.

Part of the [IELTS Study Suite](https://github.com/Apurba94/ielts-study-suite): 100 free study apps for IELTS. This one is for the IELTS Academic and General Training test. It works offline, as a Windows program or in the browser.

## Download and run

- **Windows:** download `Part 4 Lectures.exe` from the [latest release](https://github.com/Apurba94/ielts-listening-part4/releases/latest) and open it. Nothing to install. It opens in its own window and saves your progress in your user folder.
- **Browser:** open it online in the suite's web edition at https://ielts-study-suite.vercel.app/apps/ielts-listening-part4/ . Progress stays in that browser.
- **From source:** `python launcher.py` (Python 3.10 or later, no packages needed).

## What it does

Listening Part 4 is a lecture on an academic subject with no break in the middle, usually with notes to complete in ONE WORD ONLY. Eight original lectures, from the history of the bicycle to coral reefs, each with nine gaps. Every answer is a word the lecturer actually says.

Sections: Lectures, Progress, About.

## How to use it

1. Before you play, read the notes and predict each gap: a noun, an adjective, a plural?
2. The notes follow the lecture in order, and headings tell you when the topic moves on.
3. Write the word exactly as you hear it, spelled correctly. One word only: no articles.

## Good to know

- All questions, passages, recordings and definitions were written for this suite. None are official IELTS questions. For official practice, use the materials on ielts.org and from the test partners.
- It follows IELTS as delivered on computer in 2026. Formats change, so check ielts.org before your test.
- Listening uses the voices installed on your computer, which sound less natural than real test recordings.
- Feedback on writing and speaking counts what a program can count honestly, such as length and linking words. It is not an IELTS band score. Band conversions for Listening and Reading are approximate.
- Not endorsed by or affiliated with the British Council, IDP or Cambridge University Press & Assessment. IELTS is a registered trademark of its owners.

## For developers

The app is plain HTML and JavaScript in `web/`, run by a small Python launcher that serves it on 127.0.0.1 only and needs a secret token for saving. Tests: `node --test "tests/*.test.js"` (29 tests) and `python -m unittest discover -s tests`. Build the .exe with `python build_exe.py`.

Built with AI assistance (Claude Code). MIT licence. By JANIN A APURBA.
