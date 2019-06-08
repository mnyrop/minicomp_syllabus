# Wax System Setup<br>Step by Step Guide

## Windows 10 
### Install Ruby
- Download `Ruby Installer Ruby + Devkit 2.5.5-1 (x64)` from https://rubyinstaller.org/downloads/
- Double click on the `rubyinstaller-devkit-2.5.5-1-x64.exe` executable that gets downloaded to start the install process
- Accept the license
- Check “Use UTF-8 as default external encoding” and leave the rest checked
- When the install wizard (GUI) is done, it should open a special RubyInstaller2 command prompt window. Once inside, hit `ENTER`
- When the process if finished, open your Command Prompt/Terminal app and check your Ruby install with `ruby -v`. If successful, it should say `ruby 2.5.5 …`

### Install git
- The Ruby installer should have installed Git for you. You can check with `git --version`

### Install ImageMagick
- Download the `ImageMagick-7.0.8-48-Q16-x64-dll.exe` executable over http from https://imagemagick.org/script/download.php#windows and run it
- Accept the agreement
- Keep all the defaults checked but also check “Install legacy utilities (e.g. convert)”
- Finish
- Close and reopen your command prompt, and check ImageMagick with `convert -version` OR `magick wizard: wizard.jpg`

### Install GhostScript
- Install the `Ghostscript 9.27 for Windows (64 bit)` executable with GNU License from https://www.ghostscript.com/download/gsdnld.html
- Run the install wizard with defaults

## Mac 
### Install Homebrew
- Copy/paste install command from https://brew.sh/
- Hit `ENTER` to install command line tools from Xcode (if needed)

### Install Ruby
- Run `brew install ruby`
- Install/Update Git
- Run `brew install git`

### Install ImageMagick
- Run `brew install imagemagick`

### Install Ghostscript
- Run `brew install ghostscript`

## Ubuntu

### Install/Update apt-get
- Run `sudo apt-get update` and `sudo apt-get upgrade`

### Install/Update Ruby
- Install rvm (follow https://github.com/rvm/ubuntu_rvm)
- Reload terminal
- Run `rvm install 2.5`
- Run `rvm use 2.5`

### Install ImageMagick
- Run `sudo apt-get install imagemagick`

### Install Ghostscript
- Run `sudo apt-get install ghostscript`

## After (all OSes):

### Install bundler and jekyll
- If your Ruby install is correct, this should be as easy as `gem install bundler jekyll`

### Install Atom
- Download from atom.io 
- Run the downloader
- Restart command line application and test it with `atom .`

### Configure Git
- Configure Git to use your user name with `git config --global user.name "your-username"`
- Configure Git to use your email with `git config --global user.email "your@email.address"`
- Configure your Git to use Nano as its text editor with `git config --global core.editor "nano -w"`
- Check your Git configuration with `git config --list`
- Check possible config commands with `git config -h`



