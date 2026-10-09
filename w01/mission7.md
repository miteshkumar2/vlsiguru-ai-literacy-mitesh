# Mission 7: What Actually Runs AI?

## 1. What Is a CPU and What Is It Good At?

CPU stands for **Central Processing Unit**. It is the main processor of a computer that executes instructions and controls many computer operations. It is good at handling different types of tasks and performing operations that require step-by-step decision-making.

**Example:** A CPU runs applications, opens files, and performs calculations on a laptop.

## 2. What Is a GPU and Why Is It Useful for AI?

GPU stands for **Graphics Processing Unit**. It can perform many calculations at the same time, making it useful for AI tasks that require large numbers of mathematical operations.

**Example:** A GPU helps an AI model process images and perform calculations quickly.

## 3. What Is an NPU / AI Accelerator?

NPU stands for **Neural Processing Unit**. It is specialised hardware designed to perform AI-related calculations efficiently. AI accelerators can improve speed and reduce power consumption for supported AI tasks.

Modern systems use specialised hardware because AI calculations can be very large and may require more speed and less power.

**Example:** An NPU in a smartphone can help run AI features such as background blur during video calls.

## 4. What Does Parallel Computation Mean?

Parallel computation means performing multiple calculations at the same time instead of completing every calculation one after another.

**Example:** Imagine several students solving different maths problems at the same time. Together, they can finish the work faster than one student solving every problem alone.

## 5. Why Does AI Depend on Compute and Memory?

AI needs **compute** to perform mathematical calculations and **memory** to store and access data, model parameters, and intermediate results.

If computing power is low, processing may take longer. If memory is insufficient or data access is slow, the AI system may also become slower.

**Example:** Just as a student needs both time to solve problems and a place to keep books and notes, an AI system needs computing power and memory to work effectively.

## 6. Difference Between Training and Inference

| Training                                                          | Inference                                                            |
| ----------------------------------------------------------------- | -------------------------------------------------------------------- |
| The AI model learns patterns from data.                           | The trained model uses what it learned to produce an output.         |
| It usually requires many calculations to adjust model parameters. | It performs calculations to answer a prompt or make a prediction.    |
| It often requires substantial computing power and memory.         | Its hardware requirements depend on the model size and the task.     |
| Example: Teaching an AI to recognise cats using many pictures.    | Example: Asking the trained AI whether a new picture contains a cat. |

## 7. Diagram: What Runs an AI System?

The following diagram shows the main parts of an AI system and the hardware and memory that support it.

```text
┌──────────────────────────┐
│      AI Application      │
│   (Chatbot or AI app)    │
└────────────┬─────────────┘
             ↓
┌──────────────────────────┐
│        AI Model          │
│ (Learned patterns and    │
│      parameters)         │
└────────────┬─────────────┘
             ↓
┌──────────────────────────┐
│    Software / Framework  │
│ (Runs the model)         │
└────────────┬─────────────┘
             ↓
┌──────────────────────────┐
│      Computing Hardware  │
│       CPU / GPU / NPU    │
└────────────┬─────────────┘
             ↕
┌──────────────────────────┐
│          Memory          │
│ (Stores data and model   │
│       parameters)        │
└──────────────────────────┘
```

**How it works:** The AI application receives a request and sends it to the AI model. Software frameworks help run the model on suitable hardware, such as a CPU, GPU, or NPU. Memory stores the model parameters and data needed during processing.

## Conclusion

I learned that AI does not run by itself. It needs an AI model, software, computing hardware, and memory. CPUs handle general tasks, GPUs perform many calculations in parallel, and NPUs are designed for specialised AI operations. Training teaches the model, while inference uses the trained model to generate answers or predictions.

