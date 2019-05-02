# Mini cam scanner
An algorithm that performs input image denoising using mean kernel filters and adaptive thresholding.

The executable named 'scan' has been provided. To use, run the following:

>./scan pathtonoisyimage pathtocleanimage radius epsilon

Here, radius is the kernel size applied for filtering, and epsilon is the round-off value for precision and errors. 

The repository efficientCamScan under the same account gives a much faster algorithms at the expense of little quality. efficientCamScan uses median filters and has an accelerated runtime. 
