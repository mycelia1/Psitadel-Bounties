[Psitadel Bounties Nostr Client]

[A Nostr client for taking and posting bounties for the development of Psilocybin Citadel]

See 'todo.txt' for tasks that need attention.

Prerequisites

Node.js: It's recommended to use NVM (Node Version Manager) to install and manage multiple Node.js versions.

npm (Node Package Manager): This comes bundled with Node.js.

Setup

Installing Node.js using NVM:

1\. Install NVM:

curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash

OR

wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash

2\. Test to see if NVM is in your path

nvm --version

3\. If NVM isn't found in your path, try adding it using the below commands:

export NVM_DIR="$HOME/.nvm"

[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"

[ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"

4\. Install Node.js 14:

nvm install 14

5\. Use the installed version:

nvm use 14

1\. Cloning and Running the Project:

git clone [repository-url] && cd [repository-directory]

2\. Install Dependencies

Install Dependencies:

npm install

Note: If you encounter any 'peer dependency' warnings during the installation, you might need to manually install the required versions as suggested by the warnings.

3\. Start the Application

npm start

Troubleshooting

Ensure that your Node.js and npm versions are up to date or match the project's required versions.
