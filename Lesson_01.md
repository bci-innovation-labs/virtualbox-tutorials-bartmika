# Installing CentOS 7 on VirtualBox
## Download Required Files

1. Go to the following [link](http://isoredirect.centos.org/centos/7/isos/x86_64/) and download the file from the [Waterloo](http://mirror.csclub.uwaterloo.ca/centos/7.6.1810/isos/x86_64/).

2. Go to the following [link](https://www.virtualbox.org/wiki/Downloads) and download ``VirtualBox``. If you are using ``Windows`` then download the ``Windows`` OS.

3. Install ``VirtualBox`` once it has been downloaded.

## Setup VirtualBox
The following steps

1. Open up the ``VirtualBox`` application.

    ![yyy](media/1.PNG)

2. Click the ``New`` button which is located in your top left corner. You will get a dialog modal asking for filling in the virtual machine details.

    ![yyy](media/2.PNG)

3. For ``Name`` enter **BCI Innovation Labs**. For ``Type`` select **Linux**. For ``Version`` select **Red Hat (64-bit)**. Afterwords click the ``Next`` button.

    ![yyy](media/3.PNG)

4. The following screen will be displayed asking for how much memory (i.e. RAM) should this *virtual machine* use when it is running. My recommendation is to select as much memory as possible but do not cross over the orange line. Afterwords click the ``Next`` button.

    ![yyy](media/4.PNG)

5. Click the ``Next`` button.

    ![yyy](media/5.PNG)

6. Select ``VDI (VirtualBox Disk Image)`` and click the ``Next`` button.

    ![yyy](media/6.PNG)

7. The recommend option is ``Fixed size`` because the *virtual Machine* will run quicker. Afterwords click the ``Next`` button.

    ![yyy](media/7.PNG)

8. Step 1 is select ``10.00 GB`` and step 2 is click the folder icon and save the *virtual machine* location where enough disk space exists. Afterwords click the ``Create`` button.

    ![yyy](media/8.PNG)

9. Once you clicked the ``Create`` button the *virtual machine* will create an instance. You are ready to begin!

    ![yyy](media/9.PNG)

10. Now right click on the *virtual machine* that you created. You should see the following

    ![yyy](media/10.PNG)

11. Now click ``Advanced`` tab and select the following options to be ``Bi-directional``.

    ![yyy](media/11.PNG)

12. Afterwords click ``System`` tab on the left and adjust according to how many processors your computer can support. My recommendation is to not cross the orange line.

    ![yyy](media/12.PNG)

13. Next click ``Display`` tab and expand the ``Video Memory`` to be **100%**.

    ![yyy](media/13.PNG)

14. Next click ``Storage`` tab and click the ``BCI Innovation Labs.vdi``. Afterwords click the **Solid-state Drive** if you are using a *solid-state hard drive*. If you are using a *mechanical hard drive* then do not click. Now save by clicking ``OK`` button.

    ![yyy](media/14.PNG)

15. Click the ``Start`` button for your *virtual machine*.

    ![yyy](media/15.PNG)

16. You should see a screen like this. This is good! If you clicked the blank screen and you cannot click anywhere, simply click ``CTRL`` (LEFT) and ``CTRL`` (RIGHT) on your keyboard and your mouse should appear again.

    ![yyy](media/16.PNG)

17. We will be loading up our ``CentOS 7`` image now. Click the ``Devices`` menu item, click ``Optical Disk`` and click ``Add``. You should see something like this as a modal will appear asking for the location of the ``CentOs 7`` image. Find it, select it and click ``Open``.

    ![yyy](media/17.PNG)

18. Now the following screen will appear, click inside the window and move to select ``Install CentOS 7`` and then click ``ENTER`` on your keyboard.

    ![yyy](media/18.PNG)

19. Select ``English`` and then ``English (Canada)``. Afterwords click the ``Continue`` button.

    ![yyy](media/19.PNG)

20. The following screen will load up, give it a few seconds and the following options will become available. Click the ``SOFTWARE SELECTION`` button.

    ![yyy](media/20.PNG)

21. Select ``GNOME Desktop`` and select the following dependicies. Afterwords click the ``Done`` button.

    ![](media/21.PNG)

22. Next click the ``INSTALLATION DESTINATION`` section.

    ![yyy](media/22.PNG)

23. Click the disk unitl it is selected (you will notice a blue colour) and then click the ``Done`` button.

    ![yyy](media/23.PNG)

24. Click the ``NETWORK & HOSTNAME`` section.

    ![yyy](media/24.PNG)

25. Click to enable the ethernet to say ``ON``. For host name enter what you like. Afterwords click the ``Done`` button.

    ![yyy](media/25.PNG)

26. Finally click the ``Begin Installation`` button.

    ![yyy](media/26.PNG)

27. You should see the following installation screen. This is good!

    ![yyy](media/27.PNG)

28. Click the ``ROOT PASSWORD`` section.

    ![yyy](media/28.PNG)

29. Enter a *secure password* and then click the ``Done`` button.

    ![yyy](media/29.PNG)

30. Next click the ``USER CREATION`` section.

    ![yyy](media/30.PNG)

31. Populate the fields as follows and make sure you select the ``Make this user administrator``. Afterwords click the ``Done`` button.

    ![yyy](media/31.PNG)

32. You are setup! Now just wait until the *virtual machine* finishes installing ``CentOS 7``. Go grab some tea or coffee.

    ![yyy](media/32.PNG)

33. Once the installation finishes, click the ``Reboot`` button.

    ![yyy](media/33.PNG)

34. You should see something like this. Don't do anything, just wait.

    ![yyy](media/34.PNG)

35. You will get a screen like this, click the ``LICENSE INFORMATION`` section.

    ![yyy](media/35.PNG)

36. Read carefully, agree and click the ``Done`` button.

    ![yyy](media/36.PNG)

37. Finally click the ``FINISH CONFIGURATION`` button.

    ![yyy](media/37.PNG)

38. Just wait and you will have the following load up. This is the login prompt. Congradulations!

    ![yyy](media/38.PNG)

39. Login.

    ![yyy](media/39.PNG)

40. Once you successfully log in, you will see a screen like this. Click ``English`` and click ``Next`` button.

    ![yyy](media/40.PNG)

41. Click ``English (Canada)`` and click ``Next`` button.

    ![xxx](media/41.PNG)

42. Click ``Next``.

    ![yyy](media/42.PNG)

43. Click ``Skip`` or you are welcome to sign in. The choice is optional and up to you.

    ![yyy](media/43.PNG)

44. Afterwords you should see this. Click the button.

    ![yyy](media/44.PNG)

45. And then you will see this screen. Close this screen.

    ![yyy](media/45.PNG)

46. Finally you will see the following. This means you have setup ``CentOS 7`` *virtual machine* on your computer! Congradulations!

    ![yyy](media/46.PNG)
