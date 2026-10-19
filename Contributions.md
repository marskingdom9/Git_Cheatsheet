Contributions

Fork Repo

Clone Repo ... SSH
  (git clone <url>)

Create Branch ... cd to project dir -> git switch -c add-mayank-singh

Make/Commit Changes ... make file changes -> git status -> git add file.md -> git commit -m "msg"

git remote -v -> git remote set-url origin git@github.com:marskingdom9/first-contributions.git

Push Changes ... git push -u origin add-mayank-singh -> Compare & PR on GitHub

---

Generate & Configure SSH key to account: ssh-keygen -t ed25519 -C "mayank_singh09@hotmail.com" -> Admin Powershell ... Get-Service -Name ssh-agent | Set-Service -StartupType Manual -> Start-Service ssh-agent
Non Admin Powershell ... ssh-add c:/Users/ME/.ssh/id_ed25519

Add SSH Key to account: cat ~/.ssh/id_ed25519.pub -> Profile Settings -> Access (SSH & GPG Keys) -> New SSH Key

Check for previous SSH Keys: Git Bash ... ls -al ~/.ssh

