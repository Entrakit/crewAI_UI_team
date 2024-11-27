# UI Design Crew - CrewAI Project

This project is a custom UI Design Crew built with CrewAI to streamline the complex process of user interface (UI) design. It uses specialized agents that perform unique roles, working collaboratively to cover all aspects of the UI design pipeline. This modular setup allows it to integrate into larger projects, with each agent handling a focused task, from initial research to final optimization.

## Project Structure

- **agents.py**: Defines the individual agents that take on specialized roles within the UI design crew.
- **tasks.py**: Defines tasks for each agent, tailored to their role in the UI design process.
- **CustomCrew class**: Assembles the agents and tasks into a crew that can be executed as a complete UI design team.
- **main.py**: Entry point for running the UI Design Crew, which prompts for user input and kicks off the design process.

## Agent Roles

1. **Research and Inspiration Agent**: Collects design inspiration and user insights.
2. **Wireframing Agent**: Creates low-fidelity wireframes for initial layout.
3. **Prototype Design Agent**: Develops high-fidelity, interactive prototypes.
4. **User Feedback Agent**: Gathers and analyzes user feedback to refine the design.
5. **Optimization Agent**: Optimizes the final design for performance and accessibility.

## Usage

### Prerequisites
Ensure you have the following installed:
- Python 3.x
- Required Python libraries (`crewai`, `langchain`, `langchain_openai`, `decouple`, `textwrap`)

Install dependencies with:
```bash
pip install crewai langchain langchain_openai decouple textwrap duckduckgo-search
