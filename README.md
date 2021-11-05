# Contribute

## Prepare:
1. Contribute uses python 2 and pip 2. Please check if they installed. If not, install.

2. Install dependency on Python Image Library (PIL):

```pip install pillow```

3. Clone this repository:

```git clone https://github.com/mraliscoder/contribution```

4. Go to directory:

```cd contribution```

5. Create repository on GitHub

6. Prepare git to work:

```git remote add github https://github.com/[Your github username]/[Your repository]```

7. If you didn't set git username and email, set them:

```git config --global user.name "User"```

```git config --global user.email "email@example.com"```

Use email that connected to your GitHub account.

## How to work
You can use images 52x7px size. If you don't have image,
you can generate it from text:

```python gen.py --text "Hello"```

Then start process:

```python gen.py Hello.bmp```

Hello.bmp is example, use your own path.

## After that 
Finally, push changes to GitHub:

```git push github```

Script can ask you for GitHub login and password. Use
your GitHub username and access token.