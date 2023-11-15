Bug 1: Pressing the button "Show Finished Habits"
reveals a comprehensive list of habits that
are still in progress.

Steps: Modify filteredHabits function.

- Use the filter method to create a new 
array based on the specified condition.
- Check the value of showUnfinished to
determine the filtering condition.
- Return true if habit.goalDays is
greater than 0 (unfinished habit).
- Return true if habit.goalDays is
equal to 0 (finished habit).

Bug 2: Adjust the date range display.

Steps: Adjust the span that corresponds 
to the selected date range.

-Enclose each line in its own <div> element.

Bug 3: Stylize the text and ensure that
the button is centered for an improved
visual appearance.

Steps: Change clasNames and modify styles.

Bug 4: Adapt the style of the skill bar
to align with the main application and
ensure compatibility with the dark theme.

Steps: Modify index.css

