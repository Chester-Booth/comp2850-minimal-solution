# COMP2850 HCI Portfolio Task

## Privacy and Ethics Statement
-  I confirm all participant data is anonymous (session IDs use P1_xxxx format, not real names).
-  I confirm all screenshots are cropped/blurred to remove PII (no names, emails, student IDs visible).
- I confirm all participants gave informed consent.
- I confirm that all results are real and not fabricated.
- I confirm this work is my own.

Name:
Date:

## Job Stories
Paste in your job stories here, in the format:
Story #X
When [situation/context],
I want [motivation/capability],
So [outcome/benefit],
Because [underlying need].
You should have 3-6 stories in total. One story may inform more than one pilot study task.

Story #1
When I'm inputting tasks,
 I want to be able to fix mistakes,
 So I don't have to re-input the task,
 Because it would waste time.

Story #2
When I'm viewing tasks,
I want the content to have a high-enough contrast,
So I can read tasks without difficulty,
Because it creates a temporary disability in high-glare environments and permanent exclusion for those with low vision.

Story #3
When I'm navigating by a keyboard, 
I want to be able to perform all actions i can with a mouse,
So i do not lose any functionality, 
Because it would exclude people without the ability to use a mouse temporarily (economic and social reasons) and create a permanent exclusion (motor injuries)  

Story #4
When I'm using the app,
I want to be able to be able to change the size of icons and headings 
So that i can more easily identify them 
Because forced content sizes creates a permanent exclusion (low-vision) and a temporary exclusion (display size)"



## Pilot Study – Planning & Consent-Gathering
This section will contain your planning of the pilot study.

### Task 1: Add Task
Scenario: "You need to 'prepare for a meeting on Friday'. Add this as a new task."
Action: Empty task list
Success Criteria: Participant enters task title, Adds Task, Task is visible in list 
Target Time: ~20 seconds
Linked to: Story #3

### Task 2: Edit Task (stopwatch)
Scenario: "The task 'Complete ecks vee six portfolio' has a misspelling, alter the task to 'Complete XV6 portfolio' and save the updated task."
Action: task 'Complete ecks vee six portfolio' in list 
Success Criteria: Participant locates the task, selects edit button, changes task name correctly, Changed task is visible in list
Target Time: ~1 minute
Linked to: Story #1, #3

### Task 3: Filter Task
Scenario: "You've been asked find all tasks with the word 'complete'. Use the filter to count all tasks that match this criteria, and they say how many tasks meet the criteria "
Action: several (8) tasks in the list with 3 containing 'complete' 
Success Criteria:  Participant locates the filter box, inputs search term correctly, counts all visible tasks , says Correct count
Target Time: ~20 seconds
Linked to: Story #3 

### Task 4: Resize Task App (stopwatch)
Scenario: "You've been asked to alter the task app for usage by someone with a vision impairment. Use the browser to increase the text size and report whether any content does not scale up."
Action: several tasks in list and browser with zoom functionality (firefox)
Success Criteria: participant affirms that all content scales up accordingly 
Target Time: ~3 minutes
Linked to: Story #4, #3


