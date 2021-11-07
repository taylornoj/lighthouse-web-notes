## **Solving Problems with Pseudocode**

### 1. *Understand the Problem*
   * ask yourself, "what is the input to the problem?"

If we use Loopy Lighthouse as an example, we have several values as inputs:
 * the range 100 to 200
 * the strings "Loopy", "Lighthouse" and "LoopyLighthouse"
 * the multiples 3 and 4

   * then, ask youself "what is the expected output?"

Loopy Lighthouse output will look something like this:

```
   Lighthouse
   101
   Loopy
   103
   Lighthouse
   Loopy
   106
   107
   LoopyLighthouse
   ```





### 2. *Start Writing your Pseudocode*

Describe in English, the solution you're going to implement:

```
Loop from 100 to 200:
   Let num = the current step in the loop
  Print num
End loop
```
  ...which will start to loop the numbers of our code -  a good start!

Now we can start to incorporate the first condition into our pseudocode.

```
Loop from 100 to 200:
   Let num = the current step in the loop
   If num is a multiple of 3:
     Print "Loopy"
   Otherwise
     Print num
   End if
End loop
```
Continue on with the rest of your conditions.

### 3. *Translate the Solution to JavaScript*

Because we took the time to solve the problem first, converting it to JavaScript becomes no more than a matter of remembering the syntax.


