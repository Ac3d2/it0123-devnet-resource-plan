# IT0123 DevNet Resource Validation Plan

## Student and Project

- Name: Benavides, John Paul B.
- Section: TN32
- Repository name: `it0123-devnet-resource-plan`

## Purpose

Explain in 2-3 sentences why selecting the correct DevNet resource matters before beginning a network-automation task.

The first step in any task is always planning then preparation. You don't want to waste your time pouring your effort into a resource that wasn't meant for your specific needs.

## Validated Resource Decisions

Summarize your four selections from `student_plan.json`. For each use case, state the selected resource, the most important requirement, and the official Cisco evidence used.

UC1: always-on-sandbox, requiring immediate access dictates you to use this resource 
https://developer.cisco.com/docs/sandbox/

UC2: Reservation-sandbox, It is a bit more tricky but the defining situation to use this resource is requiring a private access area nad administrative controls.
https://developer.cisco.com/docs/sandbox/

UC3: Learning-lab, pretty self explanatory. You need material that would conduce a learning environment and where mistakes wont cost anything but your time.
https://developer.cisco.com/learning/

UC4: Code-exchange, Well it's the last option left that wasn't picked. And code exchanges are, well, where you exchange code with other people. It can act as a repository to find other people's code.
https://developer.cisco.com/codeexchange/

## AI Evaluation

Identify at least one AI recommendation that you accepted, rejected, or modified. Explain the evidence behind your decision.

Something me and the Ai disagreed on is the purpose of the reservation-sandbox. I view it in terms of its necessity for privacy and administration. But Gemini thinks it's purpose is for isolated testing.

## Validation Evidence

- Validator result: 9/9
- Command used: ./validate_plan.py
- Official Cisco pages reviewed:

https://developer.cisco.com/docs/sandbox/
https://developer.cisco.com/learning/
https://developer.cisco.com/codeexchange/

## Git Evidence

- Initial commit message: "Initial commit: Add project README"
- Validation commit message: "Validation success!"
- Output of `git log --oneline`: 6093565 (HEAD -> master) Initial commit: Add project README

## AI-Use Disclosure

State the AI tool used, the type of assistance received, what was independently checked, and what you revised.

I have used Gemini. Before I asked AI to choose which of the four material to choose from I made my own decisions and then I cross-referenced.

I have also never used Git before, so I had Gemini give me a quick rundown on how it works.