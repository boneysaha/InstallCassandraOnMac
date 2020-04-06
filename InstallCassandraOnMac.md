//Install Homebrew

/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"

//Install Python

brew install python

//Install and upgrade pip setup tools

pip install --upgrade pip setuptools

python --version

//Install Java

brew tap AdoptOpenJDk/openjdk

brew cask install adoptopenjdk/openjdk/adoptopenjdk8

export JAVA_HOME=/Library/Java/JavaVirtualMachines/adoptopenjdk-8.jdk/Contents/Home

echo $JAVA_HOME

//Install Python

brew install cassandra

cd /usr/local/cassandra/

cassandra -f

cqlsh 127.0.0.1
