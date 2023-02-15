<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Project Title

AI Notes

## Summary

Automatic speech-to-text-to-meeting notes addon for recurring online meetings. Used for example with platforms like Microsoft Teams or Zoom. Records and converts discussions to text, and filters and sorts it to resemble meaningfull meeting notes that can be used as recurring log book.

## Background and problem

The progress of a large scale R&D (consisting of HW and SW; frontend, backend and algorithms) project and concrete task are difficult to monitor when things don't run smoothly - and they rarely do. Agile SW development tackles this problem by dividing work (progress) into sprints and sprints into task which are then distributed to SW team. Work is transparent and allows relatively quick moves (between sprints) and everyone knows what everyone else is doing. However, this approach doesn't work for HW development since it's much slower and has far too many variables. Agile planning and scheduling is too time consuming since the scenery changes often in between single task.

Meet good old meeting notes.

Meeting notes (for example a Word document) used to be the thing in past for keeping score about the project status and responsibilities. However, it requires a typist and is troublesome in the heat of a good conversation. Also meeting notes bury in hard drives or cloud drives if they are not up-to-date, concise and visual, and bluntly put perfect - which they never were. So the overall concensus is that they are outdated and rarely worth the trouble.

Meet AI generated meeting notes.

A well trained model could keep score about the project task statuses and responsibilities and let everyone else focus on the actual design. Model would generate a visual one pager of every meeting for the next meetings. Ideally it would operate as an AI secretary. In time, these one pagers form a log book that can be browsed for whatever information and reasoning behind decisions.

## How is it used?

Open ur favorite online meeting platform and press record meeting notes. Meeting notes are attached to the meeting and can be viewed by participants. If the meeting is recurring the meeting notes will pile up and form a diary or log book.

!Note! A lot of information discussed in internal meetings is sensitive which should be taken into an account.

## Data sources and AI methods

Data is collected as a recording during the meeting. AI model should be able to transcript speech and pick up the most important parts in relation to what is being said and what has been said before.

## Challenges

  * The recording is not good enough quality
  * AI is unable to form a concise summary of what (and how) has been said
  * How to implement this sort of an addon for well established online meeting platforms
  * How to visualise things in a meaningful way - should AI be able to see what is ona screen aswell?

## What next?

Research the state of current speech-to-text algorithms and existing solutions. Figure out how to build an app and get it listed. Get help for SW and AI algorithm development.


## Acknowledgments

* sources of inspiration include day to day work building complex devices in a busy R&D environment
