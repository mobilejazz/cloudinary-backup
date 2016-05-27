![Mobile Jazz Cloudinary Backup](https://raw.githubusercontent.com/mobilejazz/metadata/master/images/banners/mobile-jazz-cloudinary-backup.png)

# ![Mobile Jazz Badge](https://raw.githubusercontent.com/mobilejazz/metadata/master/images/icons/mj-40x40.png) Cloudinary Backup

> Easy way to back up your Cloudinary Images

**cloudinary-backup** is a **dart** terminal tool that copies all images (to a maximum of 500) from a Cloudinary account to your local disk (under the backups folder in the root of the project).

If your cloud name is "testcloud", your images will be backed up in the backup/testcloud directory.

To get this working, you need to do 4 things.

* Make sure you have DART Installed. Follow the instructions here: https://www.dartlang.org/downloads/
* Clone this repository: git clone https://github.com/mobilejazz/cloudinary-backup.git
* CD into the folder in which the repository is stored locally.
* Run 'pub get' to retrieve the dependencies required.
* Run the script in any of the following forms:
	* Long syntax: `pub run bin/main.dart --name=<cloud_name_here> --key=<app_key_here> --secret=<app_secret_here>`
	* Short syntax: `pub run bin/main.dart -n<cloud_name_here> -k<app_key_here> -s<app_secret_here>`

The script will the do it's things and you will have a backup for your cloudinary files.

More details on the Cloudinary API can be found at http://cloudinary.com/documentation/admin_api


# License

This text is licensed:

    The MIT License (MIT)

    Copyright (c) 2016 Mobile Jazz

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    SOFTWARE.
