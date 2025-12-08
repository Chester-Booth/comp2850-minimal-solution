# COMP2850 HCI Portfolio Task

## Privacy and Ethics Statement
-  I confirm all participant data is anonymous (session IDs use P1_xxxx format, not real names).
-  I confirm all screenshots are cropped/blurred to remove PII (no names, emails, student IDs visible).
- I confirm all participants gave informed consent.
- I confirm that all results are real and not fabricated.
- I confirm this work is my own.


## Job Stories

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
Action: several (11) tasks in the list with 3 containing 'complete' 
Success Criteria:  Participant locates the filter box, inputs search term correctly, counts all visible tasks , says Correct count
Target Time: ~20 seconds
Linked to: Story #3 
### Task 4: Resize Task App (stopwatch)
Scenario: "You've been asked to alter the task app for usage by someone with a vision impairment. Use the browser to increase the text size and report whether any content does not scale up."
Action: several tasks in list and browser with zoom functionality (firefox)
Success Criteria: participant uses the browser's build in zoom functionality, checks the app, affirms that all content scales up accordingly 
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


### Participant Consent and Notes

| Participant Number | Read consent script to the participant? | Date and time that consent was given: |
| ------------------ | --------------------------------------- | ------------------------------------- |
| P1                 | X                                       | 04/12/2025 15:25                      |
| P2                 | X                                       | 04/12/2025 16:14                      |


#### Participant 1
##### Details of Participant:
Keyboard + Mouse with JS
##### Notes:
###### Debrief 

1. what was the hardest task to complete?
"most tasks are easy, the most uncomfortable one is the filter as the layout could be improved by bolding filtered words to indicate \[the filtered term]"
2. what could be improved about the application?
"bolding filtered words to indicate \[the filtered term]"
3. was there anything that was a surprise or did not work as intended? 
"most of them are fine its just in the beginning the task didn't show up"
4. was there any task you weren't sure if you has completed successfully?
"aside from the first task, no, everything works as usual"

##### Metrics:
```csv
2025-12-04T15:35:43.114230486Z,P1_6680fa,r_28b111ca,T1_filter,success,,9,200,on
2025-12-04T15:35:49.434900361Z,P1_6680fa,r_61da63f9,T0_list,success,,16,200,off
2025-12-04T15:36:33.251393905Z,P1_6680fa,r_4608535d,T3_add,success,,9,200,on
2025-12-04T15:36:37.055921185Z,P1_6680fa,r_82a7cfce,T0_list,success,,10,200,off
2025-12-04T15:38:56.363602029Z,P1_6680fa,r_efbef123,T0_list,success,,16,200,off
2025-12-04T15:39:10.308132299Z,P1_6680fa,r_ee47fd0b,T0_list,success,,12,200,off
2025-12-04T15:39:39.015675500Z,P1_6680fa,r_7e5d1d1f,T0_list,success,,20,200,off
2025-12-04T15:41:25.955715682Z,P1_6680fa,r_ce9a2783,T0_list,success,,24,200,off
2025-12-04T15:42:18.881959712Z,P1_6680fa,r_37c05fe7,T1_filter,success,,4,200,on
2025-12-04T15:42:19.398301371Z,P1_6680fa,r_ab682129,T1_filter,success,,7,200,on
2025-12-04T15:42:19.707410618Z,P1_6680fa,r_1f2e19b9,T1_filter,success,,7,200,on
2025-12-04T15:42:20.755807161Z,P1_6680fa,r_9e39fddf,T1_filter,success,,7,200,on
2025-12-04T15:42:21.888600462Z,P1_6680fa,r_09d35c36,T1_filter,success,,12,200,on
2025-12-04T15:42:22.507690627Z,P1_6680fa,r_64a685bf,T1_filter,success,,7,200,on
2025-12-04T15:42:24.655869425Z,P1_6680fa,r_0fe2a2e6,T1_filter,success,,10,200,on
2025-12-04T15:44:07.458617059Z,P1_6680fa,r_fcff6c44,T1_filter,success,,0,200,off
2025-12-04T15:44:07.477953892Z,P1_6680fa,r_b6eab294,T0_list,success,,17,200,off
```

