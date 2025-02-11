# Activity events

Here are a list of activity events, which are used in the audit log feature.

```text
server.backup.restore-failed
server:allocation.create
server:allocation.delete
server:allocation.notes
server:allocation.primary
server:backup.complete
server:backup.delete
server:backup.download
server:backup.fail
server:backup.lock
server:backup.restore
server:backup.restore-complete
server:backup.restore-failed
server:backup.restore-started
server:backup.start
server:backup.unlock
server:console.command
server:console.command
server:database.create
server:database.delete
server:database.rotate-password
server:file.compress
server:file.copy
server:file.create-directory
server:file.decompress
server:file.delete
server:file.download
server:file.pull
server:file.read
server:file.rename
server:file.uploaded
server:file.write
server:power.kill
server:power.restart
server:power.start
server:power.stop
server:reinstall
server:schedule.create
server:schedule.delete
server:schedule.execute
server:schedule.update
server:settings.description
server:settings.rename
server:sftp.create
server:sftp.create-directory
server:sftp.delete
server:sftp.denied
server:sftp.rename
server:sftp.write
server:startup.edit
server:startup.image
server:subuser.create
server:subuser.delete
server:subuser.update
server:task.create
server:task.delete
server:task.update

* If there are any missing events, feel free to open a pull request.
```
