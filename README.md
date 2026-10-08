this is my first python project in devops

git diff --->  for main.py i did things and i commited them 
then i added some things without adding them  like i didn't do git add
and of course without commiting the changes
than i did git diff and i got this
$ git diff
diff --git a/main.py b/main.py
index 48f82e9..acfa3a1 100644
--- a/main.py
+++ b/main.py
@@ -1 +1,3 @@
 print("hello this is my project")
+print("this is a modification")
+

git diff --staged ---> i did git add . i got this
vops1$ git diff --staged
diff --git a/README.md b/README.md
index 6e75f04..d3268ac 100644
--- a/README.md
+++ b/README.md
@@ -1 +1,17 @@
 this is my first python project in devops
+
+git diff --->  for main.py i did things and i commited them 
+then i added some things without adding them  like i didn't do git add
+and of course without commiting the changes
+than i did git diff and i got this
+$ git diff
+diff --git a/main.py b/main.py
+index 48f82e9..acfa3a1 100644
+--- a/main.py
++++ b/main.py
+@@ -1 +1,3 @@
+ print("hello this is my project")
++print("this is a modification")
++
+
+
diff --git a/main.py b/main.py
index 48f82e9..acfa3a1 100644
--- a/main.py
+++ b/main.py
@@ -1 +1,3 @@
 print("hello this is my project")
+print("this is a modification")
+


la difference entre git diff et git diff --staged est que git diff nous donne la difference dans un fichier entre la version commited et la version qui n'est pas commited and we didn't even add it with git add et pour git diff--staged show us the difference between the commited changes and the changes that are in the staging erea like we add it with git add but we didn't do the commit yet
