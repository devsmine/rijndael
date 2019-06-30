# Welcome to rijndael!
AES encrypt/decrypt, **Android,** **iOS**, **PHP** compatible

# Install PHP (compatible with php7.x) 
Via Composer

> $ composer require devsmine/rijndael

## Usage

 ### McryptData
 	 
    $key="DjrF1un4YL1d7ElNmO7NYkIP2j38rB0a";  
	$mcrypt=new McryptData($key);
	echo $encryptData=$mcrypt->encrypt("Enter your text");
	echo "\n"; //New Line
	echo $mcrypt->decrypt($encryptData);
    

