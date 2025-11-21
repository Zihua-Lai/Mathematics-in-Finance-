# Mathematics-in-Finance
I will use Python code to simulate the mathematics theory knowledge in finance use 

## Topic 2: Martingale, Stopping time, Martingale optional theorem
### 1.  Martingale 
A martingale is a type of stochastic process (sequence of random variables) used to model fair games. In finance, if a stock price follows a martingale, then its future expected price (given all past information) equals its current price. There is “no edge” and you cannot expect to make money just by timing the market.

### 2 Stopping time 
A stopping time is a random time that depends only on the information available up to that time. In finance, a common stopping time would be “the first time a stock hits a pre-set price,” or “the moment your trading strategy tells you to sell,” but the decision cannot rely on future information.

### 3. Martingale Optional (Stopping) Theorem
The optional stopping theorem states: for a martingale and a stopping time that satisfies certain integrability or boundedness conditions, the expected value at the stopping time equals the starting expected value. 
This means: for a fair asset, timing your buy/sell (provided you don't know the future) can't give you expected profits.
