# Rust Undefined Behavior Example

This repository demonstrates a common source of undefined behavior in Rust: modifying a vector through a raw pointer after its capacity has been changed.  The code attempts to modify the first element of the vector using a raw pointer, leading to unpredictable results and potential crashes. The solution demonstrates safe alternatives.