# Write Articles using AI Agents
- Build Agentic flow for searching article using Web search Agent, Serper and the summarize article using LLM.
- crewAI Flow is composed of two AI agents, each with unique roles, goals, and tools. These agents collaborate on a series of tasks leveraging their collective skills to achieve complex objective.
Multiple crews are orchestrated to work together, each handling a specific part of the writing process.


### Dependencies

**Add your `OPENAI_API_KEY` into the `.env` file**  
**Add your `SERPER_API_KEY` into the `.env` file**


### Flow Structure

1.	**OutlineCrew**: This crew is responsible for generating the outline. It defines the structure based on the provided goal and topic.
2.	**SummaryCrew**: For each chapter outlined by the OutlineCrew, summary is created with detailed and coherent content.
3.	**Final Product**: After all chapters are written, the flow combines them into a single markdown file, creating a complete article ready to publish.
