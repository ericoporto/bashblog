How to fork your own repository on Github

Recently I had to fork my own repository on Github and looked through the web.
I ended up taking the solution from a comment in a website that suggested a much complex approach.

1. create a new repository in Github, don't add a readme or anything.

2. clone it on your computer

3. add the original repository (the one you want to fork) as upstream source.

    `git remote add upstream [url]`

4. fetch and merge upstream.

    `git fetch upstream & git merge upstream/master`
    
    
Thanks to Mark Marijnissen.

Tags: github

