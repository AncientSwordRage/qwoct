Esolang Specification designed to be written one handed while giving you a headache

## Commands
QWOCT commands are written as the letters QWERTYUI which each have a base function. Each letter, or function maniulates or interacts with the current queue. To write programs, the letters are combined in pairs that form words which have
related functionalities.

### Letters

#### *Q* - Queue
Input and output goes via the queue, so all commands that directly manipulate the queue or it's contents.

*Example*: Q1   
*Output*: Contents of Queue at registry 1

#### *W* - Words
Commands which directly effect the command words themselves.

*Example*: W8   
*Output*: The function related to I

#### *E* - Each, or enumerate
Modifies a command to be run on each element of a queue.

*Example*: E2    
*Output*: The element at position 2 of the current queue

#### *R* - Return, or reverse
Return to the start of the current queue, or reverse the current function.

*Example*: R1   
*Output*: To be decided

#### *T* - Transform
Changes the element at the current position.

*Example*: T6   
*Output*: To be decided

#### *Y* - whY
Used to indicate a switch in the code (much like an if-statement or filter)

*Example*: Y8   
*Output*: True

*Example*: Y1-7   
*Output*: False

#### *U* - Uncrement
The opposite of Increment, used to lower the current value, or to pop an element off of the current queue.

*Example*: U7   
*Output*: Pops the seventh element in the current queue, defaults to returning 8 if there is no such element

#### *I* - Increment
The opposite of Uncrement, used to raise the current value, or add a value to queue

*Example*: I1   
*Output*: Pushes 1 onto the end of the current queue.

### Words
TBC

### Numbers
QWOCT only uses numbers between 1 and 8. This means that although all numbers are base 8, all instances of 0 are replaced by 8. For instance, 1-8 remain the same. As an example, the first 16 numbers are:


|QWOCT Numbers  | Ordinary Base-10 |
| ------------- | ------------- |
| 1, 2, 3, 4, 5, 6, 7, 8  | 1, 2, 3, 4, 5, 6, 7, 8  |
| 11, 12, 13, 14, 15, 16, 17, 18  | 9, 10, 11, 12, 13, 14, 15, 16  |

Note how 9 is written 11, instead of 10. Compared to ordinary base-8 which is 10, or traditional bijective base-8, by 1A.
