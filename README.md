# Version_Control_GitLab

Introduction

This version control project provided a practical, hands-on introduction to using Git and GitLab to manage changes in a collaborative software development environment. Through this process, I learned not only how to clone repositories and track changes, but also how to manage branches, resolve conflicts, create meaningful commits, and maintain a professional project history.


Step A: Cloning the Repository
The project began with cloning the remote GitLab repository to my local machine using Git Bash. I navigated to the appropriate folder and used the git clone command with the repository URL. This ensured I had a complete copy of the remote repo to work with locally.


Step B: Creating and Pushing Changes
I modified three HTML files; about.html, services.html, and team.html on a working branch. Each file was edited with relevant, realistic changes:

about.html: Added a new section outlining the company’s core values.

services.html: Introduced a new service block for "Cloud Integration."

team.html: Added a fictional team member named “Yara.”

Each change was committed separately with clear, descriptive commit messages. After committing all changes, I pushed the working branch to GitLab and took a screenshot of the successful push.


Step C: Branching and Testing
To demonstrate proper branch management, I created a new branch named Test from the command line. On the Test branch, I edited the README.md file to add my student ID and committed the change. After pushing the Test branch to GitLab, I confirmed its presence by capturing a screenshot of the repository graph.


Step D: Merge Conflict Simulation
To simulate a real-world conflict scenario, I made a conflicting change in README.md on the working branch by adding the Git version number. I then attempted to merge the Test branch into working, which triggered a merge conflict. Git notified me of the conflict in the terminal, and I resolved it by manually editing README.md to keep both the Git version and student ID. I then staged the resolved file, committed the fix, and pushed the changes. A screenshot of the GitLab graph confirmed the successful merge.


Step E: Tagging the Repository
To mark a specific state in the repository, I created a version tag v1.0.0 on the working branch using the git tag command. I then pushed the tag to GitLab. This practice is critical in real-world projects for release management, rollback points, and historical tracking.


Step F: Retrospective Directory and Logs
Finally, I created a retrospective directory to store project documentation:

log.txt was generated using git log > log.txt to record the commit history.

summary.txt described how I resolved the merge conflict and documented the three key file changes.


I compiled all screenshots and comments from steps A through F into a single PDF and included it in the directory.


After confirming all files were in place, I committed the directory and pushed it to GitLab as my final step.


Conclusion
Through this project, I gained an understanding of Git workflows, from creating and managing branches to resolving merge conflicts and maintaining a clean commit history. Each step helped reinforce the importance of proper version control practices in software development. This experience has significantly improved my confidence in using Git, and I now understand how to collaborate more effectively in real-world team environments using tools like GitLab.
