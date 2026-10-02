Remote Access(SSH):

  SSH(Secure Socket Sheel) is a protocol that lets two devices talk to each other securely over a network. The contents sent can't be read by anyone else across the internet, then the contents get revealed once it reaches the other machine.

  SSH allows us to login to computers remotely for us to use. Many Linux based servers(Computers) run without a Graphical User Interface, so we must use terminal to access it. SSH provides access to that terminal from another computer.

More commands to interact with filesystem:

  - touch -> create file
  - mkdir -> create a folder/repository
  - cp -> copy a file or folder
  - mv -> move a file or folder
  - rm -> remove a file or folder

We generally use the word root('/') to mention the top of a directory. It has several branched directories that are very important in linux filesystem.

Important root directories:
  - /etc -> The etc(etcetera) root directory is very important directory, which holds the system and program files. For example, the sudoers file contains the list of the users & groups that have permission to run sudo or a set of commands as the root user.
    
  - /var -> The variable data directory is another important directory that stores data that services and applications write to or read often, like log files (kept in /var/log), and other data not tied to a specific user, such as databases.

  - /root -> The /root directory is nothing but the home directory of the of the system 'root' user.

  - /tmp -> Short for 'temporary', this directory is temporary and is used to store data that is only needed to be accessed once or twice. Once the computer is restarted, the contents of the directory is cleared out.
