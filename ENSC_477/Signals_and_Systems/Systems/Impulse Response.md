We want to know how a system responds to *any* input. In order to do this we need a universal "building block." To do this we can use impulse. Any signal can be thought of as a weighted collection of shifted impulses. If we know how the system responds to a single impulse, we can build the systems response to *any* input (under certain conditions).

This response is known as the point spread function, or the impulse response function:
![[Pasted image 20250923190035.png]]

If we let h be the output of a system to a 2D impulse, we end up with an output that depends on four independent variables. 

If we also assume that the system S is linear, then the following integral holds true:
![[Pasted image 20250923190346.png]]
This is the superposition integral, it shows that the point spread function (PSF) uniquely categorizes a linear system. We need only know the PSF in order to calculate its output in response to any given input.