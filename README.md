# msse642


o	Types of version control systems. What type is Git?
 A version control system is a tool that aids developers tracking and handling changes to a project's codebase progressively. There are mainly two version control systems: Centralized Version Control Systems (CVCS) and Distributed Version Control Systems(DVCS). Git is a DVCS(GeeksforGeeks, n.d.). 
o	Snapshots
     A snapshot captures specific versions of application components and their associated deployment processes at a particular point in time. This facilitates consistent and repeatable deployments across various environments. Snapshots are typically created after successful deployments in testing environments and can be promoted through different stages of the delivery pipeline, ensuring that tested configurations are maintained throughout. This approach simplifies the management of complex deployments involving multiple teams and environments (IBM, n.d).
o	What is a repository? Remote vs. local.
             A code repository, or "repo," is a centralized digital storage system where developers store, manage, and collaborate on an application's source code and related files. It facilitates version control, allowing teams to track changes, coordinate simultaneous edits, and maintain a comprehensive history of the project's evolution. This centralized approach enables efficient collaboration among developers, regardless of their physical locations, ensuring consistency and integrity throughout the software development lifecycle (Amazon Web Services, n.d.).
o	What is commit?
              Commit is an action similar to saving a file that has been edited. A commit documents a change to one or more files in your branch. During this process, Git assigns a unique ID, named SHA (Secure Hash Algorithm), that identifies what type of change, when, and who created it (GitHub, n.d.). 
o	What is working directory?
A working directory is the folder on your computer where your commands are currently being executed. It's like your current location within the file system. When you create, open, or save files without specifying a full path, your computer uses this directory as the default location (Lenovo, n.d.).
o	What is the Staging Area
      The development staging environment is a simulated version of the live environment that developers use to test for bugs and refine the code. After ensuring the code is error-free, it is moved to deployment, where it becomes accessible to users in the real application (McGregor, 2024).





o	Find a good diagram that illustrates the architecture and the flow
 
    Source: https://www.geeksforgeeks.org/git-flow-vs-github-flow/

 
References
Amazon Web Services. (n.d.). What is AWS Code Commit? https://aws.amazon.com/what-is/repo/
GeeksforGeeks. (n.d.). Version Control Systems. https://www.geeksforgeeks.org/version-control-systems/
GitHub. (n.d.). Committing and reviewing changes to your project in GitHub Desktop. GitHub Docs. https://docs.github.com/en/desktop/making-changes-in-a-branch/committing-and-reviewing-changes-to-your-project-in-github-desktop
IBM. (n.d.). Snapshots. IBM Documentation. https://www.ibm.com/docs/en/devops-deploy/8.1.0?topic=deployment-snapshots
Lenovo. (n.d.). Understanding the working directory in computing. Lenovo US. https://www.lenovo.com/us/en/glossary/working-directory/
McGregor, M. (2024, August 5). Development staging explained. Built In. https://builtin.com/articles/development-staging
