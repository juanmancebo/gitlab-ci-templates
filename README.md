## TODO

1. Give support to fully automated releases based on commit messages.
  - Branch name enforcing in all projects. Only fix/*,feature/* branches allowed.
  - Add a mechanism to ensure git commit messages are compliant with https://www.conventionalcommits.org/en/v1.0.0/#specification in order to achieve fully automated releases.
2. Automated changelog based on commit messages.
3. Review rules ensuring feature branching. Only run pipelines when there is a commit to a specific branch and/or when there is a merge request to master/main. 
4. Review and optimize cache rules.

