# Design, Develop, and Deploy Multi-Agent Systems with CrewAI

Projects and code implementations from the DeepLearning.AI course **"Design, Develop, and Deploy Multi-Agent Systems with CrewAI"** (December 2025).

## 📚 Course Overview

This course, taught by João Moura (Co-founder and CEO of CrewAI), provides comprehensive training on building production-ready multi-agent systems that automate complex, end-to-end workflows. The course bridges the gap between prototyping AI agents and deploying them at scale with reliability and control.

## 🎯 Learning Objectives

By completing this course, you will:

- Build multi-agent systems that plan, reason, and collaborate to solve complex problems
- Design intelligent agent teams using tools, memory, and guardrails
- Implement real-world design patterns for agent coordination and collaboration
- Monitor and debug agent performance using traces and observability tools
- Evaluate agent behavior with LLM-as-a-Judge techniques
- Apply best practices for scaling agents from prototype to production

## 📂 Repository Structure

This repository contains notebooks and projects organized by course modules:

```
├── Module1/  # Design and Development Fundamentals
├── Module2/  # Agent Control and Tool Integration
├── Module3/  # Advanced Orchestration and Monitoring
└── README.md
```

## 📖 Module Summaries

### Module 1: Design and Development Fundamentals
**Building Single- and Multi-Agent Systems from Concept to Prototype**

This module covers the foundational concepts of designing and developing agent systems:

- Creating single-agent and multi-agent architectures
- Tuning agent behavior using context engineering
- Understanding agent roles, goals, and backstories
- Examining real-world use cases and production deployments
- **Practical Application:** Automated Code Reviewer system

**Key Topics:**
- Agent system architecture and design patterns
- Context engineering for agent behavior
- Production considerations and case studies
- Role-playing and task delegation

---

### Module 2: Agent Control and Tool Integration
**Controlling Behavior with Guardrails, Memory, and Tools**

This module focuses on enhancing agent capabilities through advanced control mechanisms:

- Implementing guardrails to ensure safe and predictable behavior
- Using execution hooks for fine-grained control
- Adding memory systems (short-term, long-term, and shared)
- Building and integrating custom tools
- Understanding the Model Context Protocol (MCP) for expanding agent capabilities

**Key Topics:**
- Guardrails and error handling
- Memory architectures for agents
- Custom tool development
- Model Context Protocol (MCP) integration
- Knowledge management for richer decision cycles

---

### Module 3: Advanced Orchestration and Monitoring
**Complex Coordination Patterns and Production Monitoring**

This module explores sophisticated orchestration strategies and production-ready monitoring:

- Orchestrating agents using sequential, parallel, hierarchical, hybrid, and asynchronous patterns
- Implementing Flows as a low-level control layer
- Monitoring multi-agent systems with tracing and observability tools
- Training agents using human-in-the-loop feedback
- Conducting structured evaluations with LLM-as-a-Judge
- **Practical Application:** Automated Code Review Flow with advanced orchestration

**Key Topics:**
- Sequential, parallel, and hierarchical coordination
- CrewAI Flows for low-level control
- Tracing, sampling, and observability
- Human feedback integration
- LLM-as-a-Judge evaluation techniques

---

### Module 4: Real-World Deployment and Case Studies
**Industry Adoption and Production Patterns**

This module examines how multi-agent systems are deployed in production environments:

- Analyzing business adoption across industries and functions
- Learning from chatbots to workflow co-pilots evolution
- Studying real deployment case studies from industry leaders
- Understanding deployment challenges and solutions

**Featured Case Studies:**
- Exa
- Snyk
- Weaviate
- AB InBev

**Key Topics:**
- Industry adoption patterns
- Production deployment strategies
- Real-world implementation challenges
- Scaling considerations for thousands of users

## 🛠️ Key Technologies and Concepts

### Core Building Blocks
- **Agents:** Autonomous entities with specific roles, goals, and backstories
- **Tasks:** Discrete units of work assigned to agents
- **Crews:** Teams of agents working together
- **Tools:** Built-in and custom capabilities agents can use
- **Memory:** Short-term, long-term, and shared memory systems
- **Guardrails:** Safety and control mechanisms

### Advanced Features
- **Execution Hooks:** Fine-grained control over agent behavior
- **Flows:** Low-level orchestration control layer
- **Model Context Protocol (MCP):** Expanding agent tool capabilities
- **Tracing:** Monitoring and debugging agent decisions
- **Human-in-the-Loop:** Training and feedback mechanisms

### Coordination Patterns
- Sequential execution
- Parallel processing
- Hierarchical delegation
- Hybrid workflows
- Asynchronous operations

## 🚀 Practical Applications Built in Course

1. **Automated Code Reviewer** - Multi-agent system for code review and analysis
2. **Meeting Co-Pilot** - AI assistant for meeting management and follow-up
3. **Deep Researcher** - Comprehensive research automation system

## 🎓 Prerequisites

- Basic Python programming knowledge
- Familiarity with prompt engineering concepts
- Understanding of generative AI and LLMs
- Interest in building production AI systems

## 💻 Setup and Installation

```bash
# Clone the repository
git clone https://github.com/mjgrav2001/Design_Develop_Deploy_Multi_Agent_Systems_CrewAI.git

# Navigate to the repository
cd Design_Develop_Deploy_Multi_Agent_Systems_CrewAI

# Install dependencies (if requirements.txt is available)
pip install -r requirements.txt
```

## 📝 Usage

Each module folder contains Jupyter notebooks with hands-on labs and implementations. To run the notebooks:

1. Navigate to the desired module directory
2. Launch Jupyter Notebook or JupyterLab
3. Open the notebook file (.ipynb)
4. Follow the instructions within each notebook

## 🔗 Additional Resources

- **Course Link:** [DeepLearning.AI Course Page](https://www.deeplearning.ai/courses/design-develop-and-deploy-multi-agent-systems-with-crewai/)
- **Coursera:** [Course on Coursera](https://www.coursera.org/learn/design-develop-and-deploy-multi-agent-systems-with-crewai)
- **CrewAI Documentation:** [Official CrewAI Docs](https://docs.crewai.com/)
- **CrewAI GitHub:** [CrewAI Repository](https://github.com/joaomdmoura/crewAI)

## 👥 Instructor

**João Moura** - Co-founder and CEO of CrewAI

João created CrewAI as an open-source framework for building and orchestrating multi-agent systems, and brings extensive experience in designing workflows for collections of agents.

## 📚 Related Courses

- **Multi AI Agent Systems with crewAI** (DeepLearning.AI Short Course)
- **Practical Multi AI Agents and Advanced Use Cases with crewAI** (DeepLearning.AI)
- **Agent Skills with Anthropic** (DeepLearning.AI)

## 🤝 Contributing

This repository contains personal course work and implementations. Feel free to:
- Fork the repository for your own learning
- Submit issues if you find errors or have questions
- Share your own implementations and improvements

## 📄 License

This repository contains educational materials from DeepLearning.AI's course. Please respect the course's terms of use and intellectual property rights.

## 🙏 Acknowledgments

- DeepLearning.AI for creating and offering this comprehensive course
- João Moura and the CrewAI team for developing the framework and teaching the course
- Andrew Ng and the DeepLearning.AI team for their continued commitment to AI education

---

**Note:** This repository represents coursework completed in December 2025 as part of ongoing professional development in AI/ML engineering and multi-agent systems.
