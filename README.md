create env
****
conda create -n winequality python=3.7.0 -y
****

activate env
****
conda activate winequality
****

created a requirements.txt file

install the requirements
****
pip install -r requirements.txt
****

download the data from 

https://drive.google.com/drive/folders/18zqQiCJVgF7uzXgfbIJ-04zgz1ItNfF5
****

git init

****

dvc init

****

dvc add data_given/winequality.csv

****
git add .

git commit -m "first commit"

****
updates for readme file

 git add . 

 git commit -m "update Readme.md"

 git remote add origin https://github.com/r-sabita/simple-dvc-demo.git

 git branch -M main

 git push origin main

****
