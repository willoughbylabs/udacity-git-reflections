**Q1:** When would you want to use a remote repository rather than keeping all
your work local?  
**A1:** If you are away from your computer and do not have access to the local
files, you could access the remote repository and then update your local files
when you have access to them again.

**Q2:** Why might you want to always pull changes manually rather than having
Git automatically stay up-to-date with your remote repository?  
**A2:** It is likely the local repository will have more commits or changes
than reflected in the remote repository. If the local repository updated
to match the remote repository, it would likely revert new additions.  

**Q3:** Describe the differences between forks, clones, and branches. When
would you use one instead of another?  
**A3:**
- Fork: for cloning another remote repository that you
do not have permission to make changes to; allows
cloning to local repository to make changes while still
giving credit to original creator.
- Clone: for cloning a remote repository to your local machine.
- Branch: for creating a new space to make changes to an existing repository
within that repository.

**Q4:** What is the benefit of having a copy of the last known state of the remote stored locally?  
**A4:** Since the remote is likely a cloud save of work done locally, it is helpful to know if your local version and remote are up-to-date. Similarly, if changes were added to your remote, it is helpful to know if your local is out of date and whether you will need to consider pulling from the remote and assessing conflicts when pushing to it.

**Q5:** How would you collaborate without using Git or GitHub? What would be easier, and what would be harder?  
**A5:** Collaboration without Git or GitHub would require sending the exact version of the file to someone and working alongside them directly or if changes were made, sending the file to them and explaining the changes. Issues like typos could be quickly corrected if working on the file together in person but that would require additional coordination and all collaborators would have to be available at the same time. Using Git and GitHub allows the same sharing of information but it specifically highlights the changes and collaborators can be notified of and attend to the changes at a more efficient time.

**Q6:** When would you want to make changes in a separate branch rather than directly in master? What benefits does each approach have?  
**A6:** If the changes may not impact functionality and have already been approved (perhaps a typo or simple style change), it would likely be easiest to fix in master. However, if not approved and collaborating separately, or a new or experimental feature, it would be best to work separately of master. A pull request for the branch can be updated so any changes after pulling the most recent master can be worked into the separate branch and merged with master when appropriate. 
