
```shell

# 1. Install brew
# http://brew.sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

# 2. Install git (源代码管理工具)
brew install git

# 3. Install gh (github， 源代码管理系统)
brew install gh


# 4. Install node.js
# https://nodejs.org/en/download
# Download and install nvm:
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.3/install.sh | bash
# in lieu of restarting the shell
\. "$HOME/.nvm/nvm.sh"
# Download and install Node.js:
nvm install 25
# Verify the Node.js version:
node -v # Should print "v25.2.1".
# Verify npm version:
npm -v # Should print "11.6.2".

```
