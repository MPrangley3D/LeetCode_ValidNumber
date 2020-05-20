# LeetCode_ValidNumber
Because I am insane, I went to LeetCode, and sorted by Hardest:LeastSolved.  No sweat!

Language: C#
 
# What I learned
This one was insane, because it really did a poor job of defining what actually would count as a number.  
If this were in in-person whiteboard, I would have been able to ask.  In this case I ended up making a bunch of logic that ended up being scrapped, and I also had to rethink a lot of solutions that I'd considered correct - and that returned what I expected - but the solution disagreed with what was and was not valid.

I'm pretty pleased with the Obejct oriented nature of my solution, but I do want to revisit it and improve the run speed.

I was quite pleased that my solution ran faster than 55% of solutions, and was more memory performant than 100% of solutions.
Additionally at the time of this solution, the problem has a 13% solve rate from around 815k attempts, so I feel pretty good about getting to a workable solution.

# The Pitch:  
Validate if a given string can be interpreted as a decimal number.

Some examples:
"0" => true
" 0.1 " => true
"abc" => false
"1 a" => false
"2e10" => true
" -90e3   " => true
" 1e" => false
"e3" => false
" 6e-1" => true
" 99e2.5 " => false
"53.5e93" => true
" --6 " => false
"-+3" => false
"95a54e53" => false

Note: It is intended for the problem statement to be ambiguous. You should gather all requirements up front before implementing one. However, here is a list of characters that can be in a valid decimal number:

    Numbers 0-9
    Exponent - "e"
    Positive/negative sign - "+"/"-"
    Decimal point - "."

Of course, the context of these characters also matters in the input.
