So far, the challenges have been giving you the flags directly.
Now, you will learn that the flag actually lives in the `/flag` file.
The `/flag` file is only readable to the challenge, because the challenge runs as the `root` user.
Since you are the `hacker` user in the dojo, the only way to retrieve the flag is to solve the challenge.

This challenge's `/challenge/solve` program will make the flag world-readable, but won't print it to you.
You will need to read `/flag` yourself after running `/challenge/solve`.
