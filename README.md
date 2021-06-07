# Cryptocurrency Wallet
## What is Cryptocurrency Wallet?
#### It is an application which allows the users to store and retrieve their digital assets as well as save private keys to be used to sign transactions for blockchain ledgers.

## Environment Setup
#### For Windows users, visit https://www.apachefriends.org/index.html and downroad XAMPP version 7. 
#### Run the following command for requrements.tx file
##### $ pip install -r requrements.tx file

## Installing hd-wallet-drive
### To open a terminal as administrator (for Windows users)
#### Input the following command directly into the system search bar and launch the program as Administrator from the resulting menu.
#### $ C:\Program Files\Git\bin\bash.exe 
![image](https://user-images.githubusercontent.com/76085861/120986258-0294b080-c742-11eb-86aa-7bb89394358d.png)

#### With your terminal open as indicated for your operating system, change the directly to your "wallet" folder and run the following 5 commands:
####  1. $ git clone https://github.com/dan-da/hd-wallet-derive
####  2. $ cd hd-wallet-derive
####  3. $ curl https://getcomposer.org/installer -o installer.php
####  4. $ php installer.php
####  5. $ php composer.phar install
##### After running the above codes, you should see a folder called hd-wallet-derive containing the PHP library in "wallet" folder.

## Verification 
#### Start terminal and navigate to hd-wallet-derive folder. 
#### Run the command below:
#### ./hd-wallet-derive.php -g --key=xprv9tyUQV64JT5qs3RSTJkXCWKMyUgoQp7F3hA1xzG6ZGu6u6Q9VMNjGr67Lctvy5P8oyaYAL9CAWrUE9i6GoNMKUga5biW6Hx4tws2six3b9c --numderive=3 --preset=bitcoincore --cols=path,address --path-change

#### If installation was successful, you should see output similar to what you see in the following image:
![image](https://user-images.githubusercontent.com/76085861/120982668-8e0c4280-c73e-11eb-9e9a-f4320c023a17.png)
