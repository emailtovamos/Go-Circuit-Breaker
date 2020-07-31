# Go-Circuit-Breaker

A Circuit Breaker implementation in Golang. 

Server gets called by client and there is a circuit breaker in between.

If server fails more than 60% of the times then the circuit breaker opens. 
