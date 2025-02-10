# Lab 3: Exploring High-Performance and Emerging Hardware for Deep Learning
## Deadline: February 18th at 2:30pm

## Summary
This assignment focuses on investigating various hardware approaches for accelerating deep learning. Each of the six teams will be randomly assigned one hardware topic to research. You do not have to test the hardware but should gather information on its performance implications, ethical considerations, and environmental impact.  

Refer to Chapter 6 in the d2l.ai textbook for foundational concepts:
- [Chapter 6: GPU Computing](https://d2l.ai/chapter_computational-performance/index.html)

## Using LLM Tools and Verifying Sources
You are encouraged to use Large Language Model (LLM) tools (e.g., GitHub Copilot, ChatGPT, or others) to help research your assigned hardware topic. However, always verify the accuracy of any information you receive from these tools, and include proper citations in your report as links to online sources used when using external sources or references provided by LLMs.

## Tasks

### Step 1: Organization into Teams
Each of the five teams should have 3–4 members. Assign tasks among team members to ensure equitable contributions. You will research your hardware topic, prepare demonstrations or experiments, and present to the class on February 18th.

### Step 2: Hardware Topics

**General-Purpose AI Hardware: GPUs & CPUs**  
Explore: Widely used GPU/CPU platforms, major companies (NVIDIA, AMD, Intel), cost structures, energy consumption, and performance trade-offs.  
- Guiding Questions: How do GPUs accelerate matrix operations? How do CPUs compare for AI workloads? What are the cost and energy implications?

**AI-Specific Accelerators (TPUs & Custom Chips)**  
Explore: Specialized instructions, major providers (Google, Tesla, etc.), cost vs. performance trade-offs, use cases in training and inference.  
- Guiding Questions: What specialized instructions do TPUs and other ASICs offer? How do they compare to GPUs in training vs. inference?

**Reconfigurable & Neuromorphic Hardware**  
Explore: FPGAs (Field-Programmable Gate Arrays), neuromorphic chip vendors, potential specialized use cases, power considerations.  
- Guiding Questions: When are FPGAs preferable to fixed-function chips? How do neuromorphic architectures differ from conventional AI accelerators?

**Cloud & Distributed AI Infrastructure**  
Explore: HPC clusters, resource allocation by major cloud providers, cost of scaling, on-premise vs. cloud vs. hybrid considerations.  
- Guiding Questions: How does cloud infrastructure allocate resources for deep learning? What are the trade-offs between cloud, on-premise, and hybrid systems?

**Edge AI & Embedded Systems**  
Explore: AI chips in mobile, IoT, robotics (NVIDIA Jetson, Apple Neural Engine), privacy-focused edge chips (Edge TPUs), deployment constraints.  
- Guiding Questions: How does running models on small devices differ from larger systems? What are the privacy and power considerations?

### Step 3: Research Your Assigned Hardware
Focus on gathering information, data, ethical/environmental issues.

### Step 4: Class Presentation
Teams will have at most 10 minutes to present, followed by a short Q&A. Keep the audience engaged with clear visuals, examples, or demos, and ensure each member contributes visibly.

### Step 5: Report
Document all experiments in `writing/report.md`, following prompts.

## Deliverables
2. Updated report (`writing/report.md`) with research findings, performance discussions, and Copilot usage (if relevant).
4. GitHub repository with commits demonstrating progress throughout the two weeks.

## Evaluation Criteria
This assignment uses contract-based grading. To receive `A` for the lab, you must:

- Address the exploration and guiding questions for the assigned hardware topic
- Meet the guidelines for the final presentation
- Submit intermediate commits on GitHub

For each component that is largely incomplete or incorrect, the assignment will receive a letter grade reduction.

GatorGrader is used to assess portions of the criteria above. The following will be checked by the GatorGrader tool:

2. **Technical Writing Checks**:
    - Ensure that `report.md` file exists in the `writing/` directory.
    - Write a minimum number of meaningful words (300) in the report.
    - Complete all TODOs and remove the TODO markers in the `report.md`.
4. **GitHub Repository Checks**:
    - Have at least a specific minimum number of commits (6) in the repository.


