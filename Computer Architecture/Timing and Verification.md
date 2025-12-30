

## Timing in combinational circuits

In reality, outputs are delayed from inputs even in combinational circuits. This is because that transistors take a finite amount of time to switch.

two delays: assume output is Y
1. Contamination delay ($t_{cd}$) : delay until Y starts changing
2. Propagation delay ($t_{pd}$): delay until Y finishes changing
![[timing_1.png]]

The value is unstable until finish. 

Many different situation will affect delays such as temperature, voltage, even different designs.

