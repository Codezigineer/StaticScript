- [x] Lexical & Syntax Analysis
- [ ] Semantic Analysis
    - [x] Scope scan
    - [x] reference resolution
        - [x] Variable resolution
            - [x] variable undefined check
            - [x] variable double definition check
        - [x] Number of levels to resolve
            - [x] Number of off undefined checks
            - [x] off number of duplicate definition checks
            - [x] function nesting check
    - [x] type checking
        - [x] variable/constant type deduction
        - [x] Variable/constant assignment type checking
        - [x] Disable parameter passing/return type checking
        - [x] array element type consistency check
    - [ ] Semantic validity check
        - [x] break/continue statement ただ can appear in a loop
        - [x] return 句のみ can appear in levels
        - [x] 戻り値 type の pass number must の return sentence
        - [x] Check if the constant is reassigned
        - [x] checks if an rvalue is assigned
        - [ ] if and else must match
- [ ] LLVM IR generation
