# ReadingRush | AppADay 201

ReadingRush is a timed reading comprehension trainer that runs in one browser tab. Claude writes original passages by fictional authors, then questions in three categories: Key Ideas and Details, Craft and Structure, and Integration of Knowledge and Ideas.

## Modes

The Boss Round has 36 questions across four passage sets, one of them a paired set of two passages. It runs on a 40 minute timer with a 67 second pace target, and it submits automatically at zero. The Drill has 9 questions on one passage with a 10 minute soft timer.

## How it works

Every answer comes with an explanation, and each wrong choice has a trap note that names the reasoning error it represents. Correct answers earn 10 XP, answers under pace earn 5 more, and completing a round earns a bonus. A 1.1 multiplier applies at a streak of three days or more. Category weighting starts from a 60 percent prior and shifts questions toward weaker categories as results come in.

## Privacy and data

Progress is stored only in this browser under the key readingrush.v1. Settings can export and import that progress as a JSON file, and reset it. The Claude key is managed by the shared AppADay key ring, which asks for it once when no key is stored.

## Files

The whole app is one file, `index.html`, with no build step. It loads `save.js`, `models.js`, and `keys.js` from the AppADay portal, plus Google Fonts.

## Portfolio

Part of [AppADay](https://augustineiacopelli.github.io/appaday/), one app built and shipped every day.
