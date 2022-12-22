# actions

## This is an action repository & it will be used by other github repositories

1. in this example repository actions_tutorial__react_project_6 will use it from it's deploy.yml file

## Create a tag from a specific commit
1. git tag -a <Name of tag> <commit number> -m <tag message or description>
   for example: git tag -a v1 65762f86e2933d28b025184c2f35376ff3b6ee77  -m "My action release"
2. git push --tags
   we use this command cause we want to push the tag we created locally to the repository