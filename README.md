# Upkeep

A single-page lifestyle app with four sections, built to grow:

- **Cookbook**: recipes with photos, scaling by servings, macros per serving, step-by-step cooking mode with timers, weekly meal plan, grocery list.
- **Gym**: workout templates by weekday, set logging with last-session numbers, rest timer, personal bests, progress charts, body weight log.
- **Wardrobe**: closet with photos, outfits, wear counts, laundry status, colour-pairing hints, gaps and wishlist.
- **Grooming**: daily and weekly routines, product shelf with expiry dates, wishlist, care log, progress photos, recurring reminders.

Home shows today's workout, routines, meals, outfit and a streak heat map. Five colour themes, each with light and dark.

## Run it

It is one file with no build step. Open `index.html` in a browser, or serve the folder (for example with GitHub Pages).
Data is stored in the browser's local storage on that device only. Photos are shrunk before saving.

The version published inside Claude syncs each person's private data across devices through the page's database.
This copy does not sync.

## Add a section

Add an entry to the `SEC` list in `index.html` and write its render function. The nav bar builds itself from that list.
