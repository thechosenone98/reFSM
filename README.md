# reFSM
## Goal
Implement an algorithm to reduce any FSM to it's simplest form.
## Here's how it should be used
1. Start by creating a new text file.
2. Fill in your state in this format :

        S1 -> (SA, SB, SC, ...)
        S2 -> (SD, SE, SF, ...)
        .
        .
        .
        SN -> (SX, SY, SZ, ...)

3. Run the python script with your text file as an argument like this: `script.py YOURFILENAME.txt`
4. Read the output table that's been printed on screen or (for future reference) access the new text file that's been generated (eg. `YOURFILENAME_reduced.txt`).
### TODO
- [ ] Receive input table
- [ ] Find the best data structure to implement the algorithm
- [ ] Simplify FSM
- [ ] Return formatted output
- [ ] Write output to text file for future use
