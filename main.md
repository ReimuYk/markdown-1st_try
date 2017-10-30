# Git Workflow 
> Git, as a system of code administration, unavoidably deals with multi person cooperation.
>
> It requests a standard workflow to make us cooperate more effectly.

![image](pic1.png)

### Feature-driven development
> Feature-driven development(FDD) means that requirement is the main point of development. Requirement leads to feature branch and hotfix branch. After development finished, these branchs merge to the main branch and then to be deleted.

### Git flow
> Git flow is the earlist and most widely spread workflow.
#### Features
> Its has two main features.
![image](pic2.png)
> First, each project has two long-term branchs.
> - Main branch(master)
> - Develop branch(develop)
>
> The "master" branch used to save the version of external release. Every time you can get a stable version from this branch. The "develop" branch used to daily development, being used to save the newest version of development.
>
> Second, each project has three short-term branchs.
> - feature branch
> - hotfix branch
> - release branch
>
> Once the development finished, these branchs would be merged to "develop" or "master" branch and be deleted.
#### Evaluation
> Advantages
>> Clear and controllable
> 1. Local repertory and offline commiting brings mutual influent development.
> 2. Less "pollution of repertory"
> 3. Users can comletely clone the version repertory.
> 4. Switch branchs easily and merge easily.
> 5. Distributed version library, without single point of failure, content integrity is good.

> Disadvantages
> 1. Two long-term branchs bring frequently "branch switch"
> 2. In most cases, two long-term branchs are similar so that users make ultra work to maintain the other branch.
