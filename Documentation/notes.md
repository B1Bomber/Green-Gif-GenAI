Goal: get it to run on ESP-32

Use the top 5000 or so most used english words
See how much memory I have left after I upload the code. 

algorithm overview (dynamic programming): 
- Load each word as basis vectors (ie [0 0 0 1] or [0 1 0 0])
- multiply by random vector. Can reuse a counter to save space. 
- Words: <u>Given</u> <u>Guess</u> as <u>Existing word</u> <u>fill in the blank</u>
- Compare the guess to the given and correct the guess vector
- Example where Given = "The fox" and Guess = "The cat"
- Make layers

