# Architecture of the CPU

When you write Python code like:

```py
print("Hello, world!")
```
Your computer doesn’t just magically know what to do. Something inside called the CPU reads your instructions, understands them, and executes them step by step.
Understanding how the CPU works helps you see what’s really happening every time your code runs.

Think of the CPU as the brain of your computer. Just like your brain reads, thinks, and acts, the CPU:

- Fetches instructions
- Decodes what they mean
- Executes them

## The Purpose of the CPU

The CPU (Central Processing Unit) is like the chef in a restaurant kitchen:

The orders coming from customers are your program’s instructions.

The ingredients are data.

The CPU reads the order, prepares the dish, and serves it.

That’s the fetch–decode–execute cycle, or sometimes shortened to the fetch–execute cycle.

## The Fetch–Execute Cycle

### Fetch	
The CPU gets the next instruction from memory. Like a chef picking up the next order from the counter.

### Decode	
The CPU works out what the instruction means.	The chef reads the order and plans what ingredients to use.

### Execute	
The CPU carries out the instruction. The chef cooks and serves the dish.

This cycle repeats constantly that’s how the computer runs your code line by line.

## Main CPU Components

### ALU (Arithmetic Logic Unit)
Performs all calculations and logic (add, subtract, compare).
Like the chef’s hands doing the actual cooking chopping, mixing, comparing ingredients.

### CU (Control Unit)
Directs operations, tells every part of the CPU what to do next.
The head chef shouting instructions to the kitchen staff.

### Cache
Very fast memory inside the CPU that stores recent instructions and data for quick access.
The spices or tools kept right beside the chef for easy reach.

### Registers
Small, super-fast storage locations inside the CPU used during processing.
The chef’s small notepad for quick notes, like “next order number 12.”

## Von Neumann Architecture

This is the design most computers use today. It means instructions and data are stored together in main memory.

The CPU uses several registers to manage this process:

### MAR (Memory Address Register)
The address of where to find the next instruction/data in memory.
The chef’s note saying “get ingredients from shelf #12.”

### MDR (Memory Data Register)
The actual data fetched from that address.
The ingredients the chef brings from the shelf.

### Program Counter (PC)	
Keeps track of the next instruction’s location.	The chef’s order list “next, order #13.”

### Accumulator (ACC)	
Temporarily holds results of calculations. The mixing bowl where the chef keeps results before serving.
