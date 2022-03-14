# aws-workspace-freqtrade
Installation instructions for [Freqtrade](https://github.com/freqtrade/freqtrade) and [MGM](https://github.com/Rikj000/MoniGoMani) on [AWS Workspaces](https://aws.amazon.com/workspaces/)

### Prepare AWS Workspace
- Launch AWS workspace for Linux. Pick Directory, user, OS, Computer, Run Type, and Launch. Installed AWS Workspaces client and test login
- Install [Docker](https://www.silverdreamracer.me/install-docker-on-amazon-linux-workspaces.html) (Get latest from https://github.com/docker/compose/releases)
- keep a copy of docker-compose in /usr/local/bin and /usr/libexec/docker/cli-plugins

### Install VSCode
- sudo rpm --import https://packages.microsoft.com/keys/microsoft.asc
- sudo sh -c 'echo -e "[code]\nname=Visual Studio Code\nbaseurl=https://packages.microsoft.com/yumrepos/vscode\nenabled=1\ngpgcheck=1\ngpgkey=https://packages.microsoft.com/keys/microsoft.asc" > /etc/yum.repos.d/vscode.repo'
- yum check-update
- 
### Install and Configure FreqTrade Docker (also Check out https://www.youtube.com/channel/UC-AOcefy1x7lTc17JiqaxqA)
-- Follow Docker Instructions: https://www.freqtrade.io/en/stable/docker_quickstart/
