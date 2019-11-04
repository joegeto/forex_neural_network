# forex_neural_network

I developed a notebook for creating a neural network based on forex data (EURUSD 15M). The input matrix in this case comes from Open, High, Low, Close chart data run through a variety of technical indicators. The notebook includes functions for the full preprocessing of the data. It uses the zigzag function in TTR to create the target array. The neural network uses a stacked autoencoder (SAE) that uses 3 hidden layers with 100 nodes each. The final output is meant to be used in conjunction with programming language MQL for realtime trades.

## Full list of technical indicators:
Welles Wilder's Directional Movement Index 
\nAroon
\nCommodity Channel Index
\nchaikinVolatility 
\nChande Momentum Oscillator
\nMACD oscillator
\nOsMA
\nRelative Strength Index
\nStochastic Oscillator
\nStochastic Momentum Index
\nVolatility (Yang and Zhang)
