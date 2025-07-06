# Week 1
## Lecture 1: Introduction to Python: knowledge, machines, objects, types, variables, bindings, IDEs

## Readings: Ch 1, Ch 2.1–2.2
## Lecture 1 Finger Ex.

### Chapter 1 Summary: Getting Started

 * Essence of Computers: They perform only two functions: calculations (at astounding speeds, ~100 billion per second) and storage of results (massive capacities, e.g., 100 GB ≈ weight of 16,000 elephants). This overcomes historical human limitations.

 * Computational Thinking: Distinguishes between:

    + Declarative Knowledge: Facts (e.g., "the square root of *x* is *y* where y² = x").

    + Imperative Knowledge: "Recipes" or algorithms for solving problems (e.g., Heron's method for square roots using guess-and-check).

 * What is an Algorithm: A finite sequence of simple instructions with defined control flow (steps, decisions, repetitions). It is analogous to a cooking recipe. Allows solving complex problems by combining basic primitives.

 * Evolution of Computers:

    + Fixed-Program: Designed for one specific task (e.g., calculators, encryption machines).

    + Stored-Program (Von Neumann): Store and execute any sequence of instructions (program) from memory. An interpreter executes the instructions, enabling flexibility and self-modification. The program counter and control flow (conditional jumps) are key.

 * Programming Languages and Computability:

    + Universal Turing Machine: Theoretical foundation. The Church-Turing Thesis states that any computable function can be programmed on it.

    + Turing Completeness: Any modern programming language (Python, Java, etc.) has equivalent computational power.

 * Language Components:

    - Syntax: Rules for valid instructions (e.g., 3.2 + 3.2 is valid; 3.2 3.2 is not).

    - Static Semantics: Rules for meaning before execution (e.g., type compatibility).

    - Semantics: Actual meaning of the executed instruction.

 * Errors and Risks: Programs can fail in dangerous ways:

    + Syntax Errors: Easily detected by the system.

    + Static Semantic Errors: Harder to detect (depends on the language).

    + Semantic Errors (Logic): The program runs but produces incorrect results (the worst type, can cause serious harm). Programs should be written so failures are evident.

#### Core Conclusion: Computing enables solving previously impossible problems. Mastering computational thinking (decomposing problems, designing algorithms) and understanding how computers execute instructions literally (including the risks!) is essential for creating effective and reliable solutions.

### Chapter 2.2 Summary: The Basic Elements of Python
 #### Core Concepts of Python Programming

 * Programs & Execution

    + Python scripts are sequences of definitions and commands

    + The interpreter evaluates definitions and executes commands

        Example: print('Yankees rule!') outputs text to the console

 * Objects & Types

    + Scalar objects (indivisible):

            int: Integers (e.g., 3, -5)

            float: Real numbers with decimals (e.g., 3.14, 1.6E3 for scientific notation)

            bool: Boolean values (True/False)

            None: Special null value

    + Non-scalar objects: Have internal structure (e.g., strings)

 * Expressions & Operators

    + Combine objects/operators to form expressions (e.g., 3 + 2 → 5)

    + Key operators:

        Arithmetic: +, -, *, /, ** (exponentiation)

        Comparison: == (equal), != (not equal)

        Boolean: and, or, not

            Use type() to check object type (e.g., type(3) → int)

 * Variables & Assignment

    + Variables are names bound to objects (not containers)

    + Assignment: pi = 3.14159 binds name pi to a float object

    + Reassignment changes binding: radius = 11 → radius = 14

    + Naming rules: Case-sensitive, can include letters/numbers/_, can't start with a number or use reserved keywords (e.g., if, for)

 * Best Practices

    + Use meaningful names (e.g., area = pi * radius**2 vs. c = a*b**2)

    + Add comments with # for readability

    + Multiple assignment:

            Simultaneous: x, y = 2, 3

            Swap values: x, y = y, x

 * Key Distinctions

    + = vs ==: Assignment (=) vs. equality test (==)

    + Literal vs. Variable: 3 (literal) vs. radius (variable name)

    + Static vs. Dynamic: Variable bindings can change, but objects are immutable (e.g., 3 is always 3)

#### 💡 Essence: Python programs manipulate objects through named variables and expressions, with strict type-based operations and syntax rules. Readability is enhanced through clear naming and comments.

