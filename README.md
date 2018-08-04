# WWorkspace

Portable develop environment for personal use.

## Usage:

### Add this to your repository:

```
cd /path/to/your/git/repo
git submodule add https://github.com/AugustusWillisWang/WWorkspace
git add -A
git push
```

### Init this environment:

```
cd /path/to/your/git/repo
git submodule init
git submodule update
```

### Clone a repository with this environment:

```
git clone <repository> --recursive 
```

### Update environment

```
git submodule update --remote
```