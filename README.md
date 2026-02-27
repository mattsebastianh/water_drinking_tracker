## Hydrate – Daily Water Tracker

Hydrate is a minimalist single-page web app for tracking your daily water intake. It visualizes your progress in a glass-style vessel, shows your current total vs. goal, keeps a log of each drink, and tracks day streaks when you meet your goal.

### Features
- **Animated water vessel**: Shows your percentage progress toward the daily goal.
- **Quick-add buttons**: Log common drink sizes (150ml, 250ml, 500ml, 750ml) in one click.
- **Custom amounts**: Enter any milliliter value to log a custom drink.
- **Daily goals**: Choose from preset goals (1500–3000ml).
- **History log**: See all drinks logged for the current day.
- **Streak tracking**: Tracks how many consecutive days you’ve reached your goal.
- **Local storage**: All data is stored locally in your browser; no backend required.

### How to use
1. **Open the app**
   - Double‑click `water_tracker.html`, or open it from your browser via `File → Open` (works in Chrome, Firefox, Safari, Edge).
2. **Set your daily goal**
   - Use the **Daily Goal** buttons (1500–3000ml) to choose your target. The current goal is shown under the glass.
3. **Log your drinks**
   - Use the **Quick Add** buttons to instantly add common amounts, or type a custom value (in ml) and press **+ Add** or hit Enter.
4. **Check your progress**
   - Watch the animated glass fill up, and read your **ml today**, **ml goal**, and **ml left** stats below it.
5. **Review today’s log**
   - Scroll through **Today’s Log** to see each drink with time and amount. Use the ✕ button to remove a single entry if needed.
6. **Reset the day**
   - Click **Reset Day** to clear today’s log and totals. Your streak is only advanced when you reach your goal before the next day.

### Development Notes
- **Tech stack**: Pure HTML, CSS, and vanilla JavaScript (`water_tracker.html` + `styles.css`).
- **Persistence**: State is saved in `localStorage` under the key `hydrate-state`.
- **Customization**:
  - Edit `styles.css` to change colors, fonts, and layout.
  - Edit `water_tracker.html` to adjust default goal values, quick‑add amounts, or copy tweaks.

