Bodyshop Tracker - Worker Availability Calendar update

Files in this package:
- index.html: updated app with the Worker Availability Calendar at the top of the Workers tab.
- sw.js: service worker cache version increased to v6 so the updated app can replace the older cached version.

To update your GitHub Pages app:
1. Open your bodyshop-tracker GitHub repository.
2. Replace the existing index.html in the repository root with this index.html.
3. Replace the existing sw.js in the repository root with this sw.js.
4. Keep your existing manifest.webmanifest, icon-192.png, icon-512.png and other app assets unchanged.
5. Commit the changes to the main branch and wait for the Pages deployment to finish successfully.

Calendar behaviour:
- Shows ongoing vehicles using their existing worker assignments.
- Each worker has a consistent colour.
- A vehicle is shown from its arrival date through its expected delivery date.
- If a vehicle is still ongoing after its expected delivery date, it remains shown through today.
- If no expected delivery date is entered, it is shown from arrival through today only.
- Select one worker to see their scheduled vehicle count, booked days and days with no booking in the selected month.
- Select a calendar date to see that day's bookings. Select a vehicle booking to edit that vehicle.
- This is a day-based calendar, not an hourly appointment planner.
