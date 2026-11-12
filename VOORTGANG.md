A: Trys
B: Manny 

# 🧠 Kennischeck


- Wat is het verschil tussen de docenten-template, jullie repository en een clone?
>De docent template is het startproject, onze repository is ons eigen project. Een kopie waarmee wij werken

- Waarom ziet je partner een wijziging pas na jouw push en diens pull?
> Omdat je de code lokaal wijzigt en pas deelt waneer je hem pusht

- Welke bestanden worden bij de installatie lokaal aangemaakt?
> .env, de SQLite db, vendor en node_modules

- Waarom krijgt je partner jouw games niet via GitHub?
> Omdat het database bestand voor veiligheid niet word gedeelt. ieder heeft een eigen db

- Waar wordt de titel gecontroleerd en hoe komen de games bij React terecht?
> in app.tsx
```js
const appName = import.meta.env.VITE_APP_NAME || 'Laravel';
```





# 🧠 Kennischeck
- Why does the status have a Laravel route and needsave()?
> React only changes the screen. The route sends the change to Laravel, and save() stores it in the database so it’s still there after a refresh.

- What is the difference between logging in and owning a game?
> Logging in = the site knows who you are. Owning a game = the game is linked to your account, so only you can change it.

- What are props and state in this page?
> Props = data coming into the page (like the games list from Laravel). State = data the page changes itself (like the search text).

- Why does the progress and resultsgames counter usevisibleGames ?
> It’s the list after search and filters. The counter should show what you actually see, not the full list.

- Why doesn't “Wis search” need a database?
> It only clears the search text. All games are already loaded in the browser, so nothing new has to be fetched.

- What code did you create, test and transfer yourself via GitHub?
> I wrote the search filter (visibleGames) and the completed counter (completedCount) in the Game Backlog page