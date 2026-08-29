# SETUP

## 1. install

### macos

```bash
# open terminal
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

brew install git
brew install gh
brew install --cask visual-studio-code
brew install pnpm
brew install node
```

### windows

```powershell
# open powershell
winget install --id Git.Git
winget install --id GitHub.cli
winget install --id Microsoft.VisualStudioCode
winget install --id pnpm.pnpm
winget install --id OpenJS.NodeJS
```

## 2. prepare

```bash
pnpm i

# if need
pnpm approve-builds

pnpm prisma generate
```

## 3. start

```bash
pnpm run dev
```
