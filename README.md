# -DIGITAL-FIR-FINITE-IMPULSE-RESPONSE-FILTER

COMPANY NAME: CODTECH IT SOLUTION PVT.LTD

CONDIDATE NAME: ABHIJIT WANKHEDE

INTERN ID: CT12TNT

DOMAIN NAME: VLSI

DURATION: 8 weeks

MENTOR NAME: NEELA SONTOSH

DESCRIPTION:

# Introduction to FIR Filters
A Finite Impulse Response (FIR) filter is a type of digital filter where the impulse response settles to zero in a finite number of steps. It is widely used in signal processing applications due to its stability and linear phase properties.

# Characteristics of FIR Filters
Finite Duration: The response to an impulse input becomes zero after a finite number of samples.
Always Stable: Since FIR filters do not have feedback, they are inherently stable.
Linear Phase: By making the coefficients symmetric or antisymmetric, FIR filters maintain a linear phase response.
Easier Implementation: They do not require feedback loops, making them simpler for digital signal processing.
# FIR Filter Equation
The output of an FIR filter is computed as:


      k=0
y[n]=  ∑     h[k]⋅x[n−k]
      N−1
​

Where:


y[n] = Output signal

x[n] = Input signal

h[k] = Filter coefficients (impulse response)

N = Number of filter taps (order + 1)
 
# FIR Filter Design Methods
There are several techniques to design FIR filters:

Windowing Method:

Uses predefined window functions like Rectangular, Hamming, Hanning, Blackman, etc.
Example: Applying a Hamming window to an ideal filter response.
Frequency Sampling Method:

Designs the filter by specifying frequency-domain samples.
Optimal Filter Design (Parks-McClellan Algorithm):

Uses the Remez exchange algorithm for optimal minimization of error.
# Types of FIR Filters
Low-Pass FIR Filter: Allows low frequencies and blocks high frequencies.
High-Pass FIR Filter: Allows high frequencies and blocks low frequencies.
Band-Pass FIR Filter: Passes a specific frequency band while attenuating others.
Band-Stop (Notch) FIR Filter: Attenuates a specific range of frequencies.

# Advantages and Disadvantages of FIR Filters
Advantages: ✔ Stable due to no feedback
✔ Can have exactly linear phase
✔ Simple hardware implementation

# Disadvantages: ✘ Higher order required for sharp transitions
✘ More computationally expensive compared to IIR filters

# Applications of FIR Filters
Audio Processing: Equalizers, noise reduction
Image Processing: Edge detection, smoothing
Communication Systems: Channel equalization
Biomedical Signal Processing: ECG noise removal
# Conclusion
FIR filters are essential in digital signal processing due to their inherent stability and ability to provide linear phase characteristics. Their design involves different techniques, and they find applications in various engineering fields.

# output:

![Image](https://github.com/user-attachments/assets/4eae34bb-fd8d-4c74-9e0a-b22e2914a29d)

![Image](https://github.com/user-attachments/assets/4fc34bc4-66b1-468f-8d8c-aa481ffaf37d)

![Image](https://github.com/user-attachments/assets/5eaa0979-84d1-445b-8402-2ef0092a0a27)

![Image](https://github.com/user-attachments/assets/dd50af80-b8c8-4b9a-8817-90266321d951)

