# 7zip macOS
#Step 1: Install Homebrew
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
After installation, ensure Homebrew is set up correctly by running
```
brew doctor
```

#Step 2: Install Wine
Run the command below to install Wine via Homebrew:

```
brew install --cask wine-stable
```

Install dependencies:
```
brew install freetype jpeg libpng libtiff libusb
```

Download and compile Wine from source:
```
brew install wine
```

#Step 3: Install 7zip
Open 7Zip.dmg and run terminal Install_to_App.command
