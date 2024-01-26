You can launch challenges in two modes, using the buttons below!
So far, you have been using `Start`, which launches the challenge so that you can attempt to solve it for real.
You can also `Practice`!
This will grant you administrative privileges (via `sudo`) in the challenge container, allowing you greater capabilities to debug solutions and otherwise experiment with the challenge.
You cannot use this to actually solve the challenge because the `/flag` file, in practice mode, is replaced with a practice flag that cannot be redeemed for points.

You never *need* Practice mode to solve a challenge, except for this challenge, because it is designed to expose you to Practice mode.
This challenge has a `/challenge/secret` file that is only readable by root, but it doesn't change between Practice mode and normal mode.
To solve this challenge:
- Launch the challenge in Practice mode.
- Read the `/challenge/secret` file.
- Relaunch the challenge in normal mode (using Start).
- Provide the secret when `/challenge/solve` asks for it.

