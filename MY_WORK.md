# 📝 MY_WORK: Student Information, Development Log, Reflection & Answers

> This is the **only file** your instructor reads to grade Parts 3 and 4 (documentation and video). Everything you write here must be **in your own words**.

---

## 🛑 STOP: Read This Before You Do Anything Else

> ### 1️⃣ Read the whole `README.md` first
> The `README.md` in this repository contains the full instructions: class descriptions, feature specifications, question prompts and the video script. **If you skip it, you will lose marks.**
>
> ### 2️⃣ Understand the full code before answering any question
> Open `SchedulerSimulation.java` and read it **from top to bottom**. You must be able to explain what `Process`, `run()`, `runToCompletion()`, `addProcessToQueue()`, `Thread.start()`, `Thread.join()` and `Thread.sleep()` do **before** you write a single answer in Parts B and C. Run the program at least once and watch the output.
>
> ### 3️⃣ Commit many times, not once
> A single commit, or all commits made in the last hour, costs you **-0.5 mark**. See the [Commit Rules](#-commit-rules-mandatory) below.

**How to use this file:**
1. Fill in your **Student Information** (below) right now.
2. Follow the steps in the **Work Roadmap** in order.
3. Update the **Development Log** *every time* you work on the assignment, not at the end.
4. Do not delete any section header. Replace the `[...]` placeholders with your own text.

---

## 👤 Student Information

> ⚠️ **WARNING:** Fill this in first. Your name and ID must match the student ID you set in `SchedulerSimulation.java` (line 150) and the one you say in your video.

| Field | Your Answer |
|-------|-------------|
| **Full Name** | [Write your full name here] |
| **Student ID** | [Write your student ID here] |
| **University Email** | [yourid]@std.psau.edu.sa |
| **GitHub Username** | [your-github-username] |
| **Repository Link** | [Paste your repository link here] |
 
---

## 🎥 Video Link

**Video Link**: [https://drive.google.com/drive/folders/179IqmQ8wYtEvb5A547xIuBuOJ1VGnB6i?usp=drive_link]

> ⚠️ **WARNING:** The video must be **publicly accessible** ("Anyone with the link can view") on **Google Drive**, **YouTube (Unlisted or Public)** or any other cloud file-sharing system. A private, restricted or broken link counts as a **missing video (-1 mark)**.
>
> 💡 **TIP:** Open the link in a **private/incognito window** before you submit. If it asks you to log in or request access, it is not public.
>
> 📌 **NOTE:** The link goes in **this file only** (`MY_WORK.md`), **not** in `README.md`. Name your video file `StudentID_Assignment1_Demo.mp4`. It must last **2 to 3 minutes**.

---

## 🗺️ Work Roadmap (follow in this order)

| Step | What to do | Where | Marks |
|:----:|------------|-------|:-----:|
| 0 | Read `README.md`, then read and run the full code | Your IDE | – |
| 1 | Fork, rename, keep the repo **PUBLIC**, set your student ID (line 150), **commit** | GitHub + code | Part 1 (1) |
| 2 | Feature 1: Process Priority, **commit** | Code | Part 2 (0.25) |
| 3 | Feature 2: Context Switch Counter, **commit** | Code | Part 2 (0.25) |
| 4 | Feature 3: Waiting Time Tracking, **commit** | Code | Part 2 (0.5) |
| 5 | Development Log (5+ entries, different dates) | This file, Part A | Part 3 (0.5) |
| 6 | Reflection (4 questions) | This file, Part B | Part 3 (0.5) |
| 7 | Technical Answers (4 questions) | This file, Part C | Part 3 (0.5) |
| 8 | Record the video, upload it, paste the link above | Video + this file | Part 4 (1.5) |
| 9 | Final check, then submit the repo link on Blackboard | Blackboard | – |

> 💡 **TIP:** Tick each step off as you go. Do not leave the log, the reflection or the video for the last day.

---

## 🔁 Commit Rules (MANDATORY)

> ### ⚠️ MANY COMMITS ARE REQUIRED. A single bulk commit is penalized (-0.5 mark).

**Minimum: 3 meaningful commits. Aim for 6 or more.**

| # | Commit | Example message |
|:-:|--------|-----------------|
| 1 | Student ID set | `Set my student ID: 441234567` |
| 2 | Feature 1: Priority | `Feature 1: Added priority field to Process class` |
| 3 | Feature 2: Context switches | `Feature 2: Implemented context switch counter` |
| 4 | Feature 3: Waiting time | `Feature 3: Added waiting time tracking and summary table` |
| 5 | Development log entries | `Docs: Added development log entries 1-3` |
| 6 | Reflection and answers | `Docs: Completed reflection and technical answers` |
| 7 | Video link | `Docs: Added demo video link` |

**Rules:**
- ✅ **One commit per feature.** Do not put all three features in one commit.
- ✅ **Commit after each work session**, and after each part of this file.
- ✅ **Spread your commits over different dates.** Not all in one day.
- ❌ **Do not make all commits in the last hour** before the deadline.
- ❌ **No vague messages** like `done`, `update` or `final version`.

> 💡 **TIP:** Your commit history is checked and you **show it in your video** (at least 3 commits visible). Your development log dates should match your commit dates.
>
> 💡 **TIP:** **Use VS Code** (see *Recommended Development Environment* in `README.md` for the full setup). Sign in to GitHub in VS Code, then commit from the Source Control panel (Ctrl+Shift+G) → stage → write a message → Commit → Sync/Push. You can edit and commit this file the same way. **Pushing** matters: commits that are not pushed to GitHub are invisible to the instructor.

---

# Part A: Development Log (0.5 mark)

> ⚠️ **WARNING:** Minimum **5 entries**, spread over **different dates**. Five entries written on the same day, or written all at once at the end, will lose marks and look like a copy. Entry dates should be **between the start of the assignment and the deadline (October 10, 2026)**.
>
> 💡 **TIP:** Write an entry at the **end of each work session**, while you still remember what happened. It takes 5 minutes.
>
> 💡 **TIP:** Be specific. "Worked on the code" is a weak entry. "Added a `static int contextSwitches` counter and incremented it before `currentThread.start()`" is a strong one.
>
> 📌 **NOTE:** Each entry needs: date and time, what you did, details, challenges, solution, and time spent. Real challenges are fine (and expected). Do not invent fake ones.

## Example Entry (do not copy it, write your own)

### Entry 1 - [September 22, 2026, 2:30 PM]
**What I did**: Forked the repository and set up my student ID

**Details**:
- Created GitHub account with university email
- Forked the starter repository and renamed it
- Changed student ID on line 150 to my actual ID (441234567)
- Compiled and ran the program successfully
- Committed and pushed: `Set my student ID: 441234567`

**Challenges**: Had to install JDK first because `javac` wasn't recognized

**Solution**: Downloaded JDK 17 and set the PATH variable

**Time spent**: 30 minutes

---

## Your Development Log
### Entry 1 - October 10, 2026 - 7:00 PM

**What I did**: Set up the GitHub repository.

**Details**: Forked the starter repository and prepared it for the assignment.

**Challenges**: Understanding the repository setup.

**Solution**: Followed the instructions in the README file.

**Time spent**: 30 minutes

---

### Entry 2 - October 10, 2026 - 7:30 PM

**What I did**: Added process priority.

**Details**: Added a random priority from 1 to 10 and displayed it when a process entered the ready queue.

**Challenges**: Keeping the queue order unchanged.

**Solution**: Kept the ready queue in FIFO order and displayed the priority only.

**Time spent**: 45 minutes

---

### Entry 3 - October 10, 2026 - 8:15 PM

**What I did**: Added the context switch counter.

**Details**: Created a static counter to count when a new process started running.

**Challenges**: Updating the counter correctly.

**Solution**: Increased the counter when a new process started running and checked the final count.

**Time spent**: 40 minutes

---

### Entry 4 - October 10, 2026 - 8:55 PM

**What I did**: Added waiting time tracking.

**Details**: Used System.currentTimeMillis() and added a final table showing process name, burst time, waiting time, and turnaround time.

**Challenges**: Calculating the waiting time correctly.

**Solution**: Checked the calculations and tested the program output.

**Time spent**: 1 hour

---

### Entry 5 - October 10, 2026 - 9:55 PM

**What I did**: Tested the program and completed the documentation.

**Details**: Reviewed the three features, checked the output, and worked on MY_WORK.md.

**Challenges**: Making sure the program and documentation met the requirements.

Solution: Reviewed the assignment checklist and checked the program again.

Time spent: 1 hour
---

### Entry 6 - [Optional - Date and Time]
**What I did**:

**Details**:

**Challenges**:

**Solution**:

**Time spent**:

---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: [X hours]

**Most challenging part**:

**Most interesting learning**:

**What I would do differently next time**:

---

# Part B: Reflection (0.5 mark)

> 🛑 **STOP:** Do **not** start this part until you have read the `README.md`, read the **entire** `SchedulerSimulation.java`, run it, and finished the three features.
>
> ⚠️ **WARNING:** Each answer must be **5 to 7 sentences**, in **your own words**. Copied or AI-generated answers without understanding get **0 marks for the whole assignment**. You may be asked to explain them in person.
>
> 💡 **TIP:** Mention concrete things you actually did: a method you wrote, an error you hit, a line of output you saw. Generic answers score low.
>
> 💡 **TIP:** Draft your answer in a few bullet points first, then turn them into sentences.
## Question 1: What did you learn about multithreading?

I learned that multithreading allows a program to run multiple threads. I learned how to create threads using Runnable and start them using Thread.start(). I also learned that Thread.join() makes one thread wait for another thread to finish. Thread.sleep() can be used to pause a thread for a short time. In this assignment, I learned how threads can simulate processes running in a CPU scheduling system. I was surprised that threads can run in different orders depending on how they are scheduled.

## Question 2: What was the most challenging part of this assignment?

The most challenging part of this assignment was understanding how the waiting time is calculated. It was difficult to know how long each process waited before it started running. I also needed to understand how the time values were connected to the scheduling process. A small mistake could make the final results incorrect. I had to review the code carefully to understand where the calculations should be added. This challenge helped me understand CPU scheduling better.

## Question 3: How did you overcome the challenges you faced?

I overcame the challenges by reading the README file carefully. I reviewed the existing code before making changes. I worked on each feature separately to make the code easier to understand. I also ran the program after making changes to check the output. When something was unclear, I reviewed the related code and instructions again. This approach helped me find mistakes and understand the assignment better.

## Question 4: How can you apply multithreading concepts in real-world applications?

Multithreading is useful in many real-world applications. For example, a web browser can load a page while allowing the user to interact with other features. A music player can play music while downloading or loading other content. Mobile applications can perform background tasks without freezing the screen. Games can use different threads for tasks such as processing and background operations. The CPU scheduling concepts in this assignment help explain how processes or tasks can take turns using CPU time. Understanding multithreading helps developers build applications that are more responsive and efficient.

## Optional: What would you like to learn more about?

I would like to learn more about thread synchronization and how threads share data safely.

## Optional: How confident do you feel about multithreading concepts now?

Beginner. I understand the basic concepts, but I need more practice writing and debugging multithreaded programs.

## Optional: Feedback on the assignment

The assignment was helpful because it allowed me to practice multithreading and understand CPU scheduling. Some parts were challenging, but testing the program helped me understand the concepts better.
---

# Part C: Technical Answers (0.5 mark)

> 🛑 **STOP:** You cannot answer these questions without understanding the code. Re-read `SchedulerSimulation.java` and **run it** first. Your answers must reference **your own code and your own output** (your student ID makes your output unique).
>
> ⚠️ **WARNING:** Each answer must be **3 to 5 sentences**, with specific examples from your code or output. Use correct terms: thread, process, time quantum, ready queue, context switch, burst time.
>
> 
Question 1: Thread vs Process

A process is an independent program with its own memory, while threads share memory within the same Java program. Processes usually need more resources to create and communicate, while threads are lighter and communicate more easily. In our assignment, the Process class represents a simulated process, but the actual work is performed by a Java thread. In the addProcessToQueue() method, the line new Thread(process) creates a real thread to run the simulated process.

Question 2: Ready Queue Behavior

In Round-Robin scheduling, if a process does not finish within its time quantum, it is added back to the ready queue to wait for another turn. For example, a process with a large burst time may need several time slices before it finishes. Re-queuing allows other processes to execute while the unfinished process waits for its next turn. This makes scheduling fair because no single process can use all the CPU time without giving other processes a chance.

Explanation of example:

When a process does not finish during its time quantum, it is added back to the ready queue. It continues executing in later turns until its remaining burst time reaches zero.

Question 3: Thread Lifecycle

1. New: P1 is in the New state when its thread is created using new Thread(process) in addProcessToQueue().
2. Runnable: P1 becomes Runnable when Thread.start() is called in the scheduler loop, allowing it to be scheduled for execution.
3. Running: P1 is Running when the JVM schedules its thread and it executes the run() method.
4. Waiting: P1 enters the Timed Waiting state when it calls Thread.sleep() to simulate processing time. The main thread enters the Waiting state when it calls Thread.join() to wait for P1 to finish.
5. Terminated: P1 becomes Terminated when its run() method finishes and its thread stops executing.

Question 4: Real-World Applications

Example 1: CPU Scheduling in Operating Systems

Description:

An operating system can use Round-Robin scheduling to share CPU time among runnable processes or threads. Each task receives a small time quantum before the scheduler gives another task a turn. The time quantum is similar to the time limit in our simulation, and a context switch occurs when the CPU changes from one task to another.

Why Round-Robin works well here:

Round-Robin provides fairness because each ready task gets a turn. It also improves responsiveness because one task cannot keep the CPU indefinitely while other tasks are waiting.

Example 2: Handling Multiple Client Requests

Description:

A server can use threads to handle multiple client requests, such as requests from users opening a website. A Round-Robin approach can give each ready task a limited amount of processing time before moving to another task. The time quantum represents the processing time allowed for each turn, while switching between tasks is similar to the scheduling changes in our simulation.

Why Round-Robin works well here:

It improves fairness by preventing one long-running task from monopolizing processing time. It can also improve responsiveness by allowing other requests to make progress while a long request is still being processed.

Summary

Key concepts I understood through these questions:

1. The difference between a process and a thread.
2. How Round-Robin scheduling uses a ready queue and a time quantum.
3. The main thread lifecycle states and how Java thread methods affect them.

Concepts I need to study more:

1. How Thread.sleep() and Thread.join() work.
2. How the scheduler decides when to re-queue a process.



# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [ ] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [ ] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [ ] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [ ] Student ID is set in `SchedulerSimulation.java` (line 150)
- [ ] Code compiles and runs with no errors
- [ ] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [ ] Each feature has clear comments

**Commits**
- [ ] **At least 3 meaningful commits, ideally 6 or more**
- [ ] **One commit per feature**
- [ ] Commits are spread over **different dates** (not all in the last hour)
- [ ] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [ ] Full name and student ID filled in at the top
- [ ] Development log has **5+ entries** on different dates
- [ ] Reflection: 4 questions, 5-7 sentences each
- [ ] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [ ] No `[...]` placeholders left
- [ ] No section headers deleted

**Video**
- [ ] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [ ] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [ ] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [ ] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.
