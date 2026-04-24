# Day 03 - CHMOD

## Objective

What was the goal for today?

Change Permissions and Ownership

## What I Learned

Change Permission using the command chmod. You use + to add a permission and use - to remove a permission. eg. chmod g+w extract.py. This adds write permission to a group.Another example is chmod o-r transform.py, this removes read permission to other people on the system. Then chmod a+x load.py, this gives everyone ie a execute permission.
One can use the Octal notation eg chmod 741 extract.py , this means that the owner 7 has rwx (4+2+1) read, write and execute permission, the group has 4 which is r-- (4) ie read only permission while all others have --x (1) execute permission.
Change ownership using chown eg. sudo chown abike transform.py. Another example is sudo çhown abike:
analyst load.py, here we changed the owner and group at the same time.


## What I Built / Practiced

- 
- 

---

## Challenges Faced

- 
- 

---

## Key Takeaways

- Change permission is chmod
- One can use symbolic or octal modes to change permission
- change owner is sudo chown

---

## Resources

04-linux-file-permissions-and-ownership/01-file-permissions-and-ownership.md by Najeeb Sulaiman 

---

## Output

(Include links, screenshots, code snippets, or results)
