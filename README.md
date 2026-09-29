# Caralta · interactive prototype

Caralta is a car expense tracker I designed at Clarice Technologies. This repo rebuilds it as a clickable, mobile-first prototype for my portfolio.

- **Live prototype:** https://abhishek98604-commits.github.io/caralta-prototype/
- **Phone-frame version (for embedding):** https://abhishek98604-commits.github.io/caralta-prototype/embed.html

## What you can do

- Swipe between three screens: overview, expenses and nearby places
- See spending by month, split into gas, service and repairs
- Add an expense (pick a category, describe it, enter the amount and date) and watch the totals update
- Open, filter and delete expenses
- Find nearby fuel stations, service centres and repair shops on the map
- Get turn-by-turn directions that follow the streets, then press Start to watch the drive play out
- Tap the car name at the top to switch between the Accord and the Camry, and check reminders

## Notes

- Colours, layout and the Accord photo come from the original design file. Avenir is swapped for the free Nunito Sans. The map is a simple drawn street grid, and routes are worked out on it with a shortest-path search.
- Camry photo by [Frederick Shaw](https://unsplash.com/@dropfastcollective) on [Unsplash](https://unsplash.com/photos/p0Iq45ZfVUU).
- Amounts, places and reminders are sample data. Fuel costs are litres times 2017 Bangalore petrol prices, so yearly totals, distances and resale values are in a realistic range. No calls, navigation or uploads happen.
- One HTML file, no build step. State lives in memory and resets on reload.

Designed by Abhishek Bora.
