#Date- 30th June 2023

1. Create a simple file and do ls -ltr to see the details of the files . As a task, change the user permissions of the file and note the changes after ls -ltr

![Capture](https://github.com/seematripathi/90DaysOfDevOps/assets/33751911/3fa91782-44ad-4a5c-a4fb-a82fe0290935)

2.Write an article about File Permissions based on your understanding from the notes.

File Permission refers to the permissions assigned for the given files.Permissions can be assigned to user, group or others to read , write or execute the file.
To change the permission we can use -
  chmod u+rwx,g+rwx,o+rwx permissions.txt (change the read/write/execute permissions of the file)
  where, u ->user,g->group, o->others, r->read, w->write, x->execute

  chown $USER permission.txt (change the ownersip of the file)

  chgrp group1 group2 (change the group ownership of the file.

3. Read about ACL and try out the commands getfacl and setfacl

   ACL refers to Access Control List . It allows to apply more specific permissions to a file or directory without modifying the base ownership.

  ![Capture1](https://github.com/seematripathi/90DaysOfDevOps/assets/33751911/c4169051-a530-4848-9d3c-04aa85bd9948)
