# Black-Scholes-Mini-Pricer
Python script that prices European vanilla options with the Black‑Scholes model and outputs Delta. Very basic but a kind of training.
Used formula from by books and knowledge

#Installation

python -m pip install --upgrade pip
pip install scipy   # numpy will be installed automatically
Python ≥ 3.9 recommended

#Running the script

python black_scholes.py

The program will successively ask for the inputs listed below; just press Enter to re‑enter a value if you mistype.

#Example 

=== Black-Scholes mini-pricer ===
Spot price S: 100
Strike K: 105
Maturity T (years): 0.5
Risk-free rate r (e.g. 0.02): 0.02
Volatility σ (e.g. 0.25): 0.25
Option type (call/put) [call]: call
Dividend yield q [0.0]: 0

*** Result ***
Option: CALL
Price : 7.1153
Delta : 0.4335


