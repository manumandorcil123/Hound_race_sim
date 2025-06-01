# Greyhound Race Simulator  
**Author:** Manu Dorcil  
**Date:** 08 May 2025  
**Language:** C# (Console App)  
**Project:** AUT Programming Assignment – Greyhound Racing Simulation

---

## About  
This program simulates a greyhound race where users can name between 6 and 8 dogs, choose the type of race (sprint, middle distance, or marathon), and watch each round of the race play out with live updates.

Each dog gets a random score per round, and a simple graph using stars shows how far each dog has progressed. The race finishes by ranking the top 3 dogs. Users can run another race straight after without restarting the program.

---

## Features  
- User names 6–8 greyhounds  
- Race type selection:  
  - Sprint (6 rounds)  
  - Middle Distance (10 rounds)  
  - Marathon (12 rounds)  
- Randomised movement for each dog per round  
- Star-based graph updates after each round to show progress  
- Final total scores and placings displayed at the end  
- Option to repeat the race without closing the program

---

## How to Use  
1. Run the program in Visual Studio or another C# IDE.  
2. Enter how many dogs are competing (between 6 and 8).  
3. Enter each dog's name.  
4. Choose the race type.  
5. Watch the progress graph update each round.  
6. View the final results and choose whether to run another race.

---

## Sample Output (Progress Graph):
```
--- Round 3 of 6 ---

Buddy     : ****** (12)
Shadow    : ***** (10)
Rocket    : ******* (14)
```

---

## Why I Built It  
This assignment helped me practice:
- Loops, conditionals, and input validation  
- Working with 1D and 2D arrays  
- Using random numbers  
- Showing progress in a simple visual format  
- Sorting totals and determining race winners

It also helped me learn how to keep the program organised and responsive to user input.

---

## AUT Requirements Met
- User names between 6 and 8 greyhounds  
- User chooses race type (sprint, middle distance, or marathon)  
- Race progress is based on random values  
- Live race progress is visualised round-by-round  
- Top 3 dogs are displayed at the end  
- User can repeat the race without restarting
