cloudinary-backup
=================

This little project copies all images (to a maximum of 500) from a Cloudinary account to your local disk (under the backups folder in the root of the project).

If your cloud name is "testcloud", your images will be backed up in the backup/testcloud directory.

To get this working, you need to do 4 things.

1. Make sure you have DART Installed. Follow the instructions here: https://www.dartlang.org/downloads/
2. Clone this repository: git clone https://github.com/mobilejazz/cloudinary-backup.git
2. CD into the folder in which the repository is stored locally.
3. Run 'pub get' to retrieve the dependencies required.
4. Run the in any of the following forms:
	4.1: pub run bin/main.dart --name=<cloud_name> --key=<app_key> --secret=<app_secret>
	4.2: pub run bin/main.dart -n=<cloud_name> -k=<app_key> -s=<app_secret>

The script will the do it's things and you will have a backup for your cloudinary files.

More details on the Cloudinary API can be found at http://cloudinary.com/documentation/admin_api