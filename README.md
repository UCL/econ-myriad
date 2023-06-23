# econ-myriad
General instructions for using Econ-myriad

# Introduction
The UCL Economics Department has access to UCL's high performance computing cluster, Myriad. This cluster is a linux based computing cluster consisting of several login nodes and hundreds
of ``compute" nodes. 

To use the system, a user must either be connected to the UCL network (i.e. using a computer at UCL or connected to eduroam at UCL) or connected to the UCL VPN.

Typical use of Myriad is:
1. Connect using ssh to analyse data or to run Stata, R (command line version), or Matlab.
2. Connect using sftp to copy data or files to Myriad or to copy output from Myriad.
3. Connect using a web browser to use RStudio server

# Connect using ssh
1. If you are not connected to the UCL network, first connect to the UCL VPN.
2. Login using ssh

````
ssh -X username@econ-myriad.rc.ucl.ac.uk
````

** The "-X" flag enables "x-forwarding". This is required to allow Myriad to forward graphical images to your local computer monitor
** Replace the word "username" with your username.
** After entering the command, the system will ask that you enter a password

Once you are connected you can use any unix commands to: 
1. create, copy, delete or move files or directories.
2. connect to a "compute" node
3. connect to RDSS using sftp to copy data from RDSS to Myriad

