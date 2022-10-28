# D. Easy. RISCV - The MOD operation [8 points]

We will be introducing a new instruction called "mod" in RISC-V which calculates the remainder. The semantics of the mod instruction `(mod dst,src1,src2)` are `dst = src1%src2`. e.g., lets say s1=5 s2=2 
`mod s3,s1,s2` stores the value 2 in s3.

We will be using the mod operation in the program below called cipher.
You want to impress your friend, so you predict the result of executin the program as it is written, just by looking at it. If the program is guaranteed to execute without crashing, describe what it prints, otherwise explain the bug that may cause a crash.
