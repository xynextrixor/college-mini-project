# Lalit Pomodoro Timer

## Project overview
A customizable Pomodoro focus timer with preset focus and break durations and a custom minute input.

## Run in VS Code
1. Open `lalit/pomodoro-timer.html`.
2. Use Live Server or open it directly in a browser.
3. Select a duration or enter custom minutes.
4. Select **Start** and use **Reset** or **Pause** as needed.

## How it works
- `duration` stores the selected session length in seconds.
- `remaining` stores the remaining seconds.
- `setInterval()` reduces remaining time once per second.
- Preset buttons update duration and reset the display.
- The custom input accepts whole values from 1 to 180.
- Pausing clears the interval.
- Completion resets the display and shows a completion status.

## Viva questions

**Q1. What is Pomodoro technique?**
It is a time-management method that divides work into timed focus sessions and breaks.

**Q2. What does `setInterval()` do?**
It repeatedly executes code at a specified time interval.

**Q3. What does `clearInterval()` do?**
It stops a running interval.

**Q4. Why convert minutes to seconds?**
It simplifies countdown calculations because JavaScript updates once per second.

**Q5. How is validation implemented?**
The custom input checks that the value is an integer from 1 to 180.
