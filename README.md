# Commit Cannon

Enter a GitHub username. Your repos become bullets. Survive the waves.

**[Play it](https://ashleywolf.github.io/commit-cannon/)**

An arcade shooter where your GitHub profile powers the ship. More repos = more firepower. Enemies spawn in waves with escalating difficulty. Dodge, shoot, survive. Your ship is named after your username and your ammo count comes from your repo count.

Neon green, pink, and blue. FPS counter in the corner. Mission Failed screen with a stats grid when you inevitably die.

## How it works

- GitHub API fetches profile to generate ship stats
- Wave-based enemy spawning with progressive difficulty (1 + wave x 0.1)
- 3+ enemy types with varying HP and score values
- Keyboard/mouse controls, mobile-friendly touch
- Web Audio API retro arcade sounds
- HUD: HP bar, wave counter, score, FPS
- Downloadable score card on game over
- Single HTML file, neon aesthetic
