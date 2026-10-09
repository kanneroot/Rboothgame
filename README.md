# Cyber Guardian Challenge: Booth Host Guide

A cybersecurity quiz for event booths. It has 12 scenarios with a 20-second clock each, and runs in English, 繁體中文 and 簡體中文.

## 1. Setup
- Copy `index.html` to the booth device and open it in Chrome or Edge. It runs fully offline.
- Full-screen the browser (press F11) for the best booth look.
- Sound starts after the first tap. Use the speaker button at the top to mute or unmute.
- Use the same browser on the same device for the whole event, because that's where the scores are saved.

## 2. How players play
1. Enter a name or nickname on the home page and tap **Start Challenge**.
2. Answer 12 questions. Each one is shown inside a realistic scene, such as an email, a phone or a desktop.
3. After each answer, the clues in the scene are numbered and the takeaway and source are shown. Tap **Next question** to go on.
4. The results page shows the score, a rank badge, a review of all answers and the top-10 leaderboard.

You can switch language (EN / 繁 / 简) at any time, including mid-question.

## 3. Scoring
| Item | Points |
|---|---|
| Correct answer | 100 |
| Speed bonus | Up to 50, more for faster answers on the 20-second clock |
| Streak multiplier | x1.2 for 2 in a row, rising to x2 at 5 or more |

Ranks go by number of correct answers, from **Security Rookie** up to **Cyber Guardian** (12/12).

## 4. Automatic behaviour
| Situation | What happens |
|---|---|
| Home page idle for 25 seconds | The attract screen shows ("Touch to play" in all three languages) |
| Player walks away mid-game | Returns home after 90 seconds. The round is saved as incomplete |
| Results page left open | Returns home after 60 seconds |
| Page refreshed mid-game | The player is offered **Continue** |
| Host dashboard left open | Returns home after 5 minutes |

Every answer is saved the moment it's given.

## 5. Host dashboard
- **Open:** long-press the Ricoh logo on the home page for 1.5 seconds, or tap the faint gear at the bottom left.
- **PIN:** `1234` by default. You can change it inside the dashboard.
- **Shows:**
  - Player count, plus completed and incomplete rounds
  - Average score, correct rate and answer time
  - The hardest and easiest question
  - For each question: correct %, an A-D answer chart and average time
  - Recent rounds

## 6. Exporting results as CSV
Open the host dashboard and use the export buttons:

- **Summary CSV:** one row per question. It has the question number and title (with the Chinese titles), the correct answer, total responses, correct count and %, A/B/C/D counts, a no-answer count and average response time.
- **Raw responses CSV:** one row per player per question. It has the round ID, player name, round status, start time, timestamp and local time, language, question number, chosen answer, correct answer, whether it was correct, time taken (ms) and points.

Files go to the device's Downloads folder and are saved as UTF-8 with BOM, so Excel shows the Chinese correctly.

## 7. Clearing data
In the host dashboard, tap **Clear all data** and type `DELETE` to confirm. **Export both CSVs first.** Clearing can't be undone.

## 8. Answer key
| No. | Topic | Answer | Takeaway |
|---|---|---|---|
| 1 | Suspicious email | B | Avoid the link. Report it through a trusted channel. |
| 2 | Stronger passwords | D | Use a long, unique password for each account, with an approved password manager. |
| 3 | Multi-factor authentication | A | MFA adds another type of identity check beyond the password. |
| 4 | Unexpected approval request | C | Reject sign-ins you didn't start, and tell IT/security. |
| 5 | QR code check | B | Check with HR through a contact you already trust. |
| 6 | Software updates | A | Install approved updates promptly. |
| 7 | Supplier payment change | D | Call a known supplier contact using the details on file. |
| 8 | Unknown USB drive | C | Keep it unplugged and hand it to IT/security. |
| 9 | Leaving your desk | A | Lock the screen. |
| 10 | Sharing a confidential file | D | Use an approved tool with access only for named people. |
| 11 | A familiar voice | C | Call your manager back on a known number to verify. |
| 12 | After a suspicious click | B | Contact IT/security immediately through a trusted channel. |

## 9. Important notes
- **Saved data:** data stays only in that browser on that device. Clearing browser data or switching browser or device loses it. Two booth devices don't share a leaderboard. Export regularly.
- **Chinese text:** the Chinese translations were machine-prepared, so have someone review them before the event.
- **Content:** scenarios are illustrative, and all names, numbers and websites in them are fictional.
- **Graphics and sound:** all graphics are drawn in code and all sounds are generated in the browser. There are no third-party assets or libraries. The Ricoh logo is the only supplied image.
