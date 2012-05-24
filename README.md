# s3-stowaway

I'm in ur S3 wagon, uploading all ur jars.

## Installation

Clone this repo, then symlink the `s3-stowaway` executable to someplace in your
$PATH.

## Usage

Run `s3-stowaway $bucket` in the directory that has the pom.xml and the jar
you'd like to upload (the jar must be named according to maven's conventions).
`$bucket` is just the name of the bucket that's serving as your s3-wagon; don't
specify an S3 URL here.
