# Coursera course
[Multi AI Agent Systems with crewAI by DeepLearning.AI](https://www.coursera.org/projects/multi-ai-agent-systems-with-crewai)

### Resumé and job seeking
##### 4 Agents
1. Tech job researcher
2. Personal profiler for engineers
3. Resume strategist for engineers
4. Engineering interview preparer

### Convert potential customers to customers
#### 4 agents
1. research (data collection) on potential customer
2. comparison to other known customers
3. score this type of potential customer
4. create talking points

### Mult-agent customer support agent
Follows the framework, define the following attributes to optimise performance:
1. Role playing, Focus, Cooperation
2. Tools, guardrails, Memory

### Mental framework for agent creation
* Think as a manager
* Thank about what is the goal and what is the process
* What kind of people I would hire to get the job done?
* Use keywords to be specific about the essential qualifications
##### Specific to CrewAI
* Agents 'self improve" using memory
* Guardrails prevent agents from going into "rabbit holes" (unproductive, repetitive loops)
* Agents always attempt to get to an answer (avoid iterating indefinitely)
* Focus
  * narrowly defined task
  * specific agent roles and objectives
  * limited set of tools assigned to one agent

### Customer outreach campaign
* Need tools that have the following attributes:
  1. Fault-tolerant (fail gracefully, not stop execution, send error message back to agent to retry)
  2. Versatile (handle different types of inputs)
  3. Caching (smart caching, cross-agent caching, prevent unnecessary caching, stay within rate limits, shorter execution times)
 
### Key elements of well-defined tasks
1. Clear description of the task
2. Set a clear and concise expectation
3. Set context
4. Set a callback
5. Override Agent tools with specific task tools
6. Force human input before end of task
7. Execute asynchronously
8. Output as Pydantic / JSON / file
9. Run in parallel

