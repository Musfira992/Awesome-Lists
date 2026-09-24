# Git initial setup

## 1. Install Git

**Windows**

- Download the installer from https://git-scm.com/downloads
- Run it with default options (it installs Git Bash, which gives you a Linux-like shell).

**macOS / Linux**

- macOS: `xcode-select --install` or install via Homebrew (`brew install git`)
- Linux: use your package manager, e.g. `sudo apt install git`

## 2. Configure Git (name and email)

```bash
git config --global user.name "Your Name"
git config --global user.email "your_email@example.com"
```

Check your settings:

```bash
git config --list
```

## 3. Create an SSH key

This allows GitHub to authenticate you without typing your password every time.

```bash
ssh-keygen -t ed25519 -C "your_email@example.com"
```

- Press Enter to accept the default file location (`~/.ssh/id_ed25519`).
- Choose a passphrase if you want extra security (or press Enter to skip).

Start the ssh-agent and add your key:

```bash
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_ed25519
```

Copy the public key:

```bash
cat ~/.ssh/id_ed25519.pub
```

(Copy the entire line starting with `ssh-ed25519`.)

## 4. Add SSH key to GitHub

- Go to GitHub → Settings → SSH and GPG keys.
- Click New SSH Key, paste the key, give it a name, save.

Test the connection:

```bash
ssh -T git@github.com
```

You should see something like: `Hi your-username! You've successfully authenticated...`

## 5. Create a local repository

Inside your project folder:

```bash
cd path/to/your/project
git init
```

This creates a `.git` folder; Git is now tracking this directory.

## Debug tip

If the remote URL needs updating to SSH:

```bash
git remote set-url origin git@github.com:username/repo-name.git
```
