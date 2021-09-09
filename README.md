# Punctuation
Take a set of text and output a picture of the text's punctuation.

## Getting started

### 1. Start by forking the Repo or making a local clone:

*Forking the GitHub Repository*

By forking this GitHub repository you are making a copy of the original to view or make changes without affecting the original. You can do this by following these steps...

- Log into your GitHub account and find the [repository](https://github.com/adamjcalhoun/punctuation).
- Click 'Fork' (last button on the top right of the repository page).
- You will then have a copy of the repository in your own GitHub account. 

*Making a Local Clone*

- Log into your GitHub account and find the [repository](https://github.com/adamjcalhoun/punctuation).
- Click on the 'Code' button (next to 'Add file'). 
- To clone the repository using HTTPS, under clone with HTTPS, copy the link.
- Then open Git Bash.
- Change the current working directory to where you want the cloned directory to be made.
- In your IDE's terminal type 'git clone' followed by the URL you copied.
- Press Enter. 
- Your local clone will now be made.

### 2. Make sure Python is installed on the IDE you're using. If you're using VSCode, find instructions [here](https://code.visualstudio.com/docs/languages/python).
### 3. Install Pillow by using this code in the command-line:

```
pip install Pillow

```
You can find some troubleshooting advice on [StackOverflow](https://stackoverflow.com/questions/26505958/why-cant-python-import-image-from-pil) if you have any issues at this stage.

### 4. Start creating images by using this code in the command-line:

```
python punctuation.py FILENAME
```

You can use the ulysses.txt file included as a test to run the code. Then add any .txt file you like to the root directory and repeat process. An image file will be generated in the root directory based on the .txt file.
