Since I don't yet know how to easily import the theme with the rest of the repo on a new device, here is the command to download the theme as if it's a new Hugo site.
```
cd themes
git clone https://github.com/kishaningithub/hugo-creative-portfolio-theme.git
rm -rf hugo-creative-portfolio-theme/.git
mv -T hugo-creative-portfolio-theme portfolio
```
Actually, before importing the repo, I can just do
```
git clone --recurse-submodules https://github.com/profiili/portfolio-site
```
