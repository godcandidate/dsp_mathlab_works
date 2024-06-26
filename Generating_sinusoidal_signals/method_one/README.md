# Method 1: Generating a Sinusoidal Signal
Generating a sinusoid signal with n data points with N periods in it.

## Parameters
- n: Number of data points (specifies the resolution of the signal).

- N: Number of periods of the sine wave to be included within the n data points.


## Data Visualization
There are two ways to visualize the generated signal
```
Matlab

% Define number of data points and number of periods
n = 60;
N = 2.5;

% Generate time vector (normalized frequency)
k = 0:n-1;
k = k/n;

% Generate the sinusoidal signal
s = sin(2*pi*N*k);
```


- Using plot: This displays a continuous line representing the overall trend of the sine wave.
  
!["continuous signal data"](continous-signal.PNG)

- Using stem: This emphasizes individual data points with vertical lines and markers, showing the discrete nature of the signal.

!["discrete signal data"](discrete-signal.PNG)
