Application/Driver Class
      Bottom pane will be TabPane with different tabs for adding to the Backlog Tasks, the Priority Task Queue, and headlines (maybe)
      Probably need to make it taller
      Another option could be dividing it vertically into three different boxes, each with add/delete buttons and text fields for different DS. 
    Save class (part of the controller unless too big)
    Tasks Class (string, int)
    Priority Tasks
      taskCompleted method, when called deletes task from minHeap
      Mark as done button calls the complete method for any checked tasks. (Just delete the top task)
      addTask method along with pane to add it. (probably a pane)
      Pop up with text field, integer
    Backlog Tasks
      Stack
      Push, pop, peek, clear methods
      Add Backlog Task method, Delete Backlog Task method
    Headline Display
      Doubly Linked List
      Display/holder, current, prev nodes pointing to whichever node is being displayed.
      AddNode (AddHeadline)
    Open-ended task (TBD). (Asteroids game)
