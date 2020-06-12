# How to install java

**First**

1. Go to this link: [click me] (https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html)

2. Scroll down half way so you see: jdk-8u251-windows-x64.exe. Install this

3. Once you have installed it go to the folder you installed it in.

4. Open up jdk1.8.0_251. Then from there open up bin and copy the directory path. (C:\Program Files\Java\jdk1.8.0_251\bin)

5. Next in the windows search bar, search for "This PC".

6. Right click on the first result and then click "Advanced System Settings"

7. A new panel will open up and click "Environment Variables"

8. Scroll down on the second scroll pane and find "Path" and double click it.

9. Now click "new" (On the pane that just opened up) and paste in the path you copied in the start

   **Test**

   To test it worked:

   - Open up the command prompt (search for cmd)

   - Type "java" and click enter

   - You should not see

     ```powershell
     'java' is not recognized as an internal or external command,
     operable program or batch file.
     ```

     