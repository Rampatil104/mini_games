Made by Ram
 I built this Mini Games Hub as a fun offline project.
It's a single HTML file that contains twelve small games.
The design uses a dark, gamey UI so it looks cool.
I used plain HTML, CSS, and vanilla JavaScript — no libraries.
Canvas is used for real-time graphics in many games.
Each game has its own area inside the same page.
I focused on making controls responsive and easy to use.
I added keyboard support like arrows, WASD and spacebar.
Mouse interactions are used for clicks, shooting, and card flips.
The games use timers, intervals, and simple physics for movement.
For collision detection I used distance checks and bounding boxes.
I kept the code readable so other students can learn from it.
Comments and short function names make the logic easier to follow.
The Tic-Tac-Toe game has a simple AI and human-vs-human mode.
Snake uses a grid system and wraps around screen edges.
I tested gameplay often and fixed many small bugs during development.
I focused on keeping each game independent so it’s easy to debug.
The page is responsive so it works on phones and laptops.
I used a simple color palette with teal accents for a modern look.
Status messages tell the player what’s happening during every game.
The Number Guess game gives limited attempts and simple hint logic.
Coin Flip has a small animation effect and a result counter.
Shooting uses many moving small balls and click-to-hit mechanics.
Flappy has gravity, pipes, and a simple flap mechanic bound to space.
Pong uses a mouse-driven paddle and a basic AI opponent.
Memory uses paired cards shuffled randomly each round.
Simon builds a sequence that the player repeats, growing each round.
Whack-a-Mole spawns temporary active holes the player can click.
Catch generates falling items and a controllable bucket at the bottom.
Each canvas game draws shapes and updates positions every frame.
I kept frame updates at reasonable intervals for smooth gameplay.
The snake logic advances the head and moves the body accordingly.
Food placement avoids the snake body by re-rolling positions.
The shooting targets bounce off walls using inverted velocities on edges.
Flappy spawns pipes with a constant gap and moves them left.
Pong handles collisions by reversing the ball and slightly speeding it.
Memory flips cards visually and compares values with a short delay.
Simon highlights buttons by changing opacity briefly during the sequence.
Whack-a-Mole uses a timer to spawn active holes at random positions.
Catch adds new falling items with randomized x positions and speeds.
The UI uses a sidebar menu to switch between games seamlessly.
Menu buttons toggle the active game and highlight the selected item.
I used CSS grid to lay out the main panel and the sidebar cleanly.
Cells and cards use border radiuses and semi-transparent backgrounds.
Buttons are styled with rounded corners and bold text for clarity.
Inputs have minimal styling to match the overall aesthetic.
I added small helper texts so players understand controls quickly.
Every game updates a score or status element for instant feedback.
Reset and New buttons allow quick restarts without reloading the page.
Start/Reset buttons control timers and game state for a clean flow.
The project is intentionally single-file to make offline sharing easy.
You can save the file and open it in any modern browser locally.
No server or build step is required — just open the HTML file.
That makes it great for showing to friends or classmates quickly.
I used simple randomness functions for spawn positions and AI choices.
The Tic-Tac-Toe AI checks for winning moves then blocking moves.
When no immediate move is found, the AI prefers the center square.
The AI then picks a random available corner or side position.
This keeps the AI simple yet competitive for casual players.
For number guessing I limited attempts to keep games short and fun.
Hints reduce attempts, so use them wisely during gameplay.
Coin flips are pseudo-random and counted so you can track runs.
Snake uses modular arithmetic to wrap the head at edges nicely.
I used small grid cells to keep the snake movement crisp.
The snake collision uses a loop to check if head equals any body part.
Shooting detects hits by comparing pointer coordinates to target centers.
When a target is hit it is removed from the array to score a hit.
Flappy collision detection checks bird against pipe gaps by rectangles.
Pong AI simply moves toward the ball’s y position each frame.
Pong ball reflection changes slightly to avoid boring straight rebounds.
Memory tracks matched pairs and notifies the player when they win.
Simon stores the sequence as an array and plays it back with timeouts.
Whack-a-Mole toggles hole active states and increments score on hits.
Catch increases score when items land inside the player bucket area.
I separated logic sections with comments for easy navigation in code.
Functions are grouped by game so you can jump to a game fast.
Variable names are chosen to be descriptive for learning purposes.
I left small helper messages for potential future contributors.
The layout uses a max-width so it looks good on wide screens too.
I included a footer with my name and a small call-to-action.
The footer invites players to message me on Instagram if they need help.
I deliberately avoided external fonts to keep the file self-contained.
The entire app runs purely in the browser and uses local memory only.
No cookies, no tracking, and no network calls are made by the page.
Because of that, it’s privacy-friendly and works offline without issues.
Controls are consistent across games to avoid confusing new players.
Spacebar, arrows, WASD, and mouse clicks form the core control set.
I tried to make the game difficulty approachable for beginners.
Timings and speeds are balanced for casual fun rather than hardcore play.
I kept artwork minimal so the focus stays on gameplay and code.
The visual style is clean and modern, with soft shadows and rounded corners.
I used subtle gradients for the background to add depth to the UI.
Status texts are muted to not distract but still provide feedback.
Important actions like New or Start are highlighted with accent color.
Some small animations improve feel without costing performance.
The coin flip uses a quick CSS-triggered animation for flair.
Buttons change slightly on hover to show interactivity to the user.
I structured event listeners to only react when their game is visible.
That prevents accidental input affecting other games in the background.
The game panel area has its own scroll so the sidebar remains visible.
I included instructions inside the sidebar so players don't get stuck.
Where appropriate I added attempt counters to make challenges clear.
Score elements are placed where players can easily see them during play.
I made the board sizes adjustable through CSS so it can be tuned.
Responsive rules shrink grid sizes on narrow screens for better fit.
Small screens will see the sidebar collapse into a vertical layout.
On desktop the grid uses fixed sizes for tidy alignment and spacing.
I kept game state resets deterministic to make debugging simpler.
Timers are cleared on reset to avoid runaway intervals after restarts.
I wrote helper init functions to centralize state initialization for each game.
This reduces duplicate code and makes maintenance easier later.
Collision math is intentionally simple so beginners can follow it.
I occasionally used helper arrays to track grid occupancy and positions.
Random seeds are not fixed — each session feels fresh and unpredictable.
I tested the file in multiple browsers to ensure cross-browser compatibility.
Canvas contexts are obtained carefully and checked for null to avoid errors.
I used requestAnimationFrame-like intervals (setInterval with tuned timing) for updates.
Frame rates are chosen to balance fluid motion and CPU usage.
Games are intentionally lightweight to run on older machines too.
The code avoids heavy computations inside tight loops for performance.
Rendering draws only what needs to change each frame to save work.
I avoided images to reduce file size and keep everything text-based.
Shapes, colors, and simple rectangles convey gameplay clearly without sprites.
This also makes the project friendly for learning graphics fundamentals.
Anyone can open the file and inspect the code to see how it works.
The project is a great demo for simple game mechanics and UI layout.
It’s also a useful learning resource for HTML, CSS, and JS beginners.
Students can use it to study event handling, game loops, and collisions.
Teachers could use it as a quick in-class example for small projects.
The code is short enough to be copy-pasted into smaller examples.
I kept function scopes local where possible to avoid global pollution.
Where globals are used they are minimal and clearly named for clarity.
I favored clarity over micro-optimizations for ease of reading.
That makes the project useful as an educational example more than a production app.
If someone wants to expand a game they can add more obstacles or powerups.
For example, Snake could get speed-up items, or Flappy could add coins.
Memory could be extended with more cards and increasing difficulty per round.
Simon could add sound effects or color gradients for variety.
Pong could implement two-player mode or score limits with win conditions.
Shooting could add moving obstacles and different target sizes for challenge.
Whack-a-Mole could add faster spawn intervals as scores climb.
Catch could add special items worth more points or negative items to avoid.
I included small UX touches like disabling controls when waiting for animation.
This prevents players from breaking sequence timing by clicking too fast.
I also added tiny delays after matches to give visual confirmation of events.
Those delays make the game feel less abrupt and more polished.
I left TODO comments suggesting places where features could be added.
Future contributors can add sound effects using the Web Audio API.
They could also persist high scores in localStorage for a leaderboard.
Another option is to break the file into modules for better organization.
But for offline simplicity I kept everything in one file for now.
The file serves as a compact portfolio piece that you can show anywhere.
It’s perfect for a GitHub Gist or for sending to friends in class.
You can also use it to practice debugging in the browser console.
Open DevTools to step through functions and watch variables change live.
Breakpoints help you see exactly when collisions or score increments happen.
I left many small console-safe operations to make debugging straightforward.
If you want to reuse parts, copy canvas setup and the update loop.
Many games share the same pattern: init, start, update, draw, reset.
Understanding that pattern helps build more complex games later on.
This project is a stepping stone to bigger projects like platformers.
It’s also useful for learning basic AI concepts in a friendly setting.
Tic-Tac-Toe AI demonstrates simple conditional logic and board evaluation.
Pong AI shows how tracking and basic predictive motion works.
Small physics in Flappy and Catch show gravity and velocity concepts.
Shooting demonstrates simple vector math for collisions and bounces.
Memory and Simon reinforce sequence memory and pattern recognition for players.
Whack-a-Mole trains reaction time and simple target prioritization.
Snake builds spatial awareness and planning to avoid self-collision.
Number Guess uses probability and elimination strategies for fun learning.
Coin Flip demonstrates pseudo-randomness and stateful counters for users.
The UI tone is casual and friendly, written like a student-made page.
I tried to keep text approachable, so other teens can read it easily.
Short statuses and clear labels reduce the chance of confusion.
I included a small “Controls” list so players know key bindings quickly.
The page can be extended with localization if you want other languages.
But English keeps it simple for the widest audience of classmates.
I wanted the file to be a learning tool and a fun time-waster too.
It’s the kind of project you show a friend to say “I made this.”
You can modify values like speed or grid size to change difficulty.
Changing intervals will increase frame rates or slow the gameplay down.
Tweak spawn probabilities to make Catch or Whack more or less frequent.
Adjusting pipe gap in Flappy alters challenge without changing game logic.
Changing paddle size in Pong makes the game easier or harder.
I left the styling simple so students can practice their own CSS tweaks.
Try changing colors, fonts, or spacing to see how the layout adapts.
Adding images or SVGs could make the games more visually rich later.
But for learning, shapes and plain rectangles are easier to reason about.
I often explain the code by pointing at the core game loop function.
That’s where physics, input, and drawing come together each tick.
Once you understand that loop you can add features methodically.
Start small, test frequently, and avoid changing too many things at once.
Use console.log liberally while learning — it helps find logic errors quickly.
I found many bugs by logging positions and velocities during playtesting.
One common bug was timers left running after resetting a game.
Another common issue was input being ignored when the wrong game was visible.
I fixed these by scoping event handlers and clearing intervals on reset.
Simple defensive checks prevent clicks when a game is not running.
This prevents accidental state transitions during animation sequences.
I also ensured arrays are copied when needed to avoid reference bugs.
For example, when checking moves in Tic-Tac-Toe I copied the board.
That way simulations for AI don't accidentally mutate the real board.
I prefer slice or spread for safe array copies in these scenarios.
The code uses Math.random for unpredictability which keeps gameplay fresh.
Random choices are biased only when needed to improve player experience.
For instance, the AI prefers center or corners to make it smarter.
This small bias produces more interesting matches in Tic-Tac-Toe.
Sometimes randomness makes early rounds feel unfair — tweak as needed.
If you want consistent testing, insert a fixed seed replacement for Math.random.
That makes replayable test scenarios easier to debug and balance.
For production-grade games you might want to add robust input handling.
That can include debouncing clicks or throttling expensive operations.
This project intentionally stays simple so that students can follow each line.
Each game file segment is short enough to be explained in a single demo.
I often use this file to show how event listeners and canvas work together.
It’s a nice bridge from static pages to interactive programming topics.
Students often ask how canvas coordinates map to pixels.
I show them how x and y positions correspond to the top-left origin.
We also go over how to scale elements if the canvas size changes.
This helps with responsive resizing and maintaining consistent gameplay.
One improvement could be to add a pause feature for each game.
A pause toggler would clear the timer and show a paused overlay.
Another idea is to add level progression with increasing speeds.
Levels can be represented by a simple multiplier applied to velocities.
You could also add player lives or time limits for additional challenge.
Power-ups and obstacles can greatly extend replayability for each game.
Collectible items could grant extra points or temporary invincibility.
Obstacles could reduce available space or change physics unexpectedly.
For learning, adding a single new mechanic per week is a good pace.
That keeps the codebase manageable while teaching new concepts gradually.
I recommend committing the file to a Git repo for version tracking.
Git makes it easy to revert mistakes and experiment safely.
Use branches for major changes so the main file stays stable.
Document each change in commit messages so others can follow your work.
If you share on GitHub, add a small README with controls and features.
Include a note about running the file locally and browser compatibility.
That helps teachers or friends quickly test without confusion.
If you want to make the page public, add a small license note.
MIT license is simple and friendly for educational projects.
Licensing clarifies how others can reuse or modify your code.
For classroom use, encourage students to fork and submit pull requests.
Peer review is a great way to learn coding standards and collaboration.
Small projects like this are also good portfolio pieces for college apps.
They show initiative, problem solving, and familiarity with web basics.
I mention my Instagram handle so people can reach out for help.
DMs are an easy way for classmates to ask quick questions.
I enjoy helping others debug and understand the code structure.
Explaining how a function works often helps me learn the topic better.
Teaching is one of the fastest ways to solidify your own knowledge.
If you want, I can add inline walkthrough comments to the code.
Those comments can explain why a step is done, not just what it does.
I can also prepare a short cheat sheet for key functions and loops.
A one-page revision sheet would help when you need to quickly review.
That sheet could map UI elements to corresponding code sections.
It could also list common pitfalls and where to look for them.
For example, check timers, event listeners, and canvas dimensions first.
If something doesn’t render, verify the canvas context and element IDs.
Always confirm that elements exist before adding event listeners to them.
That simple check avoids many "cannot read property of null" errors.
Use try-catch during learning if you want to trap unexpected exceptions.
But in this file I preferred simple checks over heavy error handling.
That keeps learning focused on logic rather than debugging tooling.
Consider modularizing later if the file becomes too large or complex.
Modules help separate concerns and make individual games easier to maintain.
Using ES modules can keep global scope clean and reduce accidental conflicts.
But remember that modules need either a local server or type="module" usage.
For this offline file approach, keeping it as one page is more convenient.
I designed the interface so new games can be added with minimal changes.
Add a new .game section in the panel and a corresponding menu button.
Then add init, start, draw, and reset functions for the new game.
Wire up controls and update the menu click handler and you’re done.
This repeatable pattern makes adding games fast and predictable.
If you want to include audio later, preload sounds to avoid latency.
Small sound cues for hits, wins, and errors improve player feedback.
But audio requires careful user gesture handling to auto-play in browsers.
Another small polish is to add a short tutorial for each game on first play.
Tutorial overlays can guide new players through one or two key actions.
You can store a flag in localStorage so tutorials don’t repeat every time.
That preserves a smooth experience for returning players.
LocalStorage is also handy for storing high scores or preferences.
Keep stored values small and check for existence before reading them.
This prevents crashes when a browser clears storage or runs in private mode.
I tried to keep dependencies minimal so the page stays robust and portable.
No npm, build tools, or bundlers — just open and play.
