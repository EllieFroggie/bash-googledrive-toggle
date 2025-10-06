# Google Drive Toggle

A very simple bash script to toggle a mounted google drive filesystem.

## STATE FILE
A file to track whether drive is mounted or not. Specified as a file path by $STATE. 1 if unmounted, 0 if mounted.

## USAGE

Edit $MOUNT_DIR to the directory you want to mount to

Edit $DRIVE_NAME to the name of your rclone drive

Make executable:
`chmod +x ./drivetoggle`

Run:
`./drivetoggle`