| Task | Completed | Time Taken (m:s:ms) | Confidence | Reasoning                                                                                                                                                                                     | Notes                                                                                                    |
| ---- | --------- | ------------------- | ---------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| 1    | No        | 1:30:00             | 5/10       | "not quite sure that  the task is visible and there's no category for dates or deadlines"                                                                                                     | The tasks.csv file did not initially have a trailing newline, causing the task addition to silently fail |
| 2    | Yes       | 0:15:11             | 9/10       | "added quite easily and saves quite quickly"                                                                                                                                                  |                                                                                                          |
| 3    | Yes       | 0:15:21             | 8/10       | "i'm not sure where but it feels a little bit off and also it is not based on the position of complete, i think it would be better if it sorted everything and highlighted the filtered word" |                                                                                                          |
| 4    | Yes       | 0:40:64             | 10/10      | "because i tried control plus and it worked after i was unsure if it did"                                                                                                                     | decided to use keyboard shortcut not GUI                                                                 |

#### Participant 2
##### Details of Participant:
Keyboard with JS
##### Notes:

###### Debrief 
1. what was the hardest task to complete?
"none of them were particularly difficult, as they are simple and everything is laid out well"
2. what could be improved about the application?
"i would make the task notification more noticeable, as the font is too small and does not stand out as my eyes are not at top left"
3. was there anything that was a surprise or did not work as intended? 
"no"
4. was there any task you weren't sure if you has completed successfully?
"no"

##### Metrics:
```csv
2025-12-04T16:11:47.498226957Z,P2_22764c,r_0c93590f,T0_list,success,,101,200,off
2025-12-04T16:11:51.536421758Z,P2_22764c,r_26aa2ce4,T1_filter,success,,10,200,on
2025-12-04T16:15:18.820255637Z,P2_22764c,r_fd90368d,T3_add,success,,35,200,on
2025-12-04T16:16:18.414864688Z,P2_22764c,r_05c586d3,T1_filter,success,,1,200,off
2025-12-04T16:16:18.446356306Z,P2_22764c,r_8c06e390,T0_list,success,,29,200,off
2025-12-04T16:18:06.319169414Z,P2_22764c,r_95d74580,T0_list,success,,28,200,off
2025-12-04T16:18:23.568866752Z,P2_22764c,r_bfeaf888,T1_filter,success,,10,200,on
2025-12-04T16:18:24.118505064Z,P2_22764c,r_2b209ab9,T1_filter,success,,8,200,on
2025-12-04T16:18:24.616841580Z,P2_22764c,r_25e812d8,T1_filter,success,,7,200,on
2025-12-04T16:18:25.399263113Z,P2_22764c,r_19d43ff6,T1_filter,success,,9,200,on
2025-12-04T16:19:00.053334451Z,P2_22764c,r_d888b4b5,T1_filter,success,,16,200,on
2025-12-04T16:19:18.746064352Z,P2_22764c,r_261477b5,T1_filter,success,,1,200,off
2025-12-04T16:19:18.780422344Z,P2_22764c,r_bc930d31,T0_list,success,,32,200,off
```

| Task | Completed | Time Taken (m:s:ms) | Confidence | Reasoning                                                                        | Notes |
| ---- | --------- | ------------------- | ---------- | -------------------------------------------------------------------------------- | ----- |
| 1    | Yes       | 0:16:33             | 10/10      | "straightforward"                                                                |       |
| 2    | Yes       | 0:27:50             | 9/10       | "quite simple, not used to keyboard navigation, takes long to get back to start" |       |
| 3    | Yes       | 0:06:99             | 10/10      | "filter box is quite visible and you dont have to press apply to see results"    |       |
| 4    | Yes       | 0:20:96             | 10/10      | "scaling is easy, nothing special by using ctrl plus"                            |       |

### Metrics Breakdown (s)

| Task | Target Time | Mean Time | Range of Times | Target - Mean |
| ---- | ----------- | --------- | -------------- | ------------- |
| 1    | < 20        | 16.3      | N/A            | -3.7          |
| 2    | < 60        | 21.3      | 15.1-27.5      | -38.7         |
| 3    | < 20        | 11.1      | 6.99-15.21     | -8.9          |
| 4    | < 180       | 30.1      | 20.1-40.6      | -149.9        |

a keyboard is likely to be more
#### Reflection / Initial Thoughts

Mouse and keyboard users were able to all complete tasks in under the target time, and had similar results throughout the tasks. 
Although for [[#Task 4]], which was completed by all participants via the usage of a keyboard shortcut, was able to be completed significantly faster by the keyboard user likely due to their familiarity with shortcuts. 


## Findings
You will now formalise your thoughts, reflections and data gathered from your pilot study into some findings which should be single issues with the site which you have identified from your evidence.

| Finding                               | Source                              | Observation                                                                                                                                                                                      | WCAG           | Impact (1-5) | Inclusion (1-5) | Effort (1-5) | Priority (im + in - E) |
| ------------------------------------- | ----------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------- | ------------ | --------------- | ------------ | ---------------------- |
| Status messages too small             | P2 Notes                            | P2:"the font is too small and does not stand out as my eyes are not at top left"                                                                                                                 | 4.1.3 Level AA | 3            | 3               | 1            | 5                      |
| Filtered words aren't highlighted     | P1 Notes + P1 tasks csv<br>L9-16    | P1:"i'm not sure where but it feels a little bit off and also it is not based on the position of complete, i think it would be better if it sorted everything and highlighted the filtered word" | 4.1.3 Level AA | 1            | 2               | 5            | -2                     |
| Error in parsing tasks.csv not caught | P1 Notes + P1 tasks csv<br>L3-9<br> | P1:"not quite sure that the task is visible..."                                                                                                                                                  | 3.3.1 Level A  | 5            | 3               | 4            | 4                      |


### Fixes To Implement

In this section you will select and explain up to three fixes you will be making based on your findings from the table.
These should be high priority findings, particularly those with WCAG Level A issues.


#### Fix 1

Finding: Status Messages too small

Explanation: the status messages would display as regular text on the same background as the rest of the content, making it hard to identify when status messages appear

Original Code: N/A ( lack of code was issue )

Fix: 
link the existing custom css file (that contains styles for #status) to the `<head>` 

| Type  | Before                 | After                 |
| ----- | ---------------------- | --------------------- |
| info  | ![[status_before.png]] | ![[status_fixed.png]] |
| error | ![[error_before.png]]  | ![[error_fixed.png]]  |
Finding: Status Messages too small

Explanation: the status messages would display as regular text on the same background as the rest of the content, making it hard to identify when status messages appear

Original Code: N/A ( lack of code was the issue )

#### Fix 2:
Finding: Error in parsing tasks.csv not caught

Explanation:  if the tasks.csv had its trailing newline removed, then the following task would be not able to be parsed and rendered on the screen

Original Code: N/A ( lack of code was the issue )

Fix: 
when parsing the tasks.csv, check if the file ends with a '\n' byte and if it doesn't append one.

Final Code: 
```kotlin
--- a/src/main/kotlin/storage/TaskStore.kt
+++ b/src/main/kotlin/storage/TaskStore.kt
@@ -63,8 +63,33 @@ class TaskStore(
      * @return List of tasks (empty if no tasks stored)
      */
     fun getAll(): List<Task> {
+
         if (!csvFile.exists() || csvFile.length() == EMPTY_FILE_SIZE) return emptyList()
 
+
+        // ensure file ends with newline to avoid malformed task lines
+        try {
+            java.io.RandomAccessFile(csvFile, "rw").use { raf ->
+
+                // goto final byte and read
+                raf.seek(csvFile.length() - 1)
+                val lastByte = raf.read()
+
+                // check for trailing newline
+                if (lastByte.toChar() != '\n') {
+                    System.err.println("Warning: CSV missing trailing newline")
+
+                    // go past final byte and write \n
+                    raf.seek(csvFile.length())
+                    raf.write('\n'.code)
+                }
+            }
+
+        } catch (e: Exception) {
+            System.err.println("Warning: could not ensure trailing newline: ${e.message}")
+        }
+
+
         return FileReader(csvFile).use { reader ->
             CSVParser(reader, CSV_FORMAT).use { parser ->
                 parser.mapNotNull { record ->
```

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
Expert participant with keyboard and mouse with js

##### Notes:

###### Debrief 
1. was there anything that was a surprise or did not work as intended? 

2. was there any task you weren't sure if you has completed successfully?

3.  were you aware of the status messages sent throughout the pilot?

4. were they useful?
##### Metrics:
```metrics.csv
```

| Task | Completed | Time Taken (m:s:ms) | Confidence | Reasoning | Notes |
| ---- | --------- | ------------------- | ---------- | --------- | ----- |
| 1    |           |                     |            |           |       |
| 2    |           |                     |            |           |       |
| 3    |           |                     |            |           |       |
| 4    |           |                     |            |           |       |

#### Participant 2
##### Details of Participant:
Expert participant in keyboard only, with js

##### Notes:
###### Debrief 
1. was there anything that was a surprise or did not work as intended? 

2. was there any task you weren't sure if you has completed successfully?

3.  were you aware of the status messages sent throughout the pilot?

4. were they useful?

##### Metrics:
```metrics.csv
```

| Task | Completed | Time Taken (m:s:ms) | Confidence | Reasoning | Notes |
| ---- | --------- | ------------------- | ---------- | --------- | ----- |
| 1    |           |                     |            |           |       |
| 2    |           |                     |            |           |       |
| 3    |           |                     |            |           |       |
| 4    |           |                     |            |           |       |
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
