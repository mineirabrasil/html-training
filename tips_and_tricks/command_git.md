register commit
TO DO ALONE  not when working with others on a project
1 - git status
2 - git add + path (of file I want to commit) OR git add .  (= to take everything from root)
3 - git commit -m "commit name" (= name the modifications done)
4 - git log (= see commit present)
5 - git push (=to push is on the github so it can be reviewed)

1 - git status
2 - git add + path  OR git add .
3 - git commit --amend (=modify + validate commit)
4 - git push
5- git push -f (=force the push since history has been modified)

git add -u = add/push ONLY updates done

WHEN WORKING WITH OTHERs ON PROJECT DO:
1 - git status
2 - git add + path OR git add .
3 - git commit -m "commit name"
4 - git pull --rebase origin main
4 - git log
5 - git push


git pull = récupère les modif faites mais pas l'odre des commits
git pull --rebase origin nom_branch_distante_a_cibler =  va récuper l'ensemble des commit dans l'ordre (historique)
git pull --rebase = raccourcis de "git pull --rebase origin nom_branch_ou_on_est" qui va récuper l'ensemble des commit dans l'ordre (historique)

ajouter une branche
git checkout -b 