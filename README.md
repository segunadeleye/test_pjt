EXERCISE 2

2. git init

3. git checkout -b staging

4. echo "This is the first commit" > test1

   git commit -am "This is the first commit"

5. git remote add origin 

   git push -u origin staging

7. git clone 

8. git checkout staging

10. git commit -am "This is the second commit"

    git push -u origin staging / git push

12. git checkout staging

14. git commit -am "This is the third commit"

15. git checkout master

16. git merge staging

17. git checkout -b testing

20. git push -u origin testing

21. git checkout master

24. git push -u origin master

25. git rebase -i master

27. git fetch
    
    git checkout --tracking origin/testing
    
28. git checkout master

29. git merge testing