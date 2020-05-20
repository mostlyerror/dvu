01_issue_tracker.md

# Issue Tracker
This is a console-only project to practice Vanilla JS skills. After
completing the JSHero course, you should have all the skills necessary to
complete this project, although you might need to combine those skills in
ways you haven't seen before.

#### Using the javascript console, users should be able to:

* Add an Issue with name, description, severity (low, medium, high)
* Issues should default to "unresolved" status until marked otherwise
* Issues should be unassigned by default
* Issues should have an ID field that is unique across all issues.
* List "Open" (unresolved) Issues, sorted by severity
* "Close" an issue (mark as resolved)
* Update a specific Issue's name, description, and/or severity
* Assign an issue to somebody (this can just be a person's name as a string)

### Notes
It's up to you what data structures to use, what the functions are called,
and how they should be called, etc. Approach the design like you're building
a library for someone else to use.

**Issues do not need to persist between browser sessions!** If the browser is reload, it's ok that the data is wiped out; everything can live in memory.

### Hints
You'll probably want to be familiar with some array methods like `filter`, `sort`, `push`, `splice`

Here is one way to model an Issue with Javascript objects:
```
{
  id: 1,
  name: "Fix Bug in Database",
  description: "Reading from the accounts table is really slow.",
  severity: 'medium',
  assignedTo: 'Bill'
}
```