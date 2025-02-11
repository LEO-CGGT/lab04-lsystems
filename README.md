# lab04-lsystems
Let's practice using grammars! For this lab, please pull up the L-system node in Houdini.

# Haoquan Liang Submission
## Puzzle 1   
Axiom: `FAF[-FAF]FA[-FAF]FAF`   
Rule: `A = -`, `F = FAF[-FAF]F[-FAF]FAF`   
<img alt="puzzle1" src="puzzle1.png">

## Puzzle 2
Axiom: `ff-F-F+F+F-F`   
Rule: `F=F-F+F+F-F`   
<img alt="puzzle2" src="puzzle2.png">


## Custom
Axiom: `FFFFFFFFFFAA`   
Rule: `A=!"[C]////[C]////B`, `B=&FFFFA`, `C=&BAB`   
5 iterations:   
<img alt="custom5" src="custom-5i.png">   
10 iterations:   
<img alt="custom10" src="custom-10i.png">


## 1. Wheat grammar puzzle
Look at these iterations (n = 1, 2, 3) of a one-rule grammar. Using the built in symbols in Houdini, design a grammar that produces this output.\
<img width="200" alt="square1" src="https://user-images.githubusercontent.com/1758825/193949661-a3a0e1f7-7d68-4b9e-8384-d9991e1e9fd2.png">
<img width="200" alt="square2" src="https://user-images.githubusercontent.com/1758825/193949853-cf2306b3-3537-4c24-91b5-0a3083bc87c0.png">
<img width="200" alt="square3" src="https://user-images.githubusercontent.com/1758825/193949859-5e432b4b-f18d-48b5-a9e9-8d7dba255955.png">

## 2. Square grammar puzzle
How about this one?\
<img width="200" alt="square1" src="https://user-images.githubusercontent.com/1758825/193949895-87cdfb43-da7c-4867-ab1b-107e1ba9d2a7.png">
<img width="200" alt="square2" src="https://user-images.githubusercontent.com/1758825/193949904-a9cdfe0f-319e-4ca8-9935-dd338217a7cf.png">
<img width="200" alt="square3" src="https://user-images.githubusercontent.com/1758825/193949910-928e5993-ce26-4681-80f8-ffeb54be4dcf.png">

## 3. Custom plant
Choose a plant in the world. Working off a reference, design a grammar that mimics the structure of that plant. Unlike our simple puzzles, please use multiple rules for greater complexity. You can take this as an opportunity to design a grammar for your homework assignment! Include images of your grammar's output.

## Submission
- Create a pull request against this repository
- In your readme, list your solutions to the puzzles, then your custom grammar and images of a few iterations of output
- Profit
