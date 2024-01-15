# Copy Plush
## The purpose of birth
Do you not know how many large files or folders are copied when using the `copy` command on `Linux`?</br>
To avoid aimless waiting and waiting without feedback, as you know, waiting without feedback is too boring, and `love` is also (lol).</br>
That's why `copy plus` was born, and its significance lies in providing feedback on waiting. During the waiting period, you can know the progress and arrive at the destination appropriately, without blindly waiting.

## Let's take a look at what its feedback looks like
### Copy File
```bash
stephen@ubuntu:~/my_work/copy-plush/src$ ./hcp ~/mysql-connector-java-8.0.19.zip ~
[COPY][4.41 MB]mysql-connector-java-8.0.19.zip ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━╸ 100% 0:00:00
[21:56:41] INFO     Done.                
```
### Copy Folder
```bash
[21:58:41] INFO     C test1/.            
[COPY][4.41 MB]mysql-connector-java-8.0.19.zip ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━╸ 100% 0:00:00
           INFO     C test1/y    
           INFO     C test1/y/d  
[COPY][12.00 B]test.txt ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━  100% 0:00:00
           INFO     C test1/t                  
```
In summary, whether it is copying files or folders, it can perform this task excellently, and it does not require the `-r` command to tell it to copy folders or files. It can autonomously identify the types of these files.
In addition to providing progress, it also lists the size of each file and prints it out in the most suitable units.

## What will it develop into in the future?
As a copy plus developer, I hope that more developers can join in and promote the progress of this project in the future. Initially, I hope to add more copy algorithms to it in the future. I hope that copy plus can not only provide feedback but also improve efficiency. For example, in the future, I will consider using divide and conquer to synchronize copying a large file or a certain folder, just like make j20, Make full use of CPU for transmission.
Of course, in the future, i also hope to add mechanisms such as DMA to make copy plus more compatible with plus.

## Do you have any ideas about this project?
What are you waiting for? Hurry up and fork! Submit your suggestions and sharing to me through Git, make it even stronger!
