# MTGA Leaderboard

The goal of this app is to have a comprehensive leaderboard for 17Lands users that lets you check the top players' event pages. Think OP.GG
for MTG Arena limited.

### What problem does this solve?

The 17Lands leaderboard is ranked by # of Match Wins by default, with options to change it to Win Rate, # of Trophies, Trophy Rate, or Latest In-game Rank. I would like to see a single leaderboard that takes into account the # of Matches Played, Win Rate, and Latest In-game Rank to get a better sense of the top limited players on MTG Arena. 

Some top players have shared the link to their event page to the public, but there is no way to access it on the 17Lands website. I currently 
have their event pages saved in my Notes app, but I would prefer to access it from the leaderboard so I can check their rank as well.


### Goals

- As a user, I can view a comprehensive, global leaderboard of 17Lands users.
- As a user, I can go directly to a ranked player's event page from the leaderboard, if available.
- I don't have to make an account to do this.

### Technical breakdown

I will likely be using a React/NextJS frontend and a Python backend. No database will be necessary. 

Since this will be a NextJS app, I'll use Vercel to deploy and host it.