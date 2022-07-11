# BoothAlgo
16-bits Booth's Multiplication Algorithm Circuit Simulation

Simulator - Logisim Evolution

## Running Simulation

run this command on your cli
```
java -jar logisim-evolution.jar
```

the simulation will pop up
then click 'file' and open 'booth_algo.circ'

set you multiplicand on M, and multiplier at register MQ.
then press ctrl+k to toggle clock oscillation
next step is to toggle Signal_In to 1, wait for the rising edge,
and toggle Signal_In to 0.
the circuit will perform multiplication until Signal_Out is one
which means multiplication is finished
