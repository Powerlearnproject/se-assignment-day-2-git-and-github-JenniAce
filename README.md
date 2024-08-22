# se-day-2-git-and-github
## Explain the fundamental concepts of version control and why GitHub is a popular tool for managing versions of code. How does version control help in maintaining project integrity? 
Version control is a system that lets you manage changes to files and projects which is considered by many to be the backbone of professional software development used daily by developers. (www.bloomtech.com)  GitHub has an open source distribution system that has adaptability, speed and stability required that is used for projects of any size either standups, enterprise and anything in between. (https://about.gitlab.com) VSC enables the developer to gain insight to every commit and access, review, collaborate, experiment, compare and undo changes to ensure code integrity and faster releases. (https://about.github.com)

## Describe the process of setting up a new repository on GitHub. What are the key steps involved, and what are some of the important decisions you need to make during this process? 
First you must have a GitHub account. At the upper right corner of the page, select and click New repository. Input a memorable name as your repository. You can choose to add a description of the repository or not. Then choose repository visibility. Next you select initialize this repository with a README. Finally, you click Create repository. 

## Discuss the importance of the README file in a GitHub repository. What should be included in a well-written README, and how does it contribute to effective collaboration? 
We need to identify the importance of communicating information regarding your project. It gives users detailed description of the project that has been worked on. This is referred to as documentation with guidelines on how to install and run the project. README can be identified as being significant in the role playing of enhancing the user’s engagement while contributing to the project’s success. (https://www.dhiwise.com). Furthermore, one can add README file to their repository to create awareness on the usefulness of the project, and how they can interface with the project. (https://docsgithub.com) 

## Compare and contrast the differences between a public repository and a private repository on GitHub. What are the advantages and disadvantages of each, particularly in the context of collaborative projects? A public repository is accessible to everyone on the internet while a private repository is accessible to explicit people whom you have granted access to. (https://docsgithub.com) 
Advantages of public repository (1) collaboration with others: Everyone can edit different portions at the same time without conflict (2) portability: the ability to log in and work conveniently from anywhere without worries. (3) easy download from any machine. One can also show variations of some things through fork. (https://academia.stackexchange.com) The disadvantage in providing public access is it entails loss of control, increased regulatory burdens and market volatility. (https://mksh.com) 
Advantage of private repository (1) ownership and control (2) visibility to a few (3) ability to store anything private including none software development files and experiencing no edits. The disadvantage is that others may have more resources than you and invariably out-code you thereby claiming provenance.  (https://stackoverflow.com/quest) 

## Detail the steps involved in making your first commit to a GitHub repository. What are commits, and how do they help in tracking changes and managing different versions of your project?
1)	Create an account. 2) sample project 3) clone the repository 4) create a branch and make your changes 5) commit and push your changes 6) merge changes 7) view changes in GitLab. (https://docs.gitlab.com) 
In Version Control, a commit is the operation of sending the latest changes of the source code to the repository making it part of the head revision while in Git, it is the core building block units of a Git project timeline. They capture the state of the project at every point in time. (https://en.m.Wikipedia.org  & https://www.atlassian.com) 
Commits help in tracking by ensuring that changes are gathered in a central repository thereby keeping the team informed. they are also used to manage different versions of the software, especially in large projects where tracking different versions and updates is done. (https://www.techcareer.net) 

## How does branching work in Git, and why is it an important feature for collaborative development on GitHub? Discuss the process of creating, using, and merging branches in a typical workflow. 
Branching determines how a team approaches code branching. According to David Mosyan, Git branching strategy is aimed at simplifying release management which was introduced in 2010 by Vincent Driessen. It has numerous, long lived branches and larger commits. (https://medium.com/@dmosyan/version-control-branching-startegies-e68e8d5ef1e0) . 
A typical workflow involves branching off from the main branch, developing the features and then merging back once complete. Each feature gets its own branch while ensuring that the main code remains stable. (https://www.linkedin.com) kindly see diagram below (https://www.varonis.com/blog/git-branching) 

     ![A typical workflow in GitHub](https://github.com/user-attachments/assets/a7fa9995-c841-47bc-92c9-9a959eeeeb44)

                                                                                 





	
                                                                


## Explore the role of pull requests in the GitHub workflow. How do they facilitate code review and collaboration, and what are the typical steps involved in creating and merging a pull request?
By creating a pull request, you are giving collaborators the opportunity to give feedbacks on your changes. Facilitating a code review entails 1) keep pull requests small and focused 2) carry the team along 3) set review times 4) always request code changes 5) responsibility should be on the author 6 )provide enough context to the reviewer include links if possible 7) endeavor to use pull/merge requests templates e.g links to Jira tickets 8) set static code analysis to save time and avoid nitpick comments 9) provide clear actionable feedback 10) follow through by addressing comments and making changes to the code , once approved, the author can merge the pull request and update tickets. (https://medium.com/domen.lanisnik/10-tips-for-better-code-reviews-6eb2fff2a85f) 
Steps to creating & merging a pull request:  1) pull the changes to the local machine 2) create a branch (version) 3) commit the changes 4a) push changes 4b) open a pull request (propose changes) 5) discuss and review code 6) rebase and test 7) merge branch to the master branch (https://medium.com/@urna.hybesis/pull-request-workflow-with-git-6-steps-guide-3858e30b5fa4) 

## Discuss the concept of "forking" a repository on GitHub. How does forking differ from cloning, and what are some scenarios where forking would be particularly useful? Forks are used to iterate on ideas or changes before being proposed back to the upstream repository such as in open source projects. (https://docs.github.com) . therefore, forking a repository in GitHub is sharing code and visibility settings with the original upstream repository. It helps the maintainer of the project to open up the repository for contributions from other developers without having to manually authorization settings for each individual contributor. (www.atlassian.com) 

## Examine the importance of issues and project boards on GitHub. How can they be used to track bugs, manage tasks, and improve project organization? Provide examples of how these tools can enhance collaborative efforts.
 Issues are importance as they help keep track of one’s work on GitHub. Once an issue is mentioned, the timeline reflects the cross-reference to enable one keep track and indicate work progress. Basically, it is opined that one can use GitHub issues to track ideas, feedback, tasks or bugs for work on GitHub. One can use them by creating labels for a repository to categorize issues, pull requests and discussions. GitHub can also provide default labels for every new repository. In this regard, one needs to build adaptable projects to track one’s work e.g. Kanban board (https://docs.github.com) 
