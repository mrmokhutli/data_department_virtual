git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/mrmokhutli/data_department_virtual.git
git push -u origin main


--------------------------------------------------------------------------------
git lfs install
git lfs track "*.csv"
git add .gitattributes
git add Data_set/Retail_Transactions_Dataset.csv
git commit -m "Track CSV using Git LFS"
git push -u origin main

--------------------------------------------------------------------------------
spark tutorial :https://www.youtube.com/watch?v=LpClcNrekQA