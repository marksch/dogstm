# dog-adoption-manager
Open source dog adoption manager with a responsive adoption page &amp; management system. Can be integrated with Wordpress or any 
website PHP/MySQL enabled.

# Installation instructions
Create two directories in at root directory
|--root
	|--dogstm
	|--manage
		|--config.php
		|--Login
Login contains the files that come with the download.
Config.php is a duplicate of config_example.php and needs to be copied from dogstm.

### Table layout
Adoption Manager

| id      | name | breed | short_description | long_description | image |
|---------|------|-------|-------------------|------------------|-------|
| int(11) | text | text  | text              | text             | text  |

| Type            | Column |
|-----------------|--------|
| Unique Key      | id     |
| Auto Increment  | id     |

Login

| user_id    | user_name   | user_password_hash | user_email  |
|------------|-------------|--------------------|-------------|
| bigint(20) | varchar(64) | varchar(255)       | varchar(64) |

| Type           | Column    |
|----------------|-----------|
| Auto Increment | user_id   |
| PRIMARY KEY    | user_id   |
| UNIQUE KEY     | user_name |

Users
/* It isn't clear whether there should be a table "Login". Probably not. */

| user_id    | user_name   | user_password_hash | user_email  |
|------------|-------------|--------------------|-------------|
| bigint(20) | varchar(64) | varchar(255)       | varchar(64) |

| Type           | Column    |
|----------------|-----------|
| Auto Increment | user_id   |
| PRIMARY KEY    | user_id   |
| UNIQUE KEY     | user_name |
# Screenshots

| Adoption Manager                             | Adoption Page                                |
|----------------------------------------------|----------------------------------------------|
| ![alt text](https://i.imgur.com/yVNlGEu.jpg) | ![alt text](https://i.imgur.com/dyXrm16.png) |
| ![alt text](https://i.imgur.com/MBOsXMc.png) | ![alt text](https://i.imgur.com/QsNtwVn.jpg) |
| ![alt text](https://i.imgur.com/Tm6QMHX.png) | ![alt text](https://i.imgur.com/yicSvQy.jpg) |
| ![alt text](https://i.imgur.com/yUeI2DL.png) | ![alt text](https://i.imgur.com/MjdoOoJ.jpg) |
