# Fixing A Bug
## The Three Code Changes:
![Image](CC1.png)
>First Code Change

![Image](CC2.png)
>Second Code Change

![Image](CC3.png)
>Third Code Change


## Test File:
The test file for a failure-inducing input that prompted you to make that change:
[Test File](test-file3.md)
This file is empty and for created a bug in our code because the array had a size of 0, therefore our index was out of bounds. 

## Symptoms: 
The symptom of that failure-inducing input, the output of running the file at the command line for the version where it was failing.
![Image](BUG.png)

The bug was that out index was out of bounds for ```get(Index)```. Since our file is empty the expected outcome was 0, however the terminal returned an out of bounds error, since there was no elements in our array. Because our expected outcome was nothing, we just returned the size of the link as opposed to the elements in the link.
