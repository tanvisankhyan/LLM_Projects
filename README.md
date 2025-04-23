# LLM_Projects
A collection of LLM projects.


1. Multi-agent Research Artical Writer Using CrewAI

   This project showcases the implementation of a multi-agent system using CrewAI to automate the process of planning, writing, and editing high-quality blog content. Each AI agent is assigned a specialized role, enabling a structured and collaborative content development workflow. This project leverages the capabilities of OpenAI's GPT-3.5-turbo model for natural language understanding and generation.

   👥 AI Agents

i. Content Planner

            Role: Research and design a structured content outline.
            Goal: Develop a detailed content plan tailored to a specific topic.
            Backstory: Acts as a research and strategy lead, ensuring content relevance and SEO alignment.

ii. Content Writer

            Role: Draft the article based on the content plan.
            Goal: Generate an insightful, engaging, and accurate blog post.
            Backstory: Builds on the planner's outline to articulate ideas clearly, with emphasis on tone and coherence.

iii. Editor

            Role: Final proofing and editorial review.
            Goal: Polish the article for grammar, tone, and organizational voice.
            Backstory: Ensures the content meets editorial standards and is suitable for publication.


   🧩 Tasks & Workflow


Task 1: Content Planning

          Analyze trends and define the target audience.
          Create a detailed blog outline including SEO elements.
          Output: Structured content plan document.

Task 2: Content Writing

          Draft the blog post based on the plan.
          Integrate SEO keywords naturally and format for readability.
          Output: Complete blog post in Markdown format.

Task 3: Editing

           Perform final editorial review and polish the article.
           Ensure tone consistency and grammatical correctness.
           Output: Publication-ready Markdown blog post.



PROJECT 2: 

# AI-Powered Learning Content Generator

This project is an autonomous agent-based platform that automatically generates structured, engaging, and educational content from a single topic input. It is built using [CrewAI](https://github.com/joaomdmoura/crewAI) and designed for applications in learning platforms, microlearning tools, and EdTech environments.

## Overview

When a user provides a topic (e.g., "Introduction to Blockchain"), a team of AI agents collaborates to:

1. Research the topic
2. Generate structured learning content
3. Edit the content for clarity and quality
4. Create flashcards for revision
5. Generate a quiz to assess understanding

## Agents

| Agent               | Role                      | Purpose                                                  |
|---------------------|---------------------------|----------------------------------------------------------|
| Researcher          | Content Planner           | Gathers accurate and relevant information about the topic |
| Content Developer   | Learning Material Developer | Creates structured, accessible educational content       |
| Editor              | Educational Content Editor | Refines content for grammar, tone, and clarity           |
| Flashcard Creator   | Revision Assistant         | Converts content into digestible Q&A flashcards          |
| Quiz Builder        | Assessment Designer        | Develops multiple-choice questions to test knowledge     |

## Task Workflow

Tasks are executed in sequence, forming a pipeline:

1. Research the topic
2. Create learning material
3. Edit and polish the material
4. Generate flashcards
5. Build a quiz

The workflow uses `verbose=2` for detailed logging and monitoring.

## Installation

Install the required package:

```
pip install crewai==0.28.8 crewai_tools==0.1.6 langchain_community==0.0.29


