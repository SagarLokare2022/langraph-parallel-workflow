<p align="center">
  <img src="output_image.png" width="600">
</p>

🧠 LangGraph Parallel Workflow — UPSC Essay Evaluation Agent

📌 Overview

This project demonstrates a LangGraph-powered parallel workflow designed for evaluating UPSC-style essays across three dimensions simultaneously:

Thought Quality

Language & Writing Style

Depth of Analysis

All three evaluations run in parallel, and the workflow merges them into a final unified evaluation using LangGraph’s StateGraph.

This showcases your strong understanding of LangGraph, agentic workflows, parallel task execution, and structured evaluation systems—high-value skills for GenAI Developer & LLM workflow roles.

🚀 Key Features
🔹 Parallel Nodes

evaluate_thought

evaluate_language

evaluate_analysis

🔹 Final Aggregation

final_evaluation merges outputs from all branches.

🔹 Clean Graph Visualization

The workflow automatically generates a graph visualization (shown above) demonstrating branching, merging, and execution flow.

🧩 Tech Stack
Component	Used For
LangGraph	Creating the workflow graph & parallel execution
LangChain OpenAI	Calling GPT models for evaluations
Python 3.12+	Main development
Jupyter Notebook	Experimentation & running workflow
dotenv	Managing environment variables
Pydantic	Typed states & structured data
