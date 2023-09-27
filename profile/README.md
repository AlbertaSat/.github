# Welcome to the AlbertaSat Github 👋

AlbertaSat is a team of around 80 undergraduate students. Our main goal is to support the training and development of highly qualified personnel in the space industry, by providing students with the opportunity to design, build and operate aerospace technology. The team is supported by alumni, faculty advisors and industry advisors. We are a diverse team with students from a variety of disciplines such as Engineering, Science, Business, Education and more. 

Software team members are responsible for all things software in AlbertaSat, particulary the OBC, and the ground station software. 

# Contributing guidelines:

### Workflow: 
We use a feature branch style git workflow where the main branch is protected and is only to contain a working version of the code. Branches are created as per their particular 'type' described below. More can be read about feature branching workflow here: https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow

### Branch naming conventions: 
The following branch naming convention must be followed. Any PR not in compliance will be denied. The naming convention going is as follows:

<name_of_author>/<branch_type>/<description_of_branch>

The following is a list of possible branch types:   
- feature
- testing
- bugfix
- hotfix
- documentation

### Branching etiquette
- Branches must implement/change only a single feature. Changes related to that feature across different layers of code is acceptable.
- If you discover a bug unrelated to the feature you are working on, switch back to master, make a branch to fix the bug, then make a PR to merge that Bugfix. Chances are you aren't the only one experiencing the bug. You may rebase your development branch off the Bugfix branch.
- Branches that do not describe what they are changing will not be accepted.

### Issue format/styling standards: 
Every issue must have:
- At least one associated label
- A priority
- A difficulty
- A 'type' 
- **A proper description**

Issues that have been started (moved from TODO) must have the following: 
- An assignee
- An associated branch (if the item is not in 'TODO'. Obvious exceptions if the task cannot be related to a repo)
- A start date
- A sprint # (when it should be completed) 

#### The following is a template for a proper description: 

TITLE: 

"Type here": Summary of what is being done 

BODY:

A more detailed description of the issue here.

A list of acceptance criteria (What is needed for the issue to be considered complete and ready for PR): 

### Commit standards:
- Use imperative mode in subject line. Think: If applied, this commit will ______ )
- Squash together commits that dont 'flow' or make sense, using an interactive rebase. 

### Code styling
- All code files in this organization - relating to the ExAlta3 mission and onward - must follow a particular coding format and style. An automatic workflow action will test your code against theses standards automatically upon any request to merge with main.
- For Python: It is suggested to install a pylint linter extension in your IDE, to write code that follows these standards as you go.
- For C/C++: It is suggested to intsall a clang linter extension in your IDE, to write code that follows these standards as you go. 

### Copyright
- Ensure that every source file written has associated 'author' and 'copyright' metadata included in the file (for now it is found in the bottom, two lines after all code).
- Because these items will exist in every source file, style checkers like pylint must be told explicitly told to ignore them otherwise your code will fail style tests


👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
- TODO 

