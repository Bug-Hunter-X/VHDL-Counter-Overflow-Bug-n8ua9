# VHDL Counter Overflow Bug

This repository demonstrates a common error in VHDL code: improper handling of counter overflow. The `buggy_counter.vhdl` file contains a counter that might exhibit unexpected behavior when the count reaches its maximum value (15 in this case). The `fixed_counter.vhdl` file provides a corrected version.

## Bug Description
The original counter lacks proper handling of the transition from the maximum count value back to 0. This can lead to unexpected behavior, potentially causing the counter to skip values or produce erroneous outputs.

## Solution
The solution involves ensuring a clean transition from the maximum count back to 0, preventing any unintended behavior.