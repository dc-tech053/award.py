## Summary of `award.py`

This is a simple Python program that awards prizes based on a triathlon completion time. Here's what it does:

**Functionality:**
1. **Collects User Input**: Prompts the user to enter their finish times (in minutes) for three triathlon events:
   - Swimming
   - Cycling
   - Running

2. **Calculates Total Time**: Adds up all three times to get the total minutes

3. **Awards Prizes** based on total completion time:
   - **≤ 100 minutes**: Provincial Colours (best award)
   - **101-105 minutes**: Provincial Half Colours
   - **106-110 minutes**: Provincial Scroll
   - **≥ 111 minutes**: No award

The program uses conditional statements (`if`/`elif`/`else`) with comparison operators to determine which award tier the user qualifies for based on their performance.
