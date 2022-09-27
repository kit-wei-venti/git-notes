<h2> lxc exec u2004 -- sudo -iu ubuntu bash -ilc "terminator&" </h2>

<img src="Images/bashrc.png">
<h2> container </h2>
<ul> 
  <li>can run multiple container on one machine!</li>
  <li> they contain packages of software and can run on any environment</li>
  <li> lightweight, so can run more containers compared to vms. require fewer resources deploy faster </li>
</ul>

<h2> rospack find </h2>
<p> can use it to find package </p>

<h2> what is echo for?</h2>
  <p> It shows the data published on a topic </p>
  
  <h2> wget </h2>
  <p> used this command to download files from internet (use this with the file url u wanna download) </p>
  
  <h2> echo </h2>
  <p>use to display text, strings or messages</p>
  
  <h2> touch </h2>
  <p> create empty file </p>
  
  <h2>cat</h2>
  <p> create single/multiple file, view it, also gives us output of files in terminal </p>
  
  <h2> sudo </h2>
  <p> very powerful command </p>

<h2> what is a package , and what does it contain? </h2>
  <div> 1)it must contain a <strong>.xml file </strong></div>roscore explain
  <div> 2)it must contain a CMakeLists.txt which uses catkin </strong></div>


<a href="https://ongkitwei.github.io/passenger-counter/"> click here </a>

<h2> difference between catkin_make and catkin_build </h2>
  <p> catkin build can be used from any directory in the workspace while catkin_make only works in the top level directory. </p>

<h2> CMake and CMalelists</h2>
<p> CMake is a build system tht uses script called CMakelists to generate build files for specific environment </p>
<p> CMakelist: CMakeLists. txt file contains a set of directives and instructions describing the project's source files and targets (executable, library, or both).</p>

<h2> GIT </h2>
<a href="https://www.youtube.com/watch?v=NcoBAfJ6l2Q&t=1619s">Link to GIT</a>
<br>
<img src="Images/git.png" height= 250px;>
<ul>
  <h3>What is git? </h3>
  <li>keep track of changes to code, synchronise work/code with different colleagues</li>
  <li>test changes to code without losing the original</li>
  <li>revert back to old version of code!</li>
  
  <h3> Git Clone:</h3>
  <li> take a repository from internet and download it onto your computer (nned the github repo link)</li>
  
  <h3> Git Commit:</h3>https://www.youtube.com/watch?v=NcoBAfJ6l2Q&t=1619s
  <li> save the current state of the files and folders inside the repository and take a snapshot, so that later you can refer back to them</li>
  <li>can use git commit -m "write the meesage u want to convey"</li>
  <img src="Images/Screenshot from 2022-09-25 12-02-43.png" height=300px;>
  <li> if u wanna combine git commit and git add, eg: wanna git add all the files, u can use <strong>git commit -am "message u wanna write here"</strong>
  
  <h3> Git Add:</h3>
  <li> it is use to add a file into a checklist such tht when the next time u wanna save it, git will save all these files you have added. it is kinda      like shortlisting the files you wanna save!</li>
  
   <h3> GIT status:</h3>
  <li> It tells u what is currently happening in ur github repo</li>
  <img src="Images/Screenshot from 2022-09-25 12-17-33.png" >
  <li> your branch is ahed of origin/main : means that ur version is more updated than the one on github. (origin/main is refering to github)</li>
  <img src="Images/Screenshot from 2022-09-25 12-56-58.png">
  
  
  <h3> GIT push:</h3>
  <li> take your changes you have made in repo and push it up to github  </li>
  <li> need to generate token if not get this error</li>
  <img src="Images/gitpusherror.png" >
  
  <h3> GIT pull:</h3>
  <li>opp of git push. EG: u think the codes on ur github is more outdated than the one on ur local    computer, then we use git pull.</li>
  <li> smths might have merge conflict then need choose in ur code what u wanna remove or keep </li>
  
  <h3> GIT Log:</h3>
  <li> keep track of changes/ commits you have made to your code (can see the message u type, who edited...) </li>
  <img style=" height: 400px;" src="Images/Screenshot from 2022-09-25 15-48-05.png">
  
  <h3> GIT reset:</h3>
  <li>  accidentally made a change you actually dw, use git reset to go back to previous commit, or can use it to reset everyth.</li>
  <li> can go back to specific commit (jus need the hash can be found by using git log) (git reset --hard commit) </li>
  <li> can also go back to the repo at github (origin/master) (git reset --hard origin/master)</li>
  
  <h2> GIT branching </h2>
  <li> git branching allow u to work on multiple things simultaneously without disrupting the master, can work on multiple rep at the same time </li>
  <li> if we dont use git branching we cant work on many repo at the same time, so if there is a bug somewhr behind, u cant work on other things</li>
  <li> master branch: default branch</li>
  <li> head branch: whr u are currently working on (can switch from one branch to another branch)</li>
  <li> feature/ other branch</li>

  <h3> GIT branch </h3>
  <li> tell u wat branch u are currently on (the star will tell you) and what branches exist.</li>
  
  <h3> GIT checkout </h3>
  <li> use git checkout to change the branch u wanna work on </li>
  
  <h3> GIT merge </h3>
  <li> merge diff branches (EG: u make changes to both brnaches in ur codes now u wanna combine both changes tgt)</li>
  
  
  <h3>GIT rebase</h3>
  <li> copy</li>
  <li> Rebasing is the process of combining or moving a sequence of commits on top of a new base commit. </li>
</ul>
