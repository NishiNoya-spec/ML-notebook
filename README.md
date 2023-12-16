# ML-notebook
ML-notebook

### HOW TO SETUP JUPYTER NOTEBOOK IN VS CODE (W/ VIRTUAL ENV & KERNELS)
Process:
__Step 1. Create project folder__

# syntax
mkdir <folder name>

# example
mkdir myproject

__Step 2. Create, activate & select your virtual environment__

# syntax
python3 -m venv <virtual environment name>

# example
# that would create a virtual environment named 'myenv'
python3 -m venv myenv

# syntax
source <virtual environment name>/bin/activate

# example
source myenv/bin/activate

__Step 3. Install ipykernel__

pip3 install ipykernel

__Step 4. Create new kernel__

# syntax
python3 -m ipykernel install --user --name=<projectname>


# example
# That would create a kernel named 'myproject'
python3 -m ipykernel install --user --name=myproject

__Step 5. Start jupyter__

jupyter notebook

URL: https://devinschumacher.com/how-to-setup-jupyter-notebook-virtual-environment-vs-code-kernels/
Video: https://www.youtube.com/watch?v=-j6y-5t37os&ab_channel=devinschumacher

Local path to kernels: C:\Users\danil\AppData\Roaming\jupyter\kernels

