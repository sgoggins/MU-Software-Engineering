# Assignment One
1. If you have not already, create an account on GitHub.
2. create a new github repository under your account, with your pawprint as the name.
    a) Create a fork of the repository https://www.github.com/chaoss/augur into your account
    b) Clone the project to your local machine.
    c) If you are a Windows computer, please see our operating system support statement in the
    Syllabus. Even the Ubuntu subsystems on the latest version of windows do not function like
    other Linux based operating systems and do not support software engineering using open
    source tools. We are unable to support Windows OS specific issues.
    MITPress NewMath.cls LATEX Book Style Size: 8x9 August 20, 2019 10:08am
    Exercises 7
    d) Take a Screen Shot of the application directory listing from your operating systems command
    line.
    e) Use git commands (see link in syllabus) to Switch to the dev branch.
    f) Take a Screen shot of the application directory listing in from your operating systems command
    line for the dev branch.
3. Setup a Development Environment
    a) 1. Update Python to 3.7:
    b) - ‘sudo apt-get install python3.7‘
    c) - ‘sudo update-alternatives –install /usr/bin/python3 python3 /usr/bin/python3.7 2‘
    d) - ‘sudo update-alternatives –config python3‘
    e) - Select the option for Python 3.7
    f) 2. Install Python’s Virtual Environment Tool: ‘pip3 install virtualenv‘
    g) 3. Change to your ”home directory” for the next step. For all the operating systems we are
    aware of, you accomplish this simply by typing ‘cd‘ and then pressing enter at the command
    line.
    h) 4. Create a Python 3 virtual environment for Augur: ‘virtualenv –python=python3 newaugur‘
    i) 5. Activate your virtual environment ‘source newaugur/bin/activate‘ (In the case of Ubuntu,
    you get the ‘source‘ command automatically put into your path using the ‘bash‘ shell. So, if
    you get an error, type ‘bash‘ and then hit the enter key and try again.)
    j) 6. Make sure you have NodeJS and NPM installed. ‘sudo dnf install nodejs‘ on Fedora or
    ‘sudo apt-get install nodejs‘ on Ubuntu. Or ‘brew install nodejs‘ on a Mac.
    k) Take a picture of your screen showing these pieces of software are installed. Basically, issue
    the commands at a terminal and screen shot those.
4. Commit all screen shots to the GitHub repository named after your pawprint, and make sure they
are pushed to GitHub under an ”assignment-one” folder.
5. submit a link to your repository on canvas under assignment one.