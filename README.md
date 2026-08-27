# Personal Agent – FL-07

## 1. What it does

This personal agent analyzes assignment briefs and turns them into a clear, practical action plan.

It identifies the assignment goal, required deliverables, step-by-step tasks, evaluation criteria, possible gaps or risks, and a final submission checklist.

The agent is designed to use the assignment brief and uploaded source material as its evidence rather than inventing requirements.

## 2. Who it is for

This agent is designed for students and learners who need help understanding complex assignment briefs and turning them into an actionable plan.

## 3. Setup

1. Open the Claude Project containing the Personal Agent – FL-07.
2. Make sure the required assignment brief or source document is available to the project.
3. Provide the assignment brief to the agent.
4. Ask the agent to analyze the brief.
5. Review the generated result against the original assignment requirements.

## 4. How to use it

Give the agent an assignment brief and ask it to identify:

* the assignment goal
* required deliverables
* step-by-step instructions
* evaluation criteria
* gaps or missing information
* practical precautions
* final submission checklist

The output can then be used as a working plan for completing the assignment.

## 5. Example

### Input

"Analyze this assignment brief and tell me what I need to do, what I need to submit, the evaluation criteria, and the final checklist."

### Output

The agent organizes the assignment into:

1. Goal
2. Required deliverables
3. Step-by-step completion process
4. Evaluation criteria
5. Potential gaps or risks
6. Final submission checklist

## 6. Architecture

```text
Assignment Brief / Source File
             |
             v
       Personal Agent
             |
             v
     Requirement Analysis
             |
     +-------+-------+
     |       |       |
     v       v       v
   Goal  Deliverables  Criteria
     |       |       |
     +-------+-------+
             |
             v
       Action Plan
             |
             v
      Final Checklist
```

## 7. V2 Evaluation Results

The final version was tested against assignment requirements including:

| Test                                       | Result |
| ------------------------------------------ | ------ |
| Identifies the assignment goal             | Pass   |
| Identifies required deliverables           | Pass   |
| Produces step-by-step instructions         | Pass   |
| Identifies evaluation criteria             | Pass   |
| Provides a final checklist                 | Pass   |
| Uses supplied source material              | Pass   |
| Avoids deliberately inventing requirements | Pass   |

The evaluation was based on comparing the agent's output with the original assignment brief.

## 8. Design Decision

A key design decision was to make the assignment brief and uploaded source material the main reference for the agent. This was chosen to reduce the risk of inventing requirements and to keep the generated plan connected to the actual assignment.

## 9. Limitations

The agent depends on the quality and completeness of the source material provided to it. If an assignment brief is incomplete, ambiguous, or missing important information, the agent may not be able to determine the missing details reliably. The output should therefore be checked against the original assignment requirements before submission.

## 10. AI Transparency

I built this project with AI assistance, primarily using Claude to develop and iterate the personal agent. I checked the agent's instructions, outputs, evaluation results, and final behavior myself against the original assignment requirements.

## 11. Project Status

The final version was tested through an end-to-end run and is ready for demonstration.
