# Theory-of-Algorithms

## Post Correspondence
Inside the folder called Assignment you will find a notebook that talks about the Post Correspondence Problem and the Bound Correspondence. 
***
## Technologies 
The technologies that are used for this are [Python](https://docs.python.org/3/) and [Jupyter](https://docs.jupyter.org/en/latest/) where the blend of both are used to work on the assigment given.
***
### Undecidable Problem in Computability Theory
Is a decision problem that any random yes or no question where it has a infinite set of inputs. This is a usual way to define the decision problem that correspond as the set of inputs where the problem returns as true. The inputs can be anything from a number to a string from a [formal language](https://en.wikipedia.org/wiki/Formal_language). And then by using [Godel numbering](https://en.wikipedia.org/wiki/G%C3%B6del_numbering) to do some encoding for the strings to be turned into natural numbers. This then lets a phrase to be passed as a set of natural numbers, which makes it easier to define. If a problem is passed into a Turing Machine to give back a solution which is actually a contradition that is entered it can cause the Turing Machine to run forever to find the right values of n, a, b, c. But we arent sure if a contradiction atutally exists and thus this becomes an Undecidable Problem.

#### **Undecidable Problems**
Is that when we have problems we can't make an algorithm that can give us an answer to the problem properly in finite time are usually called Undecidable Problems. These problems can actually be practically decidable but they will infact ever be decidable. And that means that there will always be a condition that will always make the Turing Machine go into a infinite loop and will never give the user an answer.
There is a way of actually understanding the Undecidable Problems intuitively from looking at Fermats Theorem which says not 3 positive Integers can ever please the equation:

$$ x^n + y^n = z^n $$
##### **Fermats Theorem** 
- Is said to be actually called Fermats Last Theorem where that the sides of a right angled triagle is 3^2 + 4^2 = 5^2 and always will be but if you change it to 3^3 + 4^3 != 5^3 and according to Fermat that if you change n from 2 it will never be the right answer that you get. And after 350 years [Andrew Wiles](https://en.wikipedia.org/wiki/Wiles%27s_proof_of_Fermat%27s_Last_Theorem) came up with a solution for why these equations couldnt be solved.
##### **Wiles's proof of Fermat's Last Theorem**
- It took Sir Andrew Wiles 7 years to get his proof to be correct in trying to prove that Fermats last theorem was infact true. It became clear to a few others that it could actually be proven to be correct by other mathematicians. When it was still unproven it was actually called Taniyama–Shimura–Weil conjecture at time. The modular theorem actually had elliptic curves in it and this was Wiles own specialist area. After 6 or so years of releasing small bits of his work he held a 3 day lecture and on the 3rd day he had proved that Fermats Theorem was true. Thus proving that the Undecidable Problem is correct.

## Refrences
1. Andrew Wiles proof of Fermats Theorem [here](https://en.wikipedia.org/wiki/Wiles%27s_proof_of_Fermat%27s_Last_Theorem)
2. A video giving a quick explaination of [Fermats](https://www.youtube.com/watch?v=1BSFyEIY2BY)
3. GeeksOfGeeks Decidable & Undecidable Problems [here](https://www.geeksforgeeks.org/decidable-and-undecidable-problems-in-theory-of-computation/)