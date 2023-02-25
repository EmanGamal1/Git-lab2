Git lab2

1- Tell me how to remove them locally and remotely.
    (Locally):
        `git branch -D dev`
        `git branch -D test`
    (Remotely):
`git push origin --delete dev`
`git push origin --delete test`

2- Tell me how to list tags.
    `git tag`

3- Tell me how to delete tag locally and remotely.
    (locally):
        `git tag -d v1.7`

    (remotely):
`git push --delete origin v1.7`