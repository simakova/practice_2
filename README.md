# practice_2
Second Git practice from aplana 

Step 1
$ git clone https://github.com/simakova/practice_2.git
//Create file Block.txt
$ git add .
$ git commit -m "Create Block.txt"
$ git push

Step 2
$ git checkout -b feature
//Change file Block.txt
$ git commit -am 'Change Block.txt at 4 line (feature) '
$ git push -u origin feature

Step 3
$ git checkout master
//Change file Block.txt
$ git commit -am 'Change Block.txt at 5 line (master)'
$ git push

Step 4
$ git checkout feature
$ git merge master

Step 5
$ git checkout master
$ git merge feature
$ git push

