Greyhound Race Simulator
Author: Manu Dorcil
Date: 08 May 2025
Language: C# (.NET Framework)
Project Type: Console Application
Purpose: Simulates a greyhound dog race with visual progress and ranking.

🎯 Description
This program simulates a race between 6 to 8 user-named greyhounds. Users choose a race type (sprint, middle distance, or marathon), and the race is simulated round-by-round with randomly generated performance values.

Each round displays a live graph of each dog's progress using a visual star (*) system. At the end, the top 3 finishers are announced. The user has the option to restart and run another race without closing the program.

🛠 Features
Input validation for number of dogs and race type.

Three race lengths:

Sprint: 6 rounds

Middle Distance: 10 rounds

Marathon: 12 rounds

Random scoring system per dog, per round.

Live visual feedback using stars * to represent total score/progress.

Displays total score per dog.

Ranks and announces top 3 finishers.

Option to run multiple races in a single session.

🧪 How to Run
Open the solution in Visual Studio or any C# IDE.

Build and run the program.

Follow the console prompts to:

Enter number of dogs (6–8)

Name each dog

Select race type

Watch the race progress

At the end, choose whether to race again.

📦 File Structure
bash
Copy
Edit
Assignment_Greyhound/
│
├── Program.cs     # Main C# program logic
├── README.md      # Project overview and documentation
 Example Output (Live Race Snapshot)
markdown
Copy
Edit
--- Round 3 of 10 ---

Bolt      : ********** (10)
Shadow    : ******** (8)
Flash     : *********** (11)
...
✅ Requirements Met
✅ User can run new races without restarting the program.

✅ Live race graph with visual progress per dog (scaled star chart).

✅ Valid input handling for dog count and race type.

✅ 1D and 2D arrays for dynamic data storage.

✅ Logical flow with loops, conditions, and sorting.

Educational Purpose
This project was developed to demonstrate:

Control flow (loops, conditionals)

Arrays and multi-dimensional data

Random number generation

Basic console UI and text-based graphics

Object-oriented logic structuring (basic)