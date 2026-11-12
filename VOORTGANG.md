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
