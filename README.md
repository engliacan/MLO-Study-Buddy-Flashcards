[README.md](https://github.com/user-attachments/files/26198476/README.md)
# MLO Study Buddy Flashcards

A mobile-friendly flashcard app for studying for the Mortgage Loan Originator (MLO) exam. Works on iPhone and Android as a home screen web app.

## Features

- **703 flashcards** covering all MLO exam topics
- **5-day study plan** — cards organized by Monday through Friday reading schedule
- **Multiple study modes** — All cards, random shuffle, custom count, weakest cards, or favorites
- **Card mastery tracking** — Cards level up from New → Learning → Known → Mastered
- **Session history** — Track your scores and progress over time
- **Timed mode** — Add a countdown timer for test pressure
- **Flip direction** — Study Question → Answer or Answer → Question
- **Search** — Find any card instantly
- **Favorites** — Star tricky cards for focused review
- **Streak tracker** — Stay motivated with daily study streaks
- **Dark / Light mode**
- **Works offline** — Cards are cached after first load
- **Auto-update notifications** — App detects when flashcards have been updated and prompts users to download the latest version

## Study Plan

| Day       | Parts   | Topics |
|-----------|---------|--------|
| Monday    | 1–3     | TRID, RESPA, TILA |
| Tuesday   | 4–16    | ECOA, Fair Housing, HMDA, FCRA, GLBA, DNC, Patriot Act, and more |
| Wednesday | 17–24   | Dodd-Frank, SAFE Act, CFPB, HUD, FHA/VA/USDA, Appraisals, Amortization |
| Thursday  | 25–35   | Liens, Title, Deeds, Mortgages, ARMs, Construction, Clauses |
| Friday    | 36–40   | Flood Insurance, Mortgage Terms, Underwriting, Ethics, Foreclosure |

## How to Use

1. Visit the site on your phone's browser (Safari on iPhone, Chrome on Android)
2. **iPhone:** Tap Share → Add to Home Screen | **Android:** Tap the menu → Add to Home Screen
3. Pick a study mode and start studying
4. Cards work offline after the first load

## Updating Flashcards

Edit `flashcards.csv` in this repo. The format is:

```
Question,Answer,Category
What is TRID?,TILA-RESPA Integrated Disclosures,Monday
```

- **Column A** — Question
- **Column B** — Answer
- **Column C** — Day of the week (Monday through Friday)

Users can tap the refresh button in the app to pull the latest cards. The app also checks for updates automatically — if the flashcards have changed since the last download, an "Update Available" banner will appear on the home screen.
