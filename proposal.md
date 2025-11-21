Project Title

Prioritize – AI-Enhanced Smart To-Do List Application

Background

Task management apps are common, but many users still struggle with overwhelm, poor prioritization, and unclear goals. Traditional to-do lists tend to become long, unstructured “brain dumps” instead of effective productivity tools. With the rise of AI-assisted workflows, there is an opportunity to create a smarter, more intuitive task management experience that helps users stay focused, organized, and goal-oriented.

“Prioritize” aims to solve this by combining a simple interface with AI-generated task categorization, priority suggestions, and smart labels. This makes the app accessible for everyday users while demonstrating how AI can act as multiple development roles in the software process, as required in this course.

Purpose

The purpose of the application is to develop a clean, minimal, easy-to-use to-do list tool that uses AI to improve productivity. The system will allow users to enter tasks normally, while an AI agent will automatically classify them (e.g., “Work”, “Home”, “Urgent”, “Low Effort”, etc.) and suggest priority levels. This creates a more structured overview without requiring additional effort from the user.

The project’s goal is not to compete with large commercial apps, but to implement a realistic, functioning AI-supported software product within the scope of the course and demonstrate understanding of agent-based development, BMAD-framework usage, and the collaboration between human and AI agents.

Target Users

Primary users:

Students

Everyday individuals managing daily tasks

People who want a simple, structured to-do system without unnecessary complexity

Secondary users:

Anyone curious about AI-supported productivity tools

Beginners who need an intuitive interface

Users do not need technical experience. The interface must be simple enough for anyone to use without a tutorial.

Core Functionality (MVP)
Must Have

Create, edit, and delete tasks

Tasks stored locally or in a simple backend

AI-generated smart labels (e.g., “urgent”, “work”, “personal”)

AI-generated priority suggestions

Filter tasks by smart labels

Clean, minimal UI

Should Have (if time allows)

Light/Dark mode

Ability to mark tasks as complete

Reorder tasks

Task search

Nice to Have (optional)

AI suggestions for breaking down tasks into steps

Daily summary (“Here are your top 3 tasks today…”)

Scheduling tasks for specific days

Reminders

Technical Scope

For MVP, the scope should stay simple. A typical stack could include:

Frontend: Next.js or simple React

Backend: Node.js or Python FastAPI (whichever fits the template repo)

Database: Simple JSON file, Supabase, or in-repo storage (depending on course requirements)

AI Integration: GPT model for classification and prioritization

Complex features like user authentication, mobile views, advanced analytics, or multi-user systems are intentionally out of scope to keep development feasible.

Success Criteria

A clean, functional to-do application that runs without errors

AI successfully generates smart labels and priorities

The app demonstrates agent-based development as taught in the course

All required documentation (planning, architecture, prompts, reflections) is included

The project can be shown and explained during oral exam

Risks and Limitations

Over-engineering: keeping the project simple is essential

Time pressure: features must stay realistic

AI consistency: classification may vary, but acceptable for the course

Prioritization: avoiding scope creep

Conclusion

“Prioritize” will be a small but effective demonstration of an AI-supported productivity tool built using the BMAD-methodology and multiple AI agents. It is simple enough to complete within two weeks while still showing understanding of the core concepts in the course: context engineering, agent roles, prompt design, and AI-assisted development.

User Flows
User Flow 1: Add a New Task

User opens the application.

User clicks “Add task”.

User types in a task description.

AI suggests labels and priority.

User accepts or adjusts suggestions.

Task is added to the list.

User sees updated task overview.

User Flow 2: View and Filter Tasks

User opens the task list.

User selects a filter (e.g., “Urgent”, “Work”).

Application displays filtered tasks.

User clicks a task to view details or update it.

User Flow 3: Edit or Complete a Task

User clicks on an existing task.

AI updates labels/priority if text is changed.

User edits or marks task as completed.

Updated task appears in the list.
