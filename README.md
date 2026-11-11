# Ankith Mareddy

Technology Product Analyst at Farmers & Merchants Bank. I build AI agents, automations, and data products that save people time and money — at work, and for my friends.

UIUC: B.S. Finance and Information Systems, M.S. Business Analytics · [LinkedIn](https://www.linkedin.com/in/ankithmareddy/)

Most of what's here started because a group of friends needed something: a trip that had too many moving parts, a fantasy league nobody could keep up with, a movie club that kept forgetting what it had watched. They all got used by real people, which is the part that shaped them.

## Projects

**[tagalong](https://github.com/AnkithMareddy/tagalong)** — A travel agent that lives in your group chat. Drop in the places you saved from Google Maps, Instagram and TikTok; it builds the days, then follows the group through the trip: leave-now alerts with live transit times, what's nearby in the gap before your next booking, screenshots turned into check-in reminders, and expenses settled through Splitwise. Built for a London city break and an Ireland road trip and run live for five of us, then generalised so anyone can deploy it for their own trip.
<br>*Node.js · Claude API · Telegram Bot API · Railway*

**[Reel Studio](https://github.com/AnkithMareddy/reel-studio)** — An AI video editor that turns a day's GoPro and iPhone footage into story-driven Instagram, TikTok and YouTube edits overnight, cut to the beat and colour-graded. Everything is analysed, transcribed and rendered on the Mac; only contact sheets and transcripts go to Claude to plan the story, and it falls back to a rule-based editor with no API key at all.
<br>*Python · FFmpeg · Whisper · Claude API*

**[fantasy-football](https://github.com/AnkithMareddy/fantasy-football)** · **[live dashboard](https://ankithmareddy.github.io/fantasy-football-hub/)** — A model for one 12-team league that grew into three things: a draft-night assistant, a nightly advisor that texts itself, and an arcade the league can play. 10,000-season Monte Carlo odds, start/sit that looks off the roster at the waiver wire and prices the pickup in win probability, and injury scanning on every refresh. It has run unattended since September.

The interesting part isn't the simulation — it's [the record of being wrong](https://github.com/AnkithMareddy/fantasy-football/blob/main/docs/EVOLUTION.md). The model was picking lineups in hindsight, worth 3-4 points a week. A decision game shipped 100% solvable by one rule, and then, once fixed, was found grading week-4 calls with week-17 knowledge under a banner reading "No hindsight." A projection source nearly replaced the season baseline on a backtest that had been measured on the wrong population. All three are written up, with what each one did to the numbers.
<br>*Python · Sleeper/ESPN/nflverse APIs · launchd*

**[Reel Club](https://github.com/AnkithMareddy/reel-club)** · **[live app](https://reel-club-eight.vercel.app)** — Letterboxd meets a standing movie club. Form a club, nominate films, settle it with ranked-choice voting, then rate and review together once the credits roll — and keep the history: who rates generously, whose picks everyone actually liked, what your group's taste looks like over a year.
<br>*Next.js · TypeScript · Supabase · Prisma · Auth.js*

## Tools

Python · SQL · TypeScript · Dagster · Snowflake · Power BI · Claude API · Next.js · Supabase
