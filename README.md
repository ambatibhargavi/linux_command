<img width="1920" height="1081" alt="image" src="https://github.com/user-attachments/assets/de1a1c11-70f7-4395-8348-c70d1ec4b2b6" />




Top 50 Linux Commands with Examples
📁 File & Directory Management

ls – List files and directories

ls -l


pwd – Print working directory

pwd


cd – Change directory

cd /home/user/Documents


mkdir – Create a new directory

mkdir myfolder


mv – Move or rename files

mv file.txt ~/Desktop/
mv oldname.txt newname.txt


cp – Copy files or directories

cp file.txt /home/user/Desktop/
cp -r folder1 folder2


rm – Remove files or directories

rm file.txt
rm -r foldername


touch – Create an empty file

touch newfile.txt


ln – Create symbolic or hard links

ln -s /path/to/file shortcut


clear – Clear terminal screen

clear

📄 File Viewing & Text Operations

cat – View file contents

cat file.txt


echo – Print text to screen or file

echo "Hello Linux!" > hello.txt


less – View long files one page at a time

less file.txt


man – Show manual page for a command

man ls


uname – Show system information

uname -a


whoami – Display current user name

whoami


tar – Archive files

tar -cvf archive.tar folder/
tar -xvf archive.tar


grep – Search text in files

grep "error" logfile.txt


head – Show first 10 lines of a file

head file.txt


tail – Show last 10 lines of a file

tail -f logfile.txt

⚙️ File Comparison & Sorting

diff – Compare two files line by line

diff file1.txt file2.txt


cmp – Compare two files byte by byte

cmp file1.bin file2.bin


comm – Compare sorted files line by line

comm file1.txt file2.txt


sort – Sort text in a file

sort names.txt


export – Set environment variables

export PATH=$PATH:/new/path


zip – Compress files

zip archive.zip file1 file2


unzip – Extract zip files

unzip archive.zip


ssh – Connect to a remote server

ssh user@192.168.1.10


service – Start/stop a service

service apache2 restart


ps – View running processes

ps aux

💀 System & Network Commands

kill / killall – Stop a process

kill 1234
killall firefox


df – Show disk space usage

df -h


mount – Mount a device or partition

mount /dev/sdb1 /mnt


chmod – Change file permissions

chmod 755 script.sh


chown – Change file owner

chown user:user file.txt


ifconfig – Show network configuration

ifconfig


traceroute – Show network path to a host

traceroute google.com


wget – Download files from the internet

wget https://example.com/file.zip


ufw – Firewall management

sudo ufw enable
sudo ufw status


iptables – Configure firewall rules

sudo iptables -L

🧰 Package & User Management

apt, pacman, yum, rpm – Package management

sudo apt update && sudo apt install nginx


sudo – Execute command as root

sudo rm file.txt


cal – Display calendar

cal


alias – Create shortcut commands

alias ll='ls -la'


dd – Copy and convert files/disks

dd if=/dev/sda of=/dev/sdb


whereis – Locate command binary and manual

whereis python


whatis – Display brief command description

whatis ls


top – Monitor system processes live

top


useradd – Add a new user

sudo useradd newuser


passwd – Change user password

passwd newuser
