# Lexico backend server data

This server is used to hold a json of all server-side data needed for a client to run Lexico. This includes:
- Data about the game difficulty and functionality such as but not limited to the frequency values of letters, penalty for strikes, progression and value information about the bonuses as well as descriptive information about the game
- Posted rankings from clients
- Puzzles and their data

Key guide:
- gameData
  - info (Text to be provided to Lexico's PopUpBoard)
  - valueData (Base value of puzzles, value of strikes, puzzle value variation range, letter frequency values)
  - bonusData (Array of bonus data objects concerning the function and value of bonuses)
- rankings (Array of ranking objects)
- puzzles (Array of puzzle objects)

Maxwell Gottesman | mxgtsmn@gmail.com