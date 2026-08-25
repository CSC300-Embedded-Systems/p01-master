# P01: Project 1

* Your first project must be completed in *pairs*.

## Learning Objectives

* Reflect on your day-to-day life and envision how embedded systems can enhance it.
* Design your first custom embedded solution.
* Refresh your git skills.

## How to Begin

1. Go to the [Classroom 50 for P01](https://classroom.github.com/a/tSw4qAlx) and follow the instructions.

**⚠️ NOTE:** We will be using git and Github regularly in this course. If you do not remember how to use these tools,
please visit the evening lab for a refresher. You will be expected to know how to use these tools, so do not assume you
can get by without them. Plus, they are excellent tools for your resume when you are applying to internships and jobs\!

---

## Your Mission

For your first project, we will focus on the personal:

*Create an embedded device that enhances your daily life.*

---

## The Requirements

Before you can even begin to think about a solution, you must first identify a problem.

1. Pick two consecutive weekdays (Monday through Friday), and each partner will journal _every minute_ of those two days
   from the time you wake up until you go to bed that night:
    1. A small notepad and pen is useful for this, so it’s always handy and quick to add each entry.
    2. Entries should be simple (e.g., Took shower; Brushed teeth; Did homework; etc), but try to include *everything*
       you do that day, not just the interesting stuff. At a minimum, have an entry at least every 30 minutes (an alarm
       on your phone would help remind you).
    3. Each entry of your journal should have three parts:
        1. A start time of the entry (e.g., 7:57 AM)
        2. The entry itself (e.g., Woke up to alarm going off for the third time)
        3. Your state of mind (e.g., feeling tired; Excited; Hungry; Busy)
    4. You are, of course, encouraged to leave out personal stuff (e.g., taking meds, etc) as both your partner and
       instructors will be seeing these entries.


2. After the two days, review your journal, and in particular highlight entries where your state of mind is
   negative-leaning (i.e., frustrated, annoyed, hungry, etc). Those are times when you can begin to think about ways to
   improve that moment in the future.
3. Upload the entries to your repository. I suggest adding them as images. Place them in the `logs` folder and name them
   intelligently.
3. Brainstorm ideas with your partner places in your day you could improve through the use of an embedded system. Some
   examples that are at an appropriate scale for this class:
    1. Toothbrush attachment to ensure you brush for 2+ minutes.
    2. Vibrating reminder to move/stand every 30 minutes if you’re sitting too long.

⚠️ RULE 1: Your embedded system cannot be a replication of something you already have. For example, you all have an
alarm clock (it's the only reason you're here on time). Do not pitch an alarm clock!

Once you have an idea, think about the design of that product:

1. Discuss the required hardware (e.g., sensors, output devices) to create your product in your design document.
2. Do research. You’ll likely need to look up how to connect the sensors and output devices. Most of this can be found
   online.
3. Discuss the pseudocode you’d need to create to solve the problem, ensuring it’s a) solvable and b)
   reasonable for the time you have. If it’s not, you may want to explore other ideas.

## Milestones

To ensure that you’re making continued progress for the next few weeks, there are four milestones where we’ll be
checking up on you:

1. **Milestone 1**: Initial research, planning, and design of embedded system
2. **Milestone 2**: Code setup and first prototype of embedded system
3. **Milestone 3**: Nearly finished second prototype of embedded system
4. **Milestone 4**: Final version of product and documentation

### Milestone 1 \- due Tuesday, September 1st @ 11:55 pm

For Milestone 1, you'll be building a design document in your repository. You’ll use the README.md file to do this,
formatted similar to the [example-README.md](example-README.md) (you need to copy/paste sections over as you complete
them). Be sure to look at the source code AND how it’s rendered on Github (as they are not the same). Markdown editors
are readily available out there, including ones for tools you’ve used in the past like PyCharm and Visual Studio Code.
This file includes lots of help text for how things should be done; read it thoroughly and carefully\! Github uses a
styling language called markdown (hence, the .md extension). A nice cheat sheet for how to format markdown is
included [here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet). You'll need to refer back to it often
to do certain formatting tricks, like adding images.

