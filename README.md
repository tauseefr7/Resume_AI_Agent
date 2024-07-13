# Resume_AI_Agent

**Project Overview:**
This project is a multi ai agent created using the Crew AI framework, one purpose of it is to take a CV/resume and tailor it to a provided job description. Another is to provide interview preparation materials, this includes interview questions and discussion points.

**Tools used:**
  FileReadTool,        # Tool to read files
  ScrapeWebsiteTool,   # Tool to scrape content from websites
  MDXSearchTool,       # Tool to perform semantic searches on MDX files
  SerperDevTool        # Tool to perform search operations

**Agents and Their Roles**

**Legal Job Researcher:** Provides analysis of legal job postings, specifically extracting essential skills and qualification sought by employers.
Output: Structured list of job requirements.

**Profiler Agent:** Creates detailed personal and professional profiles.
Output: Comprehensive profile document.**

**Resume Strategist Agent:** Aligns resumes based on job requirements and profile.
Output: Refined resume highlighting relevant qualifications and experience.

**Interview Preparer Agent:** Generates interview questions and discussion points.
Output: Document with interview materials.

**Crew Setup**
Crew Composition: Includes all agents (Researcher, Profiler, Resume Strategist, Interview Preparer).
Task Execution: Agents collaborate on tasks sequentially, utilising outputs from previous tasks.

The structure of the multi AI agent can be seen below:
![multi_ai_agent_system visual](https://github.com/user-attachments/assets/656f3171-080d-49f9-8091-94332f48b12a)

Acknowledgements: Big thanks to João Moura and team for creating a great Multi AI Agent framework. 

