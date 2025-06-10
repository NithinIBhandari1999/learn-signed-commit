# Learn Signed Commit

# Signed commit from Windows 11

# Commands
gpg --list-secret-keys --keyid-format LONG
gpg --armor --export ABCDEFGH
git config --global --list
git config --global user.signingkey ABCDEFGH
git config --global commit.gpgsign true
git config --global tag.gpgsign true
where gpg
git config --global gpg.program gpg
git config --global user.email "Your email"
git config --global user.name "Your name"