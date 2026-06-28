# File Permissions Commands

- `ls -l` — display file permissions and ownership
- `chmod 755 file` — change permissions (read/write/execute for owner, read/execute for others)
- `chmod u+x file` — add execute permission for the owner
- `chmod g-w file` — remove write permission for the group
- `chmod o+r file` — add read permission for others
- `chown user file` — change file owner to `user`
- `chown user:group file` — change file owner and group
- `umask` — show or set default permission mask for new files
```