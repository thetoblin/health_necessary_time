# Workflow for updating slipbox-analyses and estimates and git-repositories
#way-of-work #workflow #git #github

Given the workflow of having data and code in slipbox which are copied/linked to a git repository, here's a list of steps to follow when doing so:
1. Make desired changes in code
2. Reflect changes in slipbox
	1. If notes shall be copied to github, add appropriate tags (#github-health-necessary-time)
3. Add, commit, and push changes in git in submodules (both data and health_necessary_time are submodules)
4. If notes have been changed, copy them to appropriate git repository
5. Update to latest versions of submodules in git repository
6. Add, commit, and push changes in git repository based on changes in submodules and added notes