# Enterprise AI Agents for Social Impact

## About the organization
Benevity is a Calgary-based software company that provides a corporate purpose platform supporting corporate social responsibility initiatives. Founded in 2008, Benevity helps global enterprises manage and track employee giving, volunteering, and grant-making programs, processing billions of dollars in donations annually. The platform enables organizations to engage employees, customers, and communities through vetted nonprofit partnerships.

https://benevity.com/

## About the project
This project explores the design and development of enterprise-grade AI agents that support social impact initiatives within Benevity’s ecosystem. AI agents are positioned as autonomous systems capable of reasoning, planning, and executing tasks, going beyond content generation to action-oriented workflows.

The project is structured as an exploratory research and development initiative rather than a fixed-specification build. Student teams are expected to operate as product researchers and solutions architects, identifying high-value problem areas and designing production-ready solutions using Benevity’s cloud and AI stack. 

Student teams will conduct internal stakeholder interviews to determine which one of the two candidate projects to pursue. After selecting a project, teams will engage heavy development, building a functional
AI Agent prototype integrated into Benevity’s ecosystem.

### Candidate A: Automated Campaign Kits

- **The Concept:** Benevity helps companies respond to natural disasters by creating
"Content Kits" (news summaries, images, donation links) for their employees.
- **The History:** A previous student team built a proof-of-concept (POC) using AWS, LangChain, and OpenAI to scrape news and summarize events. While successful as a POC, it was not brought into product roadmaps and productionized. With the rapid evolution of AI services, there is an opportunity to revisit and enhance this concept.
- **The Challenge:** Re-imagine this solution using an enterprise-grade stack. Instead of LangChain and AWS, the team would rebuild this agent using GCP AI technologies such as (but not limited to) Agent Development Kit (ADK) and Vertex AI. The goal is higher autonomy, better reliability in news verification, and seamless deployment on GCP.

### Candidate B: Intelligent Nonprofit Matching

- **The Concept:** When a donor gives money to a nonprofit, they often lose visibility on the
outcome.
- **The Challenge:** Build an agent that autonomously "researches" a specific nonprofit by
scraping public data, annual reports, and news updates. The Agent would then
synthesize this unstructured data into a compelling "Impact Story" or narrative that can
be presented to the donor, closing the feedback loop and encouraging further
generosity.

## Intended users
- Internal Benevity teams involved in product development and social impact initiatives  
- Corporate clients using Benevity’s platform  
- Donors and employees engaging with giving, volunteering, and nonprofit programs  

## Required Technology 
- Google Cloud Platform (GCP) [a must]
- Vertex AI 
- Google Agent Builder / Agent Development Kit (ADK)  
- Python for AI workflows and agent logic  
- Java for backend integration where required  
- Large Language Models (LLMs), Retrieval-Augmented Generation (RAG), Docker, and APIs  
