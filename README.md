# reFSM
## Goal
Implement an algorithm to reduce any FSM to it's simplest form.
## Here's how it should be used
1. Start by creating a new text file.
2. Fill in your state in this format :

        //State change condition (K is the example input)                          Output at that state
        S1 -> ((K = "1011") -> SA, (K = "0001") -> SB, (K = "1111") -> SC, ...) -> (Q1 -> "0", Q2 -> "1011", ...)
        S2 -> ((K = "0010") -> SD, (K = "1001") -> SE, (K = "1111") -> SF, ...) -> (Q1 -> "1", Q2 -> "1100", ...)
        .
        .
        .
        SN -> ((K = "0000") - > SX, (K = "0100) -> SY, (K = "1100") -> SZ, ...) -> (Q1 -> "0", Q2 -> "0000", ...)
        //You can use '-' for don't care
        SK -> ((K = "10--") -> SY, ...) -> (Q1 -> "0", Q2 -> "1111", ....)

3. Run the python script with your text file as an argument like this: `script.py YOURFILENAME.txt`
4. Read the output table that's been printed on screen or (for future reference) access the new text file that's been generated (eg. `YOURFILENAME_reduced.txt`).
### TODO
- [ ] Receive input table
- [ ] Find the best data structure to implement the algorithm
- [ ] Simplify FSM
- [ ] Return formatted output
- [ ] Write output to text file for future use
