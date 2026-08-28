# Personal Academic Assistant
## What Does the Agent Do?

The Personal Academic Assistant is an AI agent that helps students understand complicated assignment briefs.

It reads an assignment brief and explains:
- What the assignment is about
- What the student needs to submit
- What requirements must be followed
- What steps the student should take
- What the evaluation criteria are
- What might be missing
- What the student should check before submitting
- ## Who Is It For?

This agent is mainly for students who find long or complicated assignment instructions difficult to understand.

It helps students turn an assignment brief into a simple step-by-step plan.
## Setup

To use this agent:

1. Create or open a Claude account.
2. Create a new Claude Project.
3. Add the Personal Academic Assistant instructions to the project instructions.
4. Save the project.
5. Upload an assignment brief such as a PDF or DOCX file.
6. Start a conversation inside the project.
7. Ask the agent to analyze the assignment.
8. ## How to Use the Agent

1. Upload an assignment brief to the Claude Project.
2. Ask the agent to analyze the assignment.
3. The agent identifies the main goal.
4. It identifies the required deliverables.
5. It explains the assignment in simple language.
6. It creates step-by-step instructions.
7. It creates a checklist.
8. It identifies possible gaps or things that need to be checked.
9. ## Example

### Example Input

Upload an assignment brief and ask:

"Analyze this assignment. Tell me the goal, deliverables, requirements, evaluation criteria, step-by-step tasks, checklist, and anything I might be missing."

### Example Output

The agent produces:
- The assignment goal
- Required deliverables
- Requirements
- Evaluation criteria
- Simple explanation
- Step-by-step instructions
- Checklist
- Possible gaps
- Precautions
- ## Simple Architecture
  ```text

Assignment Brief
       |
       v
Claude Project
       |
       v
Personal Academic Assistant
       |
       v
Assignment Analysis
       |
       v
Goal + Requirements + Steps + Checklist
       |
       v
Student Action Plan





# Step 10: Add your V2 evaluation

This is important.

You already tested your agent with your **FL-07 Assignment Brief.docx**.



## V2 Evaluation

For the v2 test, I uploaded the FL-07 Assignment Brief document to the Personal Academic Assistant.

The agent successfully analyzed the assignment and produced:

- Assignment goal
- Required deliverables
- Plain-language explanation
- Step-by-step instructions
- Checklist
- Requirements and evaluation criteria
- Possible gaps
- Precautions

The test showed that the agent can successfully turn an assignment brief into a structured and actionable student plan.
## Limitations

The agent has some limitations:

1. It depends on the information provided in the assignment brief.
2. If the assignment instructions are unclear, the agent may misunderstand them.
3. AI-generated information should be checked against the original assignment.
4. The agent does not replace the teacher or instructor.
5. The student is responsible for checking the final requirements before submitting the assignment.
## Guardrail

The original assignment brief is the source of truth.

The student should always compare the agent's answer with the original assignment requirements before submitting work.

If information is unclear or missing, the agent should identify the uncertainty instead of pretending that an assumption is definitely correct.
## Demo Video

The live demonstration video is available here:

[YouTube Demo Video](VIDEO-LINK-WILL-BE-ADDED-HERE)
