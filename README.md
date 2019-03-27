Esolang Specification designed to be written one handed while giving you a headache

## Commands
QWOCT only has 8 commands or letters which each have a base function. Each function maniulates or interacts with the current queue. To write programs, the letters are combined in pairs that form words which have
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

#### *E* - Each, or element-wise
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

#### *I* - Incremenet
The opposite of Uncrement, used to raise the current value, or add a value to queue

*Example*: I1   
*Output*: Pushes 1 onto the end of the current queue.

### Words
TBC

### Numbers
TBC

### Input Precedence
TBC
