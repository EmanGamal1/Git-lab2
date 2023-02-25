Git lab2

1- Tell me how to remove them locally and remotely.<br/>
    (Locally):
        `git branch -D dev` <br/>
        `git branch -D test` <br/><br/>
    (Remotely):
`git push origin --delete dev` <br/>
`git push origin --delete test` <br/><br/>

2- Tell me how to list tags. <br/>
    `git tag` <br/><br/>

3- Tell me how to delete tag locally and remotely.<br/>
    (locally):<br/>
        `git tag -d v1.7` <br/>
    (remotely):<br/>
`git push --delete origin v1.7`