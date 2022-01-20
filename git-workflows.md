# Git Workflows

- Centralized
- Feature branching
- Gitflow
- Forking

So now that we have a better understanding of how to use Git beyond the bare basics, what can this offer us within our daily workflow? We've seen that Git works best when it's a collaborative tool, with more than one developer contributing to a project. If you are going to work in teams, you need to have a plan on how you want to manage the project workflow. Git has several workflow concepts that are battle tested, chances are one of these will work for you.

## Centralized

![inline](https://github.com/philsinatra/IDM-T380/raw/master/instructor_materials/images/03-git/03-git-workflow-centralized.png)

In a _centralized_ workflow, all team members clone the same remote _origin_ repository, and push/pull directly to it. This is okay in some cases, where teams are very small and very vigilant with organization. There is a higher risk of merge conflicts in this workflow as teams get larger and team members are working on multiple features/bugs etc. at the same time.

## Forking

![inline](https://github.com/philsinatra/IDM-T380/raw/master/instructor_materials/images/03-git/03-git-workflow-forking.png)

In a _forking_ workflow, team members create a _fork_ of what is considered the official, origin repository. In this workflow, each team member maintains their own clone of the official repository. One team member serves as the _integration manager_. This person is considered a "gate keeper" of the main, origin repository. All merging and pull requests must go through the "gate keeper" owner. Let's walk through an example of this workflow.

![fit](https://github.com/philsinatra/IDM-T380/raw/master/instructor_materials/images/03-git/03-git-workflow-forking-example.png)

## Forking Workflow Example Plan

1. Create your `fork`
1. Clone your `fork`
1. Work in `feature` branch
1. `push` feature branch
1. Create `pull request`
1. `pull` _origin_ into _master_
