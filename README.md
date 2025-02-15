# DSS5105 Exercise 1 - Checkerboard

This project generates a customizable checkerboard pattern using Python, NumPy, and Matplotlib. The colormap was adjusted in a dedicated Git branch and later merged into the main branch using Git best practices.

## Installation & Dependencies
Ensure the following are installed before running the script:
Python 3.x,NumPy,Matplotlib

Install dependencies with:
```sh
pip install numpy matplotlib
```

# Executing the Program
1. Clone the repository:
   ```sh
   git clone https://github.com/kiko-yan/DSS5105_exercise-1.git
   ```
2. Navigate to the project folder:
   ```sh
   cd DSS5105_exercise-1
   ```
3. Run the script:
   ```sh
   python3 checkerboard.py
   ```   
4. A checkerboard pattern will be displayed.

# Git Workflow
1. Initialize Git:
   ```sh
   git init
   ```
2. Commit the initial script:
   ```sh
   git add checkerboard.py
   
   git commit -m "Initial commit with checkerboard generator"
   ```
3. Connect to GitHub:
   ```sh
   git remote add origin https://github.com/kiko-yan/DSS5105_exercise-1.git
   
   git push -u origin main
   ```
# Colormap Modification (Bonus)
1. Create and switch to a new branch:
   ```sh
   git checkout -b change-colormap
   ```
2. Modify `checkerboard.py` and update the colormap:
  Change:
   ```python
   plt.imshow(checkerboard, cmap="gray", interpolation="nearest")
   To
   plt.imshow(checkerboard, cmap="plasma", interpolation="nearest")
   
3. Save changes and push to GitHub:
   ```sh
   git add checkerboard.py
   git commit -m "Updated colormap from gray to plasma"
   git push origin change-colormap
   ```
4. Open a Pull Request on GitHub and merge the changes into main.
