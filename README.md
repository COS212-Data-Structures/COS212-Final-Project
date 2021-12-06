# COS212-Final-Project
ver. 2.1.a

COS 212 – Data Structures Final Project

“Command Center”

For your final project you are asked to write a Command Center GUI with the supporting backend.
The Command Center GUI is a display for use in a(n imaginary) centralized center of operations.
There will be various displays with which a user can interact – both to read and to modify the contents
thereof.

1) There will be a Priority Task Queue which will display the top priority task that needs to be underway
along with its priority number. Tasks are single line text descriptions like “Homework” or “Begin Launch
Countdown”. Each has a priority associated with it, where the lower the number the higher the priority.
Priorities are integers and range from 1 to 100 but need not be sequential and may be duplicated.
The display will provide buttons to a) remove the displayed task, indicating its completion; b) add an
additional task, both text phrase and integer priority. (Hint: the Priority Queue should be implemented
with a minHeap.) After removal of the displayed task, the display should show the next highest priority
(i.e., lowest numbered) task. When adding a task, the new task should be added but won’t necessarily
be display – if it’s not (yet) the highest priority task.

2) Somewhere on the display there will be an ongoing rotation of messages. These messages will be
simple text messages of limited size (TBD). One message at a time will be displayed, but the display will
change every 3 seconds to the next message. The will be displayed in a fixed sequence, in a fixed order.
The display will provide buttons to a) add a message, immediately following the message currently
displayed; b) delete the currently displayed message.

3) There will be a Backlog display, a stack of task names representing tasks that are each set aside until
other tasks are completed. For example, consider the following tasks: Enter the office building, enter
office A, water the plants, turn off lights, enter office B, shutdown the desktop PC.
Now each office is not contained in the others; you must leave office A before proceeding to office B.
Therefore, the stack of tasks might show:
Water the plants
Enter office A
Enter the office building
Whereupon the user, using the + and – buttons for this display, might remove the top task and replace it
with “Turn off the lights”. Later the user might remove that top task and then remove the next one
(“Enter office A”) and then add the task “Enter office B”. The display will show up to 8 tasks – in a stack
– with new tasks added at the top, and deleted tasks removed from the top.

4) The fourth aspect of this GUI is an open-ended task for you to add something of your own choosing.
It can be a series of images or a randomly generated sudoku board or a tic-tack-toe game or a binary
tree display or something else entirely.
WARNING: as with any real-world project there may be modifications made to the specifications after
the project begins. Be flexible and ready to adapt to such changes.
ver. 2.1.a
Display
What should the display look like? Be creative and make use of the GUI to construct an interesting,
readable display. Here’s one idea but you may vary from it if you choose:
Now this display needs some labeling, etc. and isn’t to scale, but just to give you some ideas.
The purpose of this project is to both visualize and demonstrate the use of various data structures that
we have studied this semester, as well as give you some further experience in OOD/OOP and GUI
development. You can use the data structures that we’ve written this semester or use the Java library
versions of them.
Persistence - File I/O
Data values in the application should “persist” from one invocation of the application to the next.
On startup, the application should load values (if any) from an existing file or set of files.
On exit, the application should write the value in the data structures to a file or set of files.
You may choose to add a button to explicitly save the data values.
You may choose to add a button to explicitly (re)load data values.

Process
There will be several checkpoints along the way. There are project grade points (more than 10% of your
project grade) associated with these checkpoints. More details will be available on moodle, but here are
the checkpoints:
• Design Check-in
• Design Approval
• Coding Check-in #1
• Coding Check-in #2
• Final Project Submission
You are certainly allowed (and encouraged) to talk with the professor at times besides your required
check-ins.
