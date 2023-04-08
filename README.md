<p align="center">
    <img  width="500" height="300" src="SIMPLY-LINUX.png" alt="Simply-Linux logo">
</p>


# Welcome to Simply-Linux 👾 
<p align="center">

</p>
Simply Linux is a resources repo for the Linux beginners who want to learn and upskill themselves. Give it a star ⭐ and contribute for any improvement, Your contributions are most welcome 😇. Add some more resources to contribute and help Current as well as future learners and beginners. 

# Installing Linux Distro(s) onto Virtualbox
## Setting up the Virtualbox
- Step 1: Firstly download Virtual box by clicking on the [link](https://www.virtualbox.org/)

- Step 2: Go to downloads and then, Select your distribution. Download will Start & then, Install VirtualBox.
- Step 3: Click [here](https://ubuntu.com/) and go to download section click on the latest version of the iso file. As of now it's 22.04 LTS(LTS Stands for Long Term Support and I personally, use it only since, it's for a longer term and rest is upto you)
- Step 4: Open Virtual box, then click on 'New' and Give name to your machine and then select the type and the version (usually, both the type & version are automatically chosen by the virtualbox as you type in name of the machine.)
- Step 5: Now, by default you'll have a path in machine folder and if you want to change it then you can click on the drop down pointer and click on 'other' and select the folder you want. Click on 'Next'.
- Step 6: Select the memory size select it according to your device or like till the end of green mark. (the more the memory and the smoother it runs.) But it's advicable not to stretch it beyond the red mark because you'll also need RAM for your Host OS to run smoothly :). 

- Step 7: After Step 6, Click on 'Next'. Then, For Hard Disk, leave the settings as it is and proceed further by clicking on 'Create' and for the Hard disk type also leave it as it is and click on 'Next'
- Step 8: Choose the file location and size(If you have storage/space issues then consider changing the location/path at the file location, maybe to another drive) as per your machine and convenience. Click on 'Create'. And, Boom! Your machine will be added to the Virtualbox.
- Step 9: Select the Virtual Machine you just created and then, click on the 'Settings' option present to the right of 'New'. In General section, go to 'Advanced' and then, You'll see that the 'Shared Clipboard' & 'Drag'n'Drop' options are 'Disabled' by default, You need to set them to 'Bidirectional'(means that with your host OS and your VM or Guest OS you will be able to drag'n'drop items and also they'll share the same clipboard) Leave everything as it is and proceed to the 'System' section.
- Step 10: In the 'System' section, go to 'Processor' and set the CPUs you'll be allocating to the VM as till the green mark or also as per your convenience (By default, it will allocate only 1 processor to the VM). Go to the Display section and maxout the video memory 
- Step 11: Go to 'Storage' and then click on the 'Empty' written under the 'Controller IDE' and then go to the leftmost blue disk icon and click on it select 'Choose a disk file' and go where your Ubuntu ISO File is located then, Select the ISO File and click on 'Open' and Now you'll be able to see the name of the ISO File where it was previously written 'Empty' Now leave remaining settings set as default and Click on 'OK'.
## Installation of Ubuntu on Virtual Box
- Step 12: Make sure your virtual machine is selected and then click on 'Start' and then select 'Try or install ubuntu' and press enter and now your ubuntu installation will begin.
- Step 13: Choose your 'language' and click on 'Install ubuntu' choose your Keyboard Layout as per your convenience (for eg: I use English(US)) and after selecting, Click on 'Continue'.
- Step 14: In the 'Updates and other software' -- The following should be selected: 1. Normal Installation 2. Download updates while installing Ubuntu and then, Click on 'Continue'
- Step 15: In 'Installing Type' --- Make sure 'Erase disk and install Ubuntu' is selected, (If you're confused or worried about what does Erase disk means here then let me tell you Since, you're installing Ubuntu on a virtual box that means none of your data will be erased from your Host OS. It will just erase the virtual drive not the Original/Host OS drive)
- Step 16: Then, Select Location and click on 'Continue'
- Step 17: Then, Enter your name, machine's name, pick a username, and choose a password and then, click on 'Continue'. After the installation is complete, Then, click on 'Restart Now' and then a window appears where you need to press 'Enter' and now your ubuntu system will restart.
- Step 18: After restarting, Enter your credentials and login to the ubuntu account(Make sure to enter the password which you entered during installation).
- Steo 19: Congo!! You can now use Ubuntu VM. 

## To resize the VM to the desktop screen size
- Step 1: Open the Terminal, Copy the command given below and paste it in the Terminal, Hit enter and type in your ubuntu password
```linux
sudo apt update
```
- Step 2: Now, Copy and Paste this command, 
```linux
sudo apt install -y build-essential linux-headers-$(uname -r)
```
- Step 3: Go to the 'Devices' option and click on 'Insert Guest Additions CD Image'
-Step 4: Click on the CD Image icon and it'll open a folder, and there will be a file named as 'autorun.sh' run it as program OR follow Step 5, it does the same job.

- Step 5: Right click in the folder and a terminal window will open, then, Copy and paste the below command in your terminal and hit enter and type in the ubuntu password in the pop-up window
```linux
./autorun.sh
```

- Step 6: After the process is done, press return/enter and Restart the Ubuntu VM

- Step 7: Open the VM, Login to your Guest OS and now when you maximize the window it'll adjust to fullscreen & now you can start using it!!.

## Resources:
- [Linux Introduction (All you need to know to get started with the Terminologies)](https://satyams.hashnode.dev/linux-prelude-and-some-basic-terminologies) 
