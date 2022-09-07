# gsdc-oscar-intro-workshop
Short introduction to using VNC / Jupyter on Oscar

## Connecting to VNC

The most flexible way to connect to Oscar is by using Virtual Network Computing (VNC). VNC nodes allow users to connect remotely to a graphical desktop environment running on an Oscar compute node.

Using VNC, you can run GUI-based applications such as Matlab, Mathematica and Rstudio, with fast access to Oscar's high performance file system. This allows you to analyze and visualize data without needing to move it off of Oscar.

The CCV VNC requires that you download a VNC client onto your machine.

**Instructions**

1. Ensure that you are either connected to [Brown VPN](https://vpn.brown.edu/vdesk/webtop.eui?z=/Common/Brown-Shib-VPN-Brown_VPN_CisAdmin&webtop=/Common/Brown-Shib-VPN-brown-vpn_webtop&webtop_type=webtop_na_only) or on a Brown Compliant Network (BrownWifi, ethernet etc). 

2. Ensure you have a recent version of the Java JDK or JRE. These can be found on [Oracle's Java Download Page](https://www.oracle.com/java/technologies/downloads/).

3. Download the [CCV VNC client](https://drive.google.com/file/d/1MX20afDiKTJC58VzGvGU0GqD-F-8frit/view).

4. If Java has been installed correctly you can now run CCV_VNC_2.x.jar by double clicking on it. 

- On a Mac, you may need to first right click on the jar, choose "Open", and give the jar permission to run. For newer versions, you may need to open a terminal, cd into the directory where the jar file is, and then run java -jar CCV_VNC_2.0.3.jar.
- On Windows, you may have to right click on the jar, Choose "Open with", and select the Java JDK.

5. In the "Username" and "Password" fields, enter your Oscar username and password, respectively. The server should remain desktop.ccv.brown.edu. Press "Connect".

6. On the window that pops up, select the memory/CPU parameters you want for your VNC session.

7. Your VNC session should appear. If you see a window saying your job was queued, it means there were not enough free resources to start your job and it has been placed into the scheduling queue. You will continue to receive that message until your VNC job actually starts. You can monitor the progress of your job in the queue using normal scheduler commands.

8. Once your VNC session starts, you should see your desktop. There are two new buttons on the menubar at the top, Suspend VNC session and End VNC session.

When you are finished with your VNC session, click the "EXIT" button. You now have two choices:
- Disconnect from VNC session closes the client but leaves your VNC session running. When you log in again, you will be automatically connected to your existing VNC session.
- Kill VNC session closes the client and stops your VNC session from running.



## Cloning a GitHub Repo with `gh`
- John

## Setting up a Conda Environment
- John

## Loading Jupyter
- Aisulu

## Running the example
- Aisulu
