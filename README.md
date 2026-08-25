# App Physics 155 Lab Repository
Computer Methods in Physics I
1st Semester, A.Y. 2026-2027

This repository hosts the python notebook exercises of NIP-UPD.

Please read thru `ap155_0prelims.ipynb` and familizarize with the workflow. 

To submit, you may use one of the following pipelines:

1. githubtocolab:
  - open the exercise in GitHub
  - change the URL from "https://github.com/..." to "https://githubtocolab.com/...)".
  - In the colab file, **save a copy in Drive** and move it to our [google drive folder](https://drive.google.com/drive/folders/1-1_0ij0YTPivspvIKJdjQHo_EqYexrMO?usp=drive_link)
  - solve the notebook
  - last editing time is submission time by default
  
2. using Git from playpen:
  - `git remote -v` # check if the output has origin (fetch & push) and upstream (fetch & push)
  - note: origin should be your fork & upstream should be this repo
  - if your origin is this repo, fix it with `git remote set-url origin git@github.com:STUDENT_USERNAME/ap155lab_ay26271.git` # change accordingly
  - `git remote add upstream git@github.com:jrgrefal/ap155lab_ay26271.git` add this repo as the upstream remote
  - `git fetch upstream` # fetch the latest changes
  - to bring in only 1 specific folder or notebook:
    - `git checkout upstream/main -- ap155_1IdiomPlot_surname.ipynb` # pull single file
    - `git checkout upstream/main -- figures` # pull entire folder
  - solve the notebook, download and submit in our [google drive folder](https://drive.google.com/drive/folders/1-1_0ij0YTPivspvIKJdjQHo_EqYexrMO?usp=drive_link)
  - last editing time is submission time by default
  - `git add .` # stage the new folder/notebook
  - `git commit -m` "Add updated notebook from upstream"
  - `git push origin main` # to push the changes into your own GitHub fork
  
  If you have any questions, please feel free to message us via Google Space chat.
