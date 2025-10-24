Cloning repo using anaconda prompt

# 1. Open Anaconda Prompt
# 2. go to 3
# 3. Clone repository
git clone https://github.com/username/my-notebooks.git
cd my-notebooks

# 4. Create/activate conda environment (optional)
conda create -n myproject python=3.9
conda activate myproject

# 5. Install Jupyter
conda install jupyter

# 6. Launch Jupyter
jupyter notebook

# 7. After working on notebooks, save them
# 8. Back in Anaconda Prompt:
git add *.ipynb
git commit -m "Update notebooks"
git push origin main


1. anaconda navigator > anaconda prompt
2. # First, find where your file is
cd path/to/your/file
dir # Verify Project1.ipynb is there

# Launch Jupyter Notebook (auto opens) 
jupyter notebook
# Or open specific notebook directly
jupyter notebook Project1.ipynb
