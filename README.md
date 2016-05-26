cloudinary-backup
=================

This little project copies all images (to a maximum of 500) from a Cloudinary account to your local disk (under the backups folder in the root of the project).

If your cloud name is "testcloud", your images will be backed up in the backup/testcloud directory.

To get this working, you need to do 4 things.

* Make sure you have DART Installed. Follow the instructions here: https://www.dartlang.org/downloads/
* Clone this repository: git clone https://github.com/mobilejazz/cloudinary-backup.git
* CD into the folder in which the repository is stored locally.
* Run 'pub get' to retrieve the dependencies required.
* Run the script in any of the following forms:
	- pub run bin/main.dart --name=cloud_name_here --key=app_key_here --secret=app_secret_here
	- pub run bin/main.dart -ncloud_name_here -kapp_key_here -sapp_secret_here

The script will the do it's things and you will have a backup for your cloudinary files.

More details on the Cloudinary API can be found at http://cloudinary.com/documentation/admin_api