# ECSE351-ckj16-GNUProblem

Submission for ECSE351 GNU Problem Set, by Cole Judson (ckj16)

Chosen Problem: AGISETI Demo

Original grc file taken from: https://github.com/Jtearwicker/AGISETI/blob/main/Week4_Radio_Astronomy_II/grc_files/Interferometry.grc

## Edits to code

The initial step was to increase Antenna count from 2 progressively up to 5 using the code blocks, to create an Interferometry pattern that had a progressively stronger final signal. This was expected due to all of the signals being of the same frequency and in phase, and thus they would add constructively to each other. 

The next step taken was to make changes to the phase in each of the signals (as inspired by the name of the original file); the goal was to create the "best looking" interference pattern that emulated a real life fringes pattern, where interspaced alternating regions of constructive and destructive interference could be seen. After several iterations of changing the amount of signals and the phase differences between them, the final design contains 5 signals that increase in phase difference by 45 degrees from each other to create the following pattern: 

![Screenshot 2025-04-23 004814](https://github.com/user-attachments/assets/0d15cffc-7bba-4fa8-96b8-b34b871b5114)

The code used to produce the above image can be found in the Interferometry_edited_ckj16.grc tab. 
