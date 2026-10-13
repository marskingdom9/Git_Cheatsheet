Codespace: repeatable development environment hosted in the cloud, defined by configuration files in repo used to simplify developer onboarding, hosted by GitHub as Docker Container

Create Codespace on main (Code <>) -> Use Custom Image & Rebuild Container (Cmd Palette) -> Add/Modify Features to Dev Container Configuration Files (Cmd Palette) -> Delete Codespace

.devcontainer/devcontainer.json ... create configuration here

Support - Cmd Palette -> Add Dev Container Config Files (Modify)

Extensions - Install/Right Click to add to devcontainer.json

Custom Scripts - create .devcontainer/file.sh -> make script executable with `chmod +x .devcontainer/file.sh` -> add code to file -> create command in devcontainer.json
  "fileCommand": ".devcontainer/file.sh"

```
{
  "name": "Basic Dev Environment",
  "image": "mcr.microsoft.com/devcontainers/base:debian"
}
```

```
rm .git/hooks/post-checkout
rm .git/hooks/post-commit
rm .git/hooks/post-merge
rm .git/hooks/pre-push
```

```
node --version
dotnet --version
python --version
gh --version

python src/hello.py
```

```
#!/bin/bash

sudo apt-get update
sudo apt-get install sl
echo "export PATH=\$PATH:/usr/games" >> ~/.bashrc
echo "export PATH=\$PATH:/usr/games" >> ~/.zshrc
```
