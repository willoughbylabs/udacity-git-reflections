**Q1:** What happens when you initialize a repository? Why do you need to do
it?  
**A1:** initializing a repository allows git to start tracking changes. It is
needed otherwise changes won't be tracked and you can't make commits.

**Q2:** How is the staging area different from the working directory and the
repository? What value do you think it offers?  
**A2:** The staging area is different from the working directory in that it
only has files that you'd like to commit. It is possible there are other files
in the working directory but they do not need to be a part of the commit.

**Q3:** How can you use the staging area to make sure you have one commit per
logical change?  
**A3:** You can use the staging area to review the differences between the last
commit. If the amount of changes seem overwhelming, underwhelming,
or non-intuitive, the changes in the staging area might not be logical enough
for a commit.

**Q4:** What are some situations when branches would be helpful in keeping your
history organized? How would branches help?  
**A4:** Branches are helpful to trying out new features or making additions
while keeping the original code in tact. The original code can be updated
while working on the side features which can then be merged into whatever
updates were added to the original code. It helps keep code organized
without having to modify parts of the code you'd like to remain constant.

**Q5:** How do the diagrams help you visualize the branch structure?  
**A5:** The diagrams help by visualizing how the tree works and what is
included in a branch, and how checking out a commit separates any changes
from the branch unless they are saved to a new branch.

**Q6:** What is the result of merging two branches together? Why do we
represent it in the diagram the way we do?  
**A6:** Merge will bring changes from one branch into another and create a new
commit with those changes added in.

**Q7:** What are the pros and cons of Git’s automatic merging vs. always
doing merges manually?  
**A7:** Automatic merging is useful for quickly merging changes without having
to go through the code and finding all changes yourself. The warning if
Git finds conflicts lets you see at a glance what changes were made and
how they might conflict for you to assess and then do the merge manually.
Nevertheless, Git merging still makes the process easier by pointing out
the specific changes in each branch.