### Consent Script
[[pilot-protocol#Consent Process]]
"Thanks for agreeing to pilot our prototype. This is a quick usability test—about 15 minutes. I'll ask you to complete 4 tasks while I observe and take notes. I'm testing the interface, not you, so there are no wrong answers.
**What we're collecting**:
- Task completion times (from server logs and a stopwatch)
- Whether you complete each task successfully
- Errors or validation issues
- Your confidence ratings after each task
- My notes on any hesitations or accessibility issues
**What we're NOT collecting**:
- Your name, email, or student ID
- Screen recordings or audio
- Your device details beyond 'keyboard-only' or 'no-JS'

 I'll assign you a random session code (like `sid=X7kL9p`) which will appear in the logs. You can request that I delete all data linked to your session code at any time, even after today.

**You can stop at any time**, no questions asked, and it won't affect your grade.

 Do you have any questions before we start?"


### Participant Consent
| Participant Number | Read consent script to the participant? | Date and time that consent was given: |
| ------------------ | --------------------------------------- | ------------------------------------- |
| EXAMPLE            | X                                       | 20/11/2025 11:15                      |
| P1                 |                                         |                                       |
| P2                 |                                         |                                       |
| P3                 |                                         |                                       |
| P4                 |                                         |                                       |

#### Participant 1
##### Details of Participant:
*How did this user access the webapp? Keyboard/Mouse/Screenreader/No-JS etc.*

##### Notes:
Copy here, or link the location of this participant’s pilot study notes

##### Metrics:
*Copy here from metrics.csv, or link to the location of this participant’s pilot study log.*

#### Participant 2
##### Details of Participant:
*How did this user access the webapp? Keyboard/Mouse/Screenreader/No-JS etc.*

##### Notes:
Copy here, or link the location of this participant’s pilot study notes

##### Metrics:
*Copy here from metrics.csv, or link to the location of this participant’s pilot study log.*

### Metrics Breakdown
| Task         | Target Time | Mean Time | Median Time | Range of Times | Target - Mean |
| ------------ | ----------- | --------- | ----------- | -------------- | ------------- |
| EXAMPLE TASK | < 10        | 12.7      | 9.3         | 7.6 – 17.3     | -2.7          |
|              |             |           |             |                |               |
|              |             |           |             |                |               |
|              |             |           |             |                |               |
|              |             |           |             |                |               |


#### Reflection / Initial Thoughts
*Use this space to informally discuss your results, both qualitative and quantitative, and any initial trends which you spotted.*

>[!Example]
Although mouse, keyboard and screen users were able to consistently complete tasks in under the target time, keyboard-only users found it more challenging due to having to move backwards and forwards on the page, leading to significantly higher times for all tasks.*
> 



## Findings
You will now formalise your thoughts, reflections and data gathered from your pilot study into some findings which should be single issues with the site which you have identified from your evidence.

| Finding                                       | Source               | Observation                               | WCAG            | Impact (1-5) | Inclusion (1-5) | Effort (1-5) | Priority (Im + In - E) |
|-----------------------------------------------|----------------------|-------------------------------------------|-----------------|--------------|-----------------|--------------|------------------------|
| EXAMPLE Screen reader – errors not announced | metrics.csv L47-49 + P2 notes 14:23 | P2: “I didn’t hear any error”             | 3.3.1 Level A   | 5            | 5               | 3            | 7                      |
|                                               |                      |                                           |                 |              |                 |              |                        |
|                                               |                      |                                           |                 |              |                 |              |                        |
|                                               |                      |                                           |                 |              |                 |              |                        |
|                                               |                      |                                           |                 |              |                 |              |                        |

### Fixes To Implement

In this section you will select and explain up to three fixes you will be making based on your findings from the table.
These should be high priority findings, particularly those with WCAG Level A issues.


#### Fix 1

Finding: [the finding from the table above]

Explanation: [explain what the current issue is in simple terms]

Original Code: [paste/screenshot the code which you believe caused this error]

Fix: [Explain how you fixed this issue or explain what you did if you cannot work out how to fix the issue in a reasonable amount of time]

Final Code: [paste/screenshot the final, edited code of your fix – **if you used generative AI to support your coding you should acknowledge that here**.]

## WCAG Checklist
Once you have made your code changes and tested the site yourself, you should work through the WCAG checklist below, recording whether your app passes or fails, with a note stating **why**.

Be honest – if you have not met a criterion, you can explain why in the next section.

| Check               | Criterion                             | Level | Pass/Fail?      | Notes                                   |
| ------------------- | ------------------------------------- | ----- | --------------- | --------------------------------------- |
| **Keyboard**        |                                       |       |                 |                                         |
| K1                  | 2.1.1 All actions keyboard accessible | A     | [pass/fail]     | e.g., "Tested Tab/Enter on all buttons" |
| K2                  | 2.4.7 Focus visible                   | AA    | [pass/fail]     |                                         |
| K3                  | No keyboard traps                     | A     | [pass/fail]     |                                         |
| K4                  | Logical tab order                     | A     | [pass/fail]     |                                         |
| K5                  | Skip links present                    | AA    | [pass/fail/n/a] |                                         |
| **Forms**           |                                       |       |                 |                                         |
| F1                  | 3.3.2 Labels present                  | A     | [pass/fail]     |                                         |
| F2                  | 3.3.1 Errors identified               | A     | [pass/fail]     |                                         |
| F3                  | 4.1.2 Name/role/value                 | A     | [pass/fail]     |                                         |
| **Dynamic Content** |                                       |       |                 |                                         |
| D1                  | 4.1.3 Status messages                 | AA    | [pass/fail]     |                                         |
| D2                  | Live regions work                     | AA    | [pass/fail]     |                                         |
| D3                  | Focus management                      | A     | [pass/fail]     |                                         |
| **No-JS**           |                                       |       |                 |                                         |
| V1                  | 1.4.3 Contrast minimum                | AA    | [pass/fail]     |                                         |
| V2                  | 1.4.4 Resize text                     | AA    | [pass/fail]     |                                         |
| V3                  | 1.4.11 Non-text contrast              | AA    | [pass/fail]     |                                         |
| **Semantic**        |                                       |       |                 |                                         |
| S1                  | 1.3.1 Headings hierarchy              | A     | [pass/fail]     |                                         |
| S2                  | 2.4.1 Bypass blocks                   | A     | [pass/fail]     |                                         |
| S3                  | 1.1.1 Alt text                        | A     | [pass/fail]     |                                         |

#### Any Missing Criteria
If you did not meet any criteria, please note the number of the criteria (e.g. K2) and a brief (1-2 sentence) explanation of how you are not currently meeting it and a quick explanation of how you could address this.

Example with an alternative WCAG criterion:

> *E7 Error Suggestion – At present, when you try and edit a priority to a non-numerical value it gives an error but does not clarify how to meet the validation check. I could change this by giving more details in the alert such as ‘This must be a positive number’.*

## Second Pilot
You will re-run your pilot with 1-2 participants in order to evidence whether your changes improved the site.

| Participant Number | Read consent script to the participant? | Date and time that consent was given: |
|--------------------|----------------------------------------|---------------------------------------|
| EXAMPLE            | X                                      | 20/11/2025 11:15                     |
| P1                 |                                        |                                       |
| P2                 |                                        |                                       |


#### Participant 1
##### Details of Participant:

*How did this user access the webapp? Keyboard/Mouse/Screenreader/No-JS etc.*

##### Notes:
Copy here, or link the location of this participant’s pilot study notes

##### Metrics:
*Copy here from metrics.csv, or link to the location of this participant’s pilot study log.*


#### Participant 2
##### Details of Participant:

*How did this user access the webapp? Keyboard/Mouse/Screenreader/No-JS etc.*

##### Notes:
Copy here, or link the location of this participant’s pilot study notes

##### Metrics:
*Copy here from metrics.csv, or link to the location of this participant’s pilot study log.* 

### Metrics Breakdown - Study 2

| Task | Target Time | Mean Time | Median Time | Range of Times | Target - Mean |
|------|-------------|-----------|-------------|----------------|---------------|
|      |             |           |             |                |               |
|      |             |           |             |                |               |
|      |             |           |             |                |               |
|      |             |           |             |                |               |
|      |             |           |             |                |               |

#### Original Study Metrics
-copy and paste your filled metrics table from your first pilot study here for comparison -

### Comparison to Original Pilot Study

*Compare the results of this re-pilot to your original – did your fixes resolve the issues? Use both qualitative and quantitative data to support your argument*

### Conclusion

*Explain one full evidence chain by filling out the following table for **one** finding from your initial pilot study which you implemented a fix for.*

| Section                  | Explanation                                                        | Your evidence |
| ------------------------ | ------------------------------------------------------------------ | ------------- |
| Raw data                 | The line from the metrics file where you saw the issue             |               |
| Observation              | What did your pilot study participant say about it?                |               |
| Screenshot of the issue  | Both the code and the webapp if possible                           |               |
| WCAG?                    | If this error aligns to a certain WCAG criterion note that here    |               |
| Prioritisation           | What priority was the issue calculated at?                         |               |
| Fix implemented          | Screenshot of the fix which you completed (or attempted).          |               |
| Verification             | How do you know it was fixed?                                      |               |
| Before/After improvement |                                                                    |               |
| Re-pilot outcome         | The data from your re-pilot study showing the improvement working. |               |
