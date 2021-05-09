# Gibberish
Password generation tool to create complex passwords

<img align="top" width="100" src="https://github.com/ProIntegritate/Gibberish/blob/master/GUI.png" />

Gibberish generates passwords too complex to remember for normal human beings. It guarantees strong passwords unlike conventional password managers that just stores any password the user provides for a given site.

* Gibberish generates passwords based on a entropy and a master password (or several master passwords).
* Part of the entropy is known (i.e. people KNOW you have an gmail account)
* Part of the entropy are user settings, and a generated seed.
* Entropy is not secret and is not encrypted. (It CAN be though in future versions if required = exercise for the reader.)
* Entropy is not decisive for a generated password, is merely affects the outcome.
* Entropy is injected in the hashing process, but where it ends up depends on your password for the specific site..
* Not susceptible to offline brute force attacks - there are no hashes or known plaintext to validate against. Without data from a keylogger and the entropy file, you cannot recreate the user input.
* Gibberish helps user generate strong passwords (Up to 160 bits of entropy) that are hard to crack. 
* Gibberish is Open Source.
* Gibberish is free.

Gibberish can downgrade passwords for sites that require N characters or no special characters.
...but why would you downgrade a password? 160 bit passwords are secure. It is not always possible to use them:

* Some websites have as specific field size in a password table, and cannot accept more.
* Some websites / servers are coded to only accept 8 character passwords, or a 8-16 character password.
* Some websites / servers filters special characters, probably because they are afraid of SQL injections. This is a legitimate fear.

* Gibberish remembers strength settings for each site.
* Generates a new password at the click of a button (Generate new seed). Keep your old password and generate a new one - if you like.
* A spelling hint allows you to see spelling of the password you enter without revealing it to someone watching over your shoulder.
* Password is generated on the fly as you type. Just copy / paste to wherever you want it.
* Changing password is not automatically saved, you have to save this manually (Save-button) after you changed it on the specific site. This is to prevent saving uncommitted changes following a crash or failure to update.
* If you did not want to change your password, you can (re)load it by pressing the Load-button.
* You can enter one password, unique passwords, or group passwords for specific sites, i.e. one for social media sites, one for work sites, one for online games (etc).
* If one "master" password gets compromised, you do not have to change every site, unlike a traditional password manager.