You'll also be creating a Github issue queue to track the specific work you intend to complete to reach your design
goals. The Github issue queue is a great way of tracking specific tasks that need completed in your project. Here is
an [example of a healthy issue queue](https://github.com/BCStudentSoftwareDevTeam/lsf/issues) used by the Student
Software team. Click into a few issues and you'll see that most of the descriptions are simple and to the point. Also,
you'll notice that some issues describe much larger contributions; they are labeled as `Epics`, which means that it will
likely need to be broken down into smaller issues to be solved completely. This is a smart way of tracking ideas (i.e.,
getting them out of your head and into notes), as well as ensuring that you and your partner aren't working on the same
item at the same time (i.e., duplicating effort).

**⚠️ NOTE**: Students often forget about the write-up by the end of the project, and try to do it at the very last
minute. The result is usually lots of grammatical errors, which do count against you, and key components missing. Also,
it makes it harder for me to help you make good decisions, like scoping the project appropriately. Instead, we encourage
you to take breaks from coding by updating the design document as you go. That will both help you take breaks from
coding (which are useful in preventing exhaustion from trying to solve those annoying bugs) as well as ensure your
document is in good shape by the end of the project. It also gives you clarity about your project by forcing you to try
to explain it, and may reveal the solution to the problem you’re trying to solve.

**In our grading of Milestone 1, we will review your design document and issue queue. We should have a good sense of the
intent of your project, as well as an outline of what work must be completed to accomplish that goal.**

### Milestone 2 \- September 8th @ 11:55 pm

For Milestone 2, we will be looking at your commit history in your repository, your issue queue for progress, and your
[README.md](README.md) for updates to your plan.

You should be making commits as you work regularly, and pushing that work before the deadline so those commits go to
Github. You should have your design notes in your README.md, including images describing the system, diagrams you’ve
created, and any other documentation you’ve created to describe the system.

Your commit history and issue queue should reflect progress you've made, notes you've taken as your project shifts, and
tasks being completed. I expect there will also be new issues, as you are breaking down your Epics into smaller pieces.

Be sure you’re taking advantage of git by this point in the project. For example, say you have to pivot because your
idea was too grandiose/not grandiose enough. You don’t want to lose the work you’ve done, because it’s still valuable.
Create a new branch\! If the new idea doesn’t pan out… no harm. Switch back to the other branch and keep coding away on
the original. Remember, git is your friend in helping you write code without losing previous versions, as long as you
remember to write meaningful commit messages, commit often, and take advantage of branching.

**Branches are cheap. Use them\!**

### Milestone 3 \- September 15th @ 11:55 pm

At this point, you should have made significant progress on your project. We will be looking again at your commit
history, issue queue, and README.md in your repository. Make sure you do another push before the deadline.

We expect to see much of your project completed by now (commit history), and a clear outline of what is left in the
issue queue. Your documentation should be coming together now, and reflect your final product. Your code should have
lots of comments and notes reminding you where you were working/where work was left unfinished.

### Milestone 4 \- September 22nd @ 8:00 AM

This milestone is your final product. You should have all of the coding complete, well commented, and well-structured
following good coding practices learned in previous courses. You should also have your README.md complete and it should
fully reflect your final product, with all sections correct, both in content and in grammar and spelling. *All
italicized help text should be removed at this point\!*

Your issue queue should reflect the current state of your project. In other words, all issues that you've completed
should be marked as complete, and issues you do not plan to complete should remain open. **Your issue queue should NOT
be empty, though\!** It should contain any work that you were unable to complete as future work, so the project can be
picked up in the future.

Each project will conclude with demonstrations. We will discuss the demo in more detail around Milestone 3\.

## Grading

* Milestone 1: 10 points
* Milestone 2: 10 points
* Milestone 3: 10 points
* Milestone 4: 10 points
* Physical prototype and code: 25 points
* Documentation (Design document, Google Doc, and in-code commenting): 20 points
* Demonstration: 15 points

## Submission Instructions

1. Review your repository to ensure everything you want is there, on a common merged branch between you and your
   partner.
2. **Commit** and **Push** your final changes to your repository.
3. In Github, issue a **Pull Request** from your branch to the main branch. Final grading will be for code and
   documentation will be done on this Pull Request, so check it before the deadline!
4. **Check your repository in Github to ensure everything was submitted and is correct.**