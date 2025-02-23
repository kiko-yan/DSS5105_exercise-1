# DSS5105 Exercise 1 - Checkerboard

## Description 
This project generates a customizable checkerboard pattern using Python, NumPy, and Matplotlib. The colormap was adjusted in a dedicated Git branch and later merged into the main branch using Git best practices.

## Installation 
Ensure you have **Python 3.x** installed. Then, install the required dependencies:
```sh
pip install numpy matplotlib
```

# Running the project
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


# Colormap Modification (Bonus)
A new branch change-colormap was created to modify the color scheme of the checkerboard.
To switch the colormap from `gray` to `plasma`, modify the following line in `checkerboard.py`:
```sh
plt.imshow(checkerboard, cmap="plasma", interpolation="nearest")
```
Changes were committed and merged into `main` via a Pull Request.

# Git Workflow
This project followed Git best practices, including branching, committing, and merging via Pull Requests.
The repository follows best Git practices:
- Changes were committed in a structured manner.
- A new branch was created for colormap modification and merged via a Pull Request.
- The final version is available on the main branch.
