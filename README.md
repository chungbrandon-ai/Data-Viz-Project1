Cloning repo using anaconda prompt

# 1. Open Anaconda Prompt
# 2. go to 3
# 3. Clone repository - copy and paste the following into your command prompt
git clone https://github.com/username/my-notebooks.git](https://github.com/chungbrandon-ai/Data-Viz-Project1.git
cd Data-Viz-Project1

#Repo is now cloned! now lets open the notebook
1. anaconda navigator > anaconda prompt
2. # First, find where your file is
cd Data-Viz-Project1
dir # Verify Project1.ipynb is there

# Launch Jupyter Notebook (auto opens) 
jupyter notebook
# Or open specific notebook directly
jupyter notebook Project1.ipynb

# 7. After working on notebooks, save them
# 8. Back in Anaconda Prompt:
git add *.ipynb
git commit -m "Update notebooks"
git push origin main

# Navigate to your repo
cd C:\Users\brand\Data-Viz-Project1

# Pull latest changes
git pull origin main

