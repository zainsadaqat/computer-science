# 1.2 CPU Performance

## 1.2.1 Clock speed

Clock speed is how fast the CPU ticks. Every tick allows the CPU to do the next tiny step of work. A faster clock means more instructions per second.

### Analogy

Imagine a cashier scanning items. Every beep is one item scanned. A cashier who beeps faster finishes the queue faster.

### Example-1
Games like Fortnite or Pubg run smoother on processors with higher clock speed because the CPU can update the game world more times each second.

### Example-2
Video editing software exports faster because the CPU completes its calculations more rapidly.

### Note

There is one universal number of ticks per second. That is not true. A CPU tick is tied to its clock frequency and every processor family runs at different frequencies that also fluctuate during use.

modern CPUs do not run at a fixed frequency. Technologies like turbo boost and power saving constantly change the clock rate. So asking for a single number hides important details about how real processors behave.

Instead of thinking about a fixed ticks per second, think in terms of:
- The base clock frequency which is usually between one billion and four billion cycles per second.
- The dynamic range which can drop much lower under light load and go much higher under heavy load.
- The idea that one cycle does not always equal one useful instruction.

If a CPU is running at 3 gigahertz, it means roughly three billion cycles per second. But this does not mean three billion instructions. Some instructions take multiple cycles. Some operations happen in parallel with pipelines and superscalar execution. So the tick count is not a direct measure of work.

### Question
If a CPU has a higher clock speed, what does that usually mean for how fast it can work?

## 1.2.2 Cache size
Cache is tiny memory inside the CPU that holds the most important information the CPU needs right now. It is much faster than RAM.

### Analogy
A school student doing homework. They work faster when the textbook, notes, and calculator are on the desk rather than having to go to another room each time. Cache is the items on the desk.

### Example-1
Phones with bigger CPU cache load apps faster because they do not need to fetch the same data repeatedly.

### Example-2
Browsers run smoother when processing many tabs because the CPU keeps repeating instructions in the cache.

### Question
Why does having more cache make the CPU faster?

## 1.2.3 Number of cores

A core is a thinking brain inside the CPU. More cores means the computer can do more than one job at the same time.

### Analogy
Imagine a kitchen with one chef versus a kitchen with four chefs. One chef can cook only one meal at a time. Four chefs can cook four meals at once.

### Example-1
Modern games use multiple cores so one core handles graphics, one handles physics, one handles world updates.

### Example-2
While video calling, one core handles the camera, one handles the microphone, one handles background apps.

### Question
What is one benefit of having more than one core?
