# Valley Residents Atlas

Pixel-art maps showing where every resident lives in Stardew Valley's Pelican Town, the Stardew Valley Expanded valley, the Ridgeside Village mod, and the East Scarp mod. Tap a sign to see who lives there and their loved gifts. It's built for phones: a sticky search bar with live results, a bottom map bar, and a bottom sheet for home details.

Features: a "Where is everyone?" time-of-day view (morning, afternoon, evening, night) based on usual schedules, pick which mods you play (the map tabs, villagers and gifts follow), search by villager, home or gift, filter to romanceable villagers, star favorites, a birthday calendar with an "up next" line, and offline use once it's been opened.

It's a single `index.html` file with no build step and no dependencies. Open it in a browser, or host it with GitHub Pages.

## Notes

- The map art is original. Building positions follow each wiki's location descriptions, so they're close but not exact.
- Loved gifts come from the Stardew Valley Wiki, the Stardew Valley Expanded Wiki, and the Ridgeside Village Wiki. Game-wide "universal" loves are left out.
- The time-of-day view uses each villager's usual schedule for a chosen season, weekday and weather. Base-game schedules come from a public data dump of the game files, East Scarp's from the mod files. Festivals, story events and friendship-heart schedules are not included, and Expanded and Ridgeside villagers stay at home because their schedules aren't loaded yet.
- East Scarp gifts, birthdays, romance flags and door positions were read from the mod's own data files (version 3.0.x), and item IDs were matched to names. Expanded and Ridgeside birthdays also come from the mods' data files. Villagers with no birthday in the files show none.
- This is a fan-made reference and isn't affiliated with ConcernedApe or the mod authors.
