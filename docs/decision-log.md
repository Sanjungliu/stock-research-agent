# Decision 001

Title:
Why build a Stock Research Agent?

Problem:
Need a project that teaches modern AI Engineering concepts.

Alternatives:
- Chatbot
- Customer Support Agent
- Coding Agent
- Document Q&A Agent

Decision:
Build a Stock Research Agent.

Reason:
The project naturally requires:
- Tools
- Workflows
- RAG
- Memory
- Multi-agent systems
- Evaluation
- Monitoring

Tradeoffs:
Requires financial data sources and domain learning.

Date:
2026-06-16

# Decision 002

Title:
Why Documentation First?

Decision:
Create architecture and decision records before implementation.

Reason:
Understand the system before building it.

Benefits:
- Better learning
- Better architecture discussions
- Easier future maintenance

Tradeoffs:
- Slower initial progress

# Decision 003

Title:
Research Assistant vs Investment Analyst

Alternatives:
1. Research Assistant
- Only presents data and summaries

2. Investment Analyst
- Produce recommendations and investment theses

Decision:
Build an Investment Analyst.

Reason:
Provide a more realistic and challenging
AI engineering project while remaining
focused on decision support rather than
trade execution.

Tradeoffs:
Requires more sophisticated evaluation,
financial knowledge, and data quality.

# Decision 004

Title:
Why Start With a Single Agent?

Alternatives:
1. Single Agent
2. Multi-Agent

Decision:
Start with a single agent,

Reason:
Learn tools, prompts, and workflows before
adding coordination complexity.

Benefits:
- Easier debugging
- Faster iteration
- Smaller learning surface

Tradeoffs:
- Less specialized behaviour
- Limited scalability

Revisit When:
- The agent exceeds 5-10 tools
- Different analysis tasks require specialized prompts
- Tool selection becomes unreliable
- Workflow complexitu becomes difficult to maintain

# Decision 005

Title:
Why LangChain before LangGraph?

Alternatives:
1. Use LangChain first
2. Use LangGraph directly

Decision:
Start with Langchain first.

Reason:
- Need to build it as simple as possible in initial version
- The main point here is to learn the fundamentals, not to build a fancy architecture directly

Benefits:
- Learn fundamental more deeply
- Know when to use LangChain and when need to use LangGraph
- Smaller learning surface

Tradeoffs:
- Cant really scalable if the app become more complex

Revisit When:
- Need more control of the workflow later
- the architecture grows into more complex system
- has multiple component that need to handled
