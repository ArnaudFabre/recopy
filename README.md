# recopy

Date Copy with a sqlite3 database

Allows to classify files even if the whole archive is not present on the hardrive.

## Usage

`./recopy init`

Initialize a sqlite3 database

`./recopy insert [directory or file]`

Insert image in database if not already there and copy files in year/month/md5_name format

`./recopy status`

Number of images in the database

`./recopy search [where clause]`

Search in the database

## Other tools

You can use rclone.org to then copy to a cloud account.

