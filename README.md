**SYSTEM INFORMATION**

uname  -a # Display Linux system information

uname  -r # Display kernel release information

lsb_release  -a # Show which version of ubuntu installed

uptime  # Show how long the system has been running + load

hostname  # Show system host name

hostname  -I # Display the IP addresses of the host

last reboot  # Show system reboot history

date  # Show the current date and time

cal  # Show this month's calendar

w  # Display who is online

whoami  # Who you are logged in as

**HARDWARE INFORMATION**

cat /proc/cpuinfo # Display CPU information

cat /proc/meminfo # Display memory information

free -h # Display free and used memory ( -hfor human readable,
-mfor MB, -gfor GB.)

lspci -tv # Display PCI devices

lsusb -tv # Display USB devices

dmidecode # Display DMI/SMBIOS (hardware info) from theBIOS

hdparm -i /dev/sda # Show info about disk sda

hdparm -tT /dev/sda # Perform a read speed test on disk sda

**PERFORMANCE MONITORING ANDSTATISTICS**

top # Display and manage the top processes

mpstat 1 # Display processor related statistics

vmstat 1 # Display virtual memory statistics

iostat 1 # Display I/O statistics

tcpdump -i eth0 # Capture and display all packets on interface eth0

tcpdump -i eth0 'port 80' # Monitor all traffic on port 80 ( HTTP )

lsof # List all open files on the system

lsof -u user # List files opened by user

free -h # Display free and used memory ( -h for human readable, -m
for MB, -g for GB.)

watch df -h # Execute "df -h", showing periodic updates

**USER INFORMATION ANDMANAGEMENT**

id # Display the user and group ids of your
current user.

last # Display the last users who have loggedonto the system.

who # Show who is logged into the system.

w # Show who is logged in and what they are doing.

groupadd test # Create a group named "test".

useradd -c "John Smith" -m john # Create an account named john, with a
comment of "John Smith" and create the user's home
directory.

userdel john # Delete the john account.

usermod -aG sales john # Add the john account to the sales group
