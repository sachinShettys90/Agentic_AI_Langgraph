# AgenticAI Basics

This directory contains fundamental examples and tutorials for building agentic AI applications using **LangGraph**. Each notebook demonstrates core concepts and patterns for building sophisticated multi-step workflows.

## 📚 Notebooks Overview

### 1. **1_BMI_state_demo.ipynb**
Demonstrates basic **state management** in LangGraph. Shows how to maintain and update state across workflow steps using a simple Body Mass Index (BMI) calculation example.

**Key Concepts:**
- State initialization
- State transitions
- Basic node execution

---

### 2. **2_LLmqa_demoSequential.ipynb**
Introduces **sequential workflows** with LLM-based question answering. Shows how to chain multiple steps together in a linear fashion.

**Key Concepts:**
- Sequential node chaining
- LLM integration
- Question-answering pipelines
- State passing between nodes

---

### 3. **3_prompt_chaining.ipynb**
Explores **prompt chaining** techniques to break down complex tasks into smaller, manageable steps. Each step builds on the output of the previous one.

**Key Concepts:**
- Multi-step prompt chaining
- Output parsing and passing
- Iterative refinement
- Task decomposition

---

### 4. **4_PrallelWorkflow.ipynb**
Demonstrates **parallel execution** where multiple independent tasks run concurrently instead of sequentially.

**Key Concepts:**
- Parallel node execution
- Concurrent task handling
- State aggregation
- Performance optimization

---

### 5. **5_ParallelWorkflow_EssayEvaluation.ipynb**
A practical example of parallel workflows applied to **essay evaluation**. Multiple evaluators (nodes) assess different aspects of an essay in parallel.

**Key Concepts:**
- Parallel multi-agent evaluation
- Aggregating parallel results
- Real-world use case implementation

---

### 6. **6_Conditional_Workflow_quadEquation.ipynb**
Introduces **conditional branching** logic. Routes execution based on conditions (e.g., solving quadratic equations with different methods).

**Key Concepts:**
- Conditional routing
- Decision-based branching
- Dynamic workflow control

---

### 7. **7_Conditional_workflow_review_reply.ipynb**
Demonstrates conditional workflows in a **review and reply** scenario. Different paths are taken based on the type of review or content.

**Key Concepts:**
- Content-based routing
- Multi-path workflows
- Conditional logic in production scenarios

---

### 8. **8_Iterative_workflow.ipynb**
Shows how to build **iterative workflows** that repeat steps until a condition is met (e.g., refinement loops, feedback loops).

**Key Concepts:**
- Loop control
- Termination conditions
- Iterative refinement
- Convergence patterns

---

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- Jupyter Notebook or JupyterLab
- LangGraph and dependencies (see `requirement.txt`)

### Installation
1. Activate your Python virtual environment:
   ```bash
   myenv\Scripts\activate
   ```

2. Install required packages:
   ```bash
   pip install -r ../requirement.txt
   ```

3. Launch Jupyter:
   ```bash
   jupyter notebook
   ```

4. Open any notebook to explore the examples.

---

## 📖 Learning Path

**Recommended order of exploration:**

1. Start with **1_BMI_state_demo.ipynb** - Understand state basics
2. Move to **2_LLmqa_demoSequential.ipynb** - Learn sequential workflows
3. Explore **3_prompt_chaining.ipynb** - Master prompt chaining
4. Study **4_PrallelWorkflow.ipynb** - Understand parallel execution
5. Review **5_ParallelWorkflow_EssayEvaluation.ipynb** - See real-world application
6. Learn **6_Conditional_Workflow_quadEquation.ipynb** & **7_Conditional_workflow_review_reply.ipynb** - Master conditionals
7. Conclude with **8_Iterative_workflow.ipynb** - Advanced iteration patterns

---

## 🔑 Key Concepts

### State Management
Control and track data flow throughout your workflow using persistent state objects.

### Workflows
Connect multiple steps (nodes) together to create complex, multi-step AI systems.

### Nodes
Individual processing units that transform state. Can be LLM calls, Python functions, tools, etc.

### Edges
Connections between nodes that define workflow flow and data passing.

### Conditional Routing
Dynamically choose the next node based on state or intermediate results.

### Parallel Execution
Run multiple nodes concurrently to improve performance and handle complex multi-agent scenarios.

---

## 🛠️ Common Patterns

- **Sequential Pipeline**: Step-by-step processing
- **Parallel Multi-Agent**: Multiple agents working on different aspects
- **Conditional Branching**: Different paths based on logic
- **Iterative Loops**: Repeat until convergence
- **Hybrid Workflows**: Combine patterns for complex scenarios

---

## 📝 Notes

- Each notebook is self-contained and can be run independently
- Modify examples to experiment with different configurations
- Use these as templates for your own LangGraph applications

---

## 🤝 Contributing

To extend this tutorial series:
1. Create a new notebook following the naming pattern
2. Document key concepts clearly
3. Include both code and markdown explanations
4. Test all cells before committing

---

## 📞 Support

For questions about LangGraph, refer to the official [LangGraph Documentation](https://python.langchain.com/docs/langgraph/).

