Create a virtual environment at the top level of your project directory:
    uv venv
Activate the virtual environment:
    source .venv/bin/activate
Add the pygame library as a project dependency:
    uv add pygame==2.6.1
Make sure pygame is installed:
    uv run -m pygame
run the game
    uv run main.py
