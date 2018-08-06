# ROS_liuqizheng
我的ros笔记
fatal: destination path 'ROS_liuqizheng' already exists and is not an empty directory.
intel@ROS-K:~$ ls
ai_ws    catkin_ws  Desktop    Downloads         imgui.ini         install_VNC.sh  local  mxBot_ws  Public          ros_voice_system  Templates
Arduino  code       Documents  examples.desktop  install_mxBot.sh  intel_ws        Music  Pictures  ROS_liuqizheng  SLAM              Videos
intel@ROS-K:~$ cd ROS_liuqizheng/
intel@ROS-K:~/ROS_liuqizheng$ cd ~
intel@ROS-K:~$ git clone https://github.com/liuqizheng123/ROS_liuqizheng.git
fatal: destination path 'ROS_liuqizheng' already exists and is not an empty directory.
intel@ROS-K:~$ ls
ai_ws    catkin_ws  Desktop    Downloads         imgui.ini         install_VNC.sh  local  mxBot_ws  Public          ros_voice_system  Templates
Arduino  code       Documents  examples.desktop  install_mxBot.sh  intel_ws        Music  Pictures  ROS_liuqizheng  SLAM              Videos
intel@ROS-K:~$ cd ROS_liuqizheng/
intel@ROS-K:~/ROS_liuqizheng$ ls
README.md
intel@ROS-K:~/ROS_liuqizheng$ ls
README.md
intel@ROS-K:~/ROS_liuqizheng$ git status
On branch master
Your branch is up-to-date with 'origin/master'.
nothing to commit, working directory clean
intel@ROS-K:~/ROS_liuqizheng$ touch a
intel@ROS-K:~/ROS_liuqizheng$ git add .
intel@ROS-K:~/ROS_liuqizheng$ git status
On branch master
Your branch is up-to-date with 'origin/master'.
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	new file:   a

intel@ROS-K:~/ROS_liuqizheng$ git status
On branch master
Your branch is up-to-date with 'origin/master'.
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	new file:   a

intel@ROS-K:~/ROS_liuqizheng$ git commit -a -m"add readme.md"
[master ebfc2fd] add readme.md
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 a
intel@ROS-K:~/ROS_liuqizheng$ git status
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)
nothing to commit, working directory clean
intel@ROS-K:~/ROS_liuqizheng$ git push
warning: push.default is unset; its implicit value has changed in
Git 2.0 from 'matching' to 'simple'. To squelch this message
and maintain the traditional behavior, use:

  git config --global push.default matching

To squelch this message and adopt the new behavior now, use:

  git config --global push.default simple

When push.default is set to 'matching', git will push local branches
to the remote branches that already exist with the same name.

Since Git 2.0, Git defaults to the more conservative 'simple'
behavior, which only pushes the current branch to the corresponding
remote branch that 'git pull' uses to update the current branch.

See 'git help config' and search for 'push.default' for further information.
(the 'simple' mode was introduced in Git 1.7.11. Use the similar mode
'current' instead of 'simple' if you sometimes use older versions of Git)

Username for 'https://github.com': liuqizheng123               
Password for 'https://liuqizheng123@github.com': 
remote: Invalid username or password.
fatal: Authentication failed for 'https://github.com/liuqizheng123/ROS_liuqizheng.git/'
intel@ROS-K:~/ROS_liuqizheng$ git push
warning: push.default is unset; its implicit value has changed in
Git 2.0 from 'matching' to 'simple'. To squelch this message
and maintain the traditional behavior, use:

  git config --global push.default matching

To squelch this message and adopt the new behavior now, use:

  git config --global push.default simple

When push.default is set to 'matching', git will push local branches
to the remote branches that already exist with the same name.

Since Git 2.0, Git defaults to the more conservative 'simple'
behavior, which only pushes the current branch to the corresponding
remote branch that 'git pull' uses to update the current branch.

See 'git help config' and search for 'push.default' for further information.
(the 'simple' mode was introduced in Git 1.7.11. Use the similar mode
'current' instead of 'simple' if you sometimes use older versions of Git)

^[[AUsername for 'https://github.co            
Password for 'https://github.com': 
remote: Anonymous access to liuqizheng123/ROS_liuqizheng.git denied.
fatal: Authentication failed for 'https://github.com/liuqizheng123/ROS_liuqizheng.git/'
intel@ROS-K:~/ROS_liuqizheng$ 
intel@ROS-K:~/ROS_liuqizheng$ git config --global user.name"Maxwell"
intel@ROS-K:~/ROS_liuqizheng$ git config --global user.email 
sunmaxwell@outlook.com
intel@ROS-K:~/ROS_liuqizheng$ git config --global user.name "liuqizheng123"
intel@ROS-K:~/ROS_liuqizheng$ git config --global user.email "3524475361@qq.com"
intel@ROS-K:~/ROS_liuqizheng$ git status
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)
nothing to commit, working directory clean
intel@ROS-K:~/ROS_liuqizheng$ git push
warning: push.default is unset; its implicit value has changed in
Git 2.0 from 'matching' to 'simple'. To squelch this message
and maintain the traditional behavior, use:

  git config --global push.default matching

To squelch this message and adopt the new behavior now, use:

  git config --global push.default simple

When push.default is set to 'matching', git will push local branches
to the remote branches that already exist with the same name.

Since Git 2.0, Git defaults to the more conservative 'simple'
behavior, which only pushes the current branch to the corresponding
remote branch that 'git pull' uses to update the current branch.

See 'git help config' and search for 'push.default' for further information.
(the 'simple' mode was introduced in Git 1.7.11. Use the similar mode
'current' instead of 'simple' if you sometimes use older versions of Git)

Username for 'https://github.com': liuqizheng123
Password for 'https://liuqizheng123@github.com': 
Counting objects: 3, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 269 bytes | 0 bytes/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/liuqizheng123/ROS_liuqizheng.git
   9a6c592..ebfc2fd  master -> master
intel@ROS-K:~/ROS_liuqizheng$ 


