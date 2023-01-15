# Python Virtual Environment using VSCode

To create a python virtual environment with the required packages, follow this guide.

1. Open your VSCode and clone this git repo.
2. Open up VSCode Command Pallette (Ctrl+Shift+P by default) and look for 'Python: Create Environment'. After you created your virtual environment, a folder titled '.venv' should pop up in the main directory.
3. Now you can access your virtual environment terminal by using the command 'Python: Create Terminal. Your python terminal now should have a <span style="color:green">(.venv)</span> prefix.
4. Install all of the dependencies by using `pip -m install -r requirements.txt`
5. Now you should be able to run the codes in the newly created python virtual environment

## Virtual Environment not working on Jupyter Notebook

If your Jupyter Notebook still uses system kernel, you will need to change the kernel.
In VSCode, you can change your kernel by clicking the button saying `(python 3.x.x)` on the top right of the screen. You might need to install ipkernel. Choose the virtual environment and it should work now.
