## Design Specification Pre-lab

| AB \ CD | 00 | 01 | 11 | 10 |
|--------|----|----|----|----|
| 00     | 1  | 0  | 0  | 1  |
| 01     | 1  | 1  | 1  | 1  |
| 11     | 1  | 0  | 1  | 0  |
| 10     | 1  | 0  | 0  | 0  |



**F1 =** A′D′ + C′D′ + A′B + BCD (SOP form)

**F2 =** (B + D') * (C + A' + D') * (D + A' + C')  (POS form)


I simulated both logic equations in Vivado using behavioral simulation and verified that they produce identical outputs for all input combinations. This confirms that the SOP implementation in `f1` and the POS implementation in `f2` are logically equivalent, even though they are written in different forms. The matching simulation results demonstrate that both descriptions implement the same Boolean function.


