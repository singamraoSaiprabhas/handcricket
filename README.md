# handcricket

This project is a Hand Cricket web application, a digital version of the popular schoolyard game where players use their fingers to score runs or take wickets. It provides a clean, modern interface for a single-player experience against a "smart" CPU.

# Core Project Features
Game Mechanics: The game simulates a standard two-innings cricket match. Players choose a number between 1 and 6; if the numbers chosen by the player and the CPU match, the batsman is "Out." Otherwise, the batsman scores the number of runs they selected.

Adaptive CPU AI: The game includes a "Heuristic" CPU strategy. It tracks the player's recent moves to detect patterns and bias its choices to either score more effectively or increase the chance of getting the player out.

Integrated Toss System: Before the match starts, users engage in a realistic "Odd or Even" toss to decide who bats or bowls first.

Dynamic UI & Commentary: The interface features a live scoreboard tracking runs, balls, and targets, alongside a real-time "Commentary" log that describes every ball's outcome.

Advanced Controls: Users can "Undo" the last ball if they make a mistake or "Forfeit" a match if they want to restart.

# Technical Implementation
Language: The project is built entirely as a static web page using HTML5, CSS3, and Vanilla JavaScript.

Responsive Design: It uses CSS Flexbox and Grid to ensure the game is playable on both desktop monitors and mobile devices (using a vertical layout for smaller screens).

State Management: The game's logic is driven by a central state object in JavaScript that tracks innings, scores, roles, and match history.

Visual Style: The app features a professional "Dark Mode" aesthetic using CSS variables, blurs (backdrop-filter), and linear gradients.

# How to Play
The Toss: Pick "Odd" or "Even," enter a number, and click "Toss."

Batting: If you are batting, click a number (1–6). Your score increases by that number unless the CPU picks the same number.

Bowling: If you are bowling, try to guess what the CPU will pick. If your numbers match, the CPU is out.

Winning: Complete the overs or reach the target score in the second innings to win the match.
