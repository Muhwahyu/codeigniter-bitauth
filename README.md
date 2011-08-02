#BitAuth

* [Website](http://www.dmontgomery.net/bitauth) - http://www.dmontgomery.net/bitauth
* [User Guide](http://www.dmontgomery.net/bitauth/user_guide) - http://www.dmontgomery.net/bitauth/user_guide
* [Github](https://github.com/danmontgomery/codeigniter-bitauth) - https://github.com/danmontgomery/codeigniter-bitauth
* [Issues](https://github.com/danmontgomery/codeigniter-bitauth/issues) - https://github.com/danmontgomery/codeigniter-bitauth/issues

##Requirements
* PHP 5.1.6+, 5.3+ recommended
* CodeIgniter 2.0+
* MySQL
* php-gmp

##Features
* Phpass Integration: BitAuth uses [phpass](http://www.openwall.com/phpass/) to handle password hashing
* Password complexity rules: Along with minimum and maximum length, specify the required number of:
	* Uppercase Characters
	* Numbers
	* Special Characters
* Password aging: Require your users to change their passwords at a set interval
* Completely custom userdata: Easily customize BitAuth to include any custom you want. Full name, Nickname, Phone number, Favorite color... You name it!
* Group-based permissions: Create groups, and assign users to your groups. Your permissions are set on a group, not a user, so changing user permissions, whether the scale is large or small, is fast and painless.
* Text-based permissions slugs: Simply list your permissions in the configuration file, then check against them in your code. BitAuth handles everything in between.

##Download
[https://github.com/danmontgomery/codeigniter-bitauth/tarball/master](https://github.com/danmontgomery/codeigniter-bitauth/tarball/master)

##Installation
Copy the included files to their appropriate locations in the application/ folder. Import bitauth.sql into your database. **If you would like to change the names of the tables BitAuth uses, you can change them in this .sql file, and must also change them in config/bitauth.php**.

##Notes
The default login is **admin**/**admin**.

It is **highly** recommended you enable db sessions.

Currently, only MySQL is supported. This may change in the future. Or not. We'll see.