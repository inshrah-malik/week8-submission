# Personal Agent — FL-07

## 1. Project Overview

My Personal Agent is an AI-assisted study and assignment-planning tool. It helps students understand complex assignment briefs and turn them into a clear, practical action plan.

The agent identifies the main goal, required deliverables, step-by-step tasks, evaluation criteria, possible gaps or risks, and a final submission checklist.

The main purpose is to make difficult assignment instructions easier to understand and follow.

## 2. Intended Users

The agent is mainly designed for students and learners who receive detailed or complicated assignment briefs and need help understanding exactly what they are expected to complete and submit.

## 3. What the Agent Does

The agent takes an assignment brief or source document as input and organizes the information into:

* Assignment goal
* Required deliverables
* Step-by-step instructions
* Evaluation criteria
* Important requirements
* Possible gaps or risks
* Final submission checklist

The agent is intended to make the assignment easier to understand without replacing the student's own judgment or verification.

## 4. Setup

The agent was built as a Claude Project.

To use the agent:

1. Open the Claude Project containing the Personal Agent.
2. Make sure the relevant assignment brief or source material is available.
3. Provide the assignment brief to the agent.
4. Ask the agent to analyze the assignment.
5. Review the generated response.
6. Compare important requirements with the original assignment brief before completing or submitting the work.

No additional software installation is required for the basic Claude Project setup.

## 5. Example Usage

A user can provide an assignment brief and ask:

> Analyze this assignment and tell me what I need to do, what I need to submit, how I should complete it step by step, what the evaluation criteria are, and give me a final checklist.

The agent then organizes the assignment into a structured plan.

For example, the output can contain:

1. Assignment purpose
2. Required tasks
3. Required deliverables
4. Step-by-step completion instructions
5. Evaluation criteria
6. Important things to check
7. Final submission checklist

## 6. Architecture

```text
Assignment Brief / Source Material
              |
              v
        Personal Agent
              |
              v
      Requirement Analysis
              |
       +------+------+
       |      |      |
       v      v      v
      Goal  Tasks  Criteria
       |      |      |
       +------+------+
              |
              v
        Action Plan
              |
              v
       Final Checklist
```

## 7. V2 Evaluation

I tested the final version of the agent using an actual assignment brief and checked the generated response against the original requirements.

The main evaluation checks were:

| Evaluation                               | Result |
| ---------------------------------------- | ------ |
| Identifies the assignment goal           | Pass   |
| Identifies required deliverables         | Pass   |
| Provides step-by-step instructions       | Pass   |
| Identifies evaluation criteria           | Pass   |
| Produces a final checklist               | Pass   |
| Uses the provided assignment information | Pass   |
| Produces an understandable response      | Pass   |

The evaluation focused on whether the agent could transform the assignment brief into a useful and accurate action plan.

## 8. Design Decision

One important design decision was to make the original assignment brief and provided source material the main reference for the agent.

I chose this approach because assignment requirements should come from the actual brief rather than assumptions. This helps reduce the risk of adding requirements that are not part of the assignment.

## 9. Limitations

The main limitation is that the agent depends on the quality and completeness of the information provided to it.

If an assignment brief is unclear, incomplete, or missing important information, the agent may not be able to determine the missing information accurately.

For this reason, I still compare the agent's output with the original assignment requirements before submitting work.

## 10. AI Transparency

I built this project with AI assistance, primarily using Claude to create and improve the Personal Agent.

I personally checked the agent's instructions, outputs, testing results, and final behavior against the original assignment requirements. AI was used as a building and thinking partner, while I remained responsible for checking the final result.

## 11. Current Status

The Personal Agent has been tested through an end-to-end assignment analysis and is documented here for demonstration and evaluation.

## 12. Demo

Demo video: **https://drive.google.com/file/d/1uwN80z5Xuxz37DLosoVYK2mJgH148KZ6/view?usp=sharing**
