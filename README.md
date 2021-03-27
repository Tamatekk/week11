This weather service will show the current weather in Vancouver

To start setting up this service, all of the files must be cloned to a directory, the files will be in a folder called "week 11"

Once this has been done, move the files "wthr.timer" and "wthr.service" to the "/etc/systemd/system" directory

Then, edit the paths found beside "ExecStart" and "WorkingDirectory" within the "wthr.service" file, to match the directory where the "wthr" file resides.

Make sure that for "ExecStart" the path still ends with "wthr" as this refers to the file and not a directory.
