# tts-internal-buy-starter-repo
A starter repo that every TTS internal buy can clone to get started.

## Instructions

For a project titled `Project X` and with the repository `tts-buy-project-x` already started, run the following start a fresh repo:

```
git clone https://github.com/18F/tts-internal-buy-starter-repo.git
mv tts-internal-buy-starter-repo tts-buy-project-x
cd project-x
rm -rf .git
git init
echo "# Project X" > README.md
```

This pulls down the repository from GitHub, renames the folder, restarts the `git` commit history (to disconnect from _this_ repo), and removes these instructions.

```
git add .
git commit -m "Initial commit"
git status
```

This commits the entire folder with the note "Initial commit" and provides you with confirmation that it registered.

```
git remote add origin https://github.com/18F/tts-buy-project-x.git
git push -u origin master
```

This pushes your folder into your project's repository.
# tts-buy-cloud-support-services
