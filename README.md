Alliance
Getting Started

To build Alliance from source, you'll need to be familiar with Git and Repo.

To initialize your local repository, use this command:

repo init -u https://github.com/AllianceOreo/manifest.git -b 8.1

Then to sync source, use this command:

repo sync

After syncing is done, use these commands to build:

1.) . build/envsetup.sh

2.) lunch

3.) select device

4.) mka bacon -j(x)
