# Research Notes

Checked on April 13, 2026.

- Official NBA game page supplied for this project: `https://www.nba.com/game/chi-vs-dal-0022501193`
- Official NBA live-data boxscore endpoint used for raw stats: `https://cdn.nba.com/static/json/liveData/boxscore/boxscore_0022501193.json`
- ESPN/AP recap cross-check: `https://www.espn.com.sg/nba/recap?gameId=401811048`

Verified core facts:

- Game ID: `0022501193`
- Game code: `20260412/CHIDAL`
- Final score: Dallas Mavericks 149, Chicago Bulls 128
- Date/time: April 12, 2026, 8:30 PM ET
- Arena: American Airlines Center, Dallas, Texas
- Attendance: 20,232
- Quarter scoring: Chicago 34, 22, 32, 40; Dallas 45, 35, 39, 30
- Dallas team stats: 52-of-100 FG, 22-of-49 3PT, 23-of-27 FT, 61 rebounds, 35 assists, 97 bench points
- Chicago team stats: 52-of-106 FG, 10-of-38 3PT, 14-of-19 FT, 52 rebounds, 30 assists, 63 bench points
- Dallas leaders used: John Poulakidas 28 points, Ryan Nembhard 15/9/23, Moussa Cisse 17/20, Tyler Smith 20/7
- Chicago leaders used: Rob Dillingham 25/5/5, Collin Sexton 19, Lachlan Olbrich 10/15/10, Leonard Miller 17/7

Editorial approach:

- Write an original recap rather than reuse the wire recap.
- Use official NBA boxscore data for exact numbers.
- Use ESPN/AP only to cross-check the reported rookie-record note and injury context.
- Avoid team logos, copied photos, and competitor images.
