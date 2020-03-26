//Install Homebrew

/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"

//Install Python

brew install python

//Install and upgrade pip setup tools

pip install --upgrade pip setuptools

python --version

//Install Java

brew tap AdoptOpenJDk/openjdk

brew cask install adoptopenjdk8

export JAVA_HOME=/Library/Java/JavaVirtualMachines/adoptopenjdk-8.jdk/Contents/Home

echo $JAVA_HOME

//Install Python

brew install cassandra

cassandra -f 127.0.0.1

cqlsh 127.0.0.1
