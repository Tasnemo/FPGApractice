## Sequential Logic Latch

| TRIGGER | INPUT | What happens to OUT when INPUT changes? |
|--------|--------|-----------------------------------------|
| 0      | 0 → 1  |   No Change                             |
| 0      | 1 → 0  |          No Change                      |
| 0 → 1  | 0      |     OUT becomes 0                       |
| 0 → 1  | 1      |     OUT becomes 1                       |
| 1      | 0 → 1  |     OUT matches INPUT                   |
| 1      | 1 → 0  |     OUT matches INPUT                   |
| 1 → 0  | 0      |     OUT holds previous value            |
| 1 → 0  | 1      |     OUT holds previous value            |


## Sequential Logic D-Flip Flop (Edge-Triggered)

| CLOCK | D | What happens to Q when D changes? |
|-------|---|----------------------------------|
| 0     | 0 → 1 | No change |
| 0     | 1 → 0 | No change |
| 0 → 1 | 0     | OUT becomes 0 |
| 0 → 1 | 1     | OUT becomes 1 |
| 1     | 0 → 1 | No change |
| 1     | 1 → 0 | No change |
| 1 → 0 | 0     | No change |
| 1 → 0 | 1     | No change |

**What is different about the input/output operation of the D-Latch versus the D-Flip Flop?**

The D-Latch functions in the sense that the TRIGGER simply allows for the INPUT to be sent to the OUT and the TRIGGER being 0 stops the INPUT from influencing the OUTPUT. The D-Flip Flop ultilizes the CLOCK to only allow an update from D (The input) when it "ticks" from 0 → 1 or during a rising edge.

**Can you think of any ways the D-Flip Flop might be more useful than the Latch?**

D-Flip Flops can provide a unit of iteration or instance that is relative to itself and makes relative logic a lot simpler.
