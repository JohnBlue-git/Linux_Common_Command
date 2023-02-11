# Linux_Common_Command
Note about Linux common command




# Navigation

pwd
: current directory

ls
: list contents in the current directory
ls -a
: list … (including hidden files)
ls -l
: list … (showing more specific detail)
ls (path)
: list … (showing contents under this path)

man (command)
: detail about this command

cd
cd /User/…
: change directory
cd ..
: return to upper directory

# Control file and folder

mkdir
: create new directory

cat
: show content of the current file

cp
cp old.txt new.txt
: copy
cp -r <old folder> <new folder>
: copy folder

rm
: delete file
rm -r <folder>
: delete folder
rm -rf
: enforce to delete

mv
: move
mv old.txt <new path>
: move file to new directory

grep “match” <file>
: find specific pattern in <file>
ls | grep “match"
: find files or folder with name “match"
  pipe (useful;) :  |

tar
: package a file or folder

zip
unzip
: compress files or folders

chmod
: change permission of file or folder

chown
: change owner of file or folder


# Control thread

kill
: kill thread

top
: watch all thread that are running right now
https://tigercosmos.xyz/post/2020/04/unix/top-usage/

# Web

ping
: connection status of server

wget
: download file, …,  webpage





# vim
:Text editer




# Package manager

brew install
:(for mac)

apt install
:(for ubuntu)
