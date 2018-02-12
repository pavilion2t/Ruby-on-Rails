### 补充一点终端知识：   
tilde ~   
clear = command + k  
  ```   
   echo $PATH
/usr/local/mongodb/bin:/usr/local/bin:/usr/bin:/bin:/usr/sbin:/sbin:/usr/local/go/bin:/Users/judy/Library/Android/sdk/platform-tools:/Users/judy/Library/Android/sdk/tools:/Users/judy/Library/Android/sdk/platform-tools    
  ```      
  
```  
 gcc -v
Configured with: --prefix=/Applications/Xcode.app/Contents/Developer/usr --with-gxx-include-dir=/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX10.13.sdk/usr/include/c++/4.2.1
Apple LLVM version 9.0.0 (clang-900.0.37)
Target: x86_64-apple-darwin17.0.0
Thread model: posix
InstalledDir: /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin   
```     
```  
ruby -v
ruby 2.4.1p111 (2017-03-22 revision 58053) [x86_64-darwin16]       
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"    
brew doctor    
brew update     
```      

```   
 brew install rbenv
==> Installing dependencies for rbenv: ruby-build
==> Installing rbenv dependency: ruby-build
==> Downloading https://github.com/rbenv/ruby-build/archive/v20171226.tar.gz
==> Downloading from https://codeload.github.com/rbenv/ruby-build/tar.gz/v20171226
######################################################################## 100.0%
==> ./install.sh
🍺  /usr/local/Cellar/ruby-build/20171226: 373 files, 191.3KB, built in 7 seconds
==> Installing rbenv
==> Downloading https://homebrew.bintray.com/bottles/rbenv-1.1.1.high_sierra.bottle.tar.gz
######################################################################## 100.0%
==> Pouring rbenv-1.1.1.high_sierra.bottle.tar.gz
🍺  /usr/local/Cellar/rbenv/1.1.1: 36 files, 62.7KB     
```        

```   
cat .bash_profile

export PATH=${PATH}:~/Library/Android/sdk/platform-tools
export PATH=/usr/local/mongodb/bin:$PATH
export ANDROID_HOME=$HOME/Library/Android/sdk
export PATH=$PATH:$ANDROID_HOME/tools
export PATH=$PATH:$ANDROID_HOME/platform-tools
export ANDROID_HOME=/usr/local/opt/android-sdk    
```       

```     
rbenv install --list    
rbenv install 2.X.X    
Installed ruby-2.3.1 to /Users/judy/.rbenv/versions/2.3.1   
```     

```   
gem -v
2.6.12     
```     

```     
gem install rails
Successfully installed rails-5.1.4
Parsing documentation for rails-5.1.4
Done installing documentation for rails after 0 seconds
1 gem installed      
```     

```   
gem list    
...   
rails(5.1.4)    
```     

```    
mysql --version
mysql  Ver 14.14 Distrib 5.6.36, for osx10.12 (x86_64) using  EditLine wrapper    
```    



  


