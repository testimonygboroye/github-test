~/github-test $ git add README.md
~/github-test $ git commit -m "Update README"
[main 0417abb] Update README
 1 file changed, 1 insertion(+)
~/github-test $ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 301 bytes | 100.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/testimonygboroye/github-test.git
   9b580a5..0417abb  main -> main
~/github-test $ cd ~/github-test
~/github-test $ git pull
remote: Enumerating objects: 8, done.
remote: Counting objects: 100% (8/8), done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (6/6), 1.84 KiB | 62.00 KiB/s, done.
From https://github.com/testimonygboroye/github-test
   0417abb..57d8770  main       -> origin/main
Updating 0417abb..57d8770
Fast-forward
 README.md | 8 ++++----
 1 file changed, 4 insertions(+), 4 deletions(-)
~/github-test $ cat README.md
# My First Repository 
GitHub is fun!

