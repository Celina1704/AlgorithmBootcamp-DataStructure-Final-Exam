# AlgoBootcamp_Final

cel_17@LAPTOP-NQ3799O4:~$ mkdir hotel-del-jojo/
cel_17@LAPTOP-NQ3799O4:~$ cd hotel-del-jojo
cel_17@LAPTOP-NQ3799O4:~/hotel-del-jojo$ mkdir asisten
cel_17@LAPTOP-NQ3799O4:~/hotel-del-jojo$ cd asisten
cel_17@LAPTOP-NQ3799O4:~/hotel-del-jojo/asisten$ cat > asisten.txt

cel_17@LAPTOP-NQ3799O4:~$ tree hotel-del-jojo
hotel-del-jojo
└── asisten
    └── asisten.txt

1 directory, 1 file

cel_17@LAPTOP-NQ3799O4:~/hotel-del-jojo/asisten$ cd -
/home/cel_17/hotel-del-jojo
cel_17@LAPTOP-NQ3799O4:~/hotel-del-jojo$ mkdir manager
cel_17@LAPTOP-NQ3799O4:~/hotel-del-jojo$ cd manager
cel_17@LAPTOP-NQ3799O4:~/hotel-del-jojo/manager$ cat > data-manager.txt
cel_17@LAPTOP-NQ3799O4:~/hotel-del-jojo$ tree
.
├── asisten
│   └── asisten.txt
└── manager
    └── data-manager.txt

2 directories, 2 files

cel_17@LAPTOP-NQ3799O4:~$ mkdir bos
cel_17@LAPTOP-NQ3799O4:~$ mv bos ~/hotel-del-jojo
cel_17@LAPTOP-NQ3799O4:~$ tree hotel-del-jojo
hotel-del-jojo
├── asisten
│   └── asisten.txt
├── bos
└── manager
    └── data-manager.txt

3 directories, 2 files




cel_17@LAPTOP-NQ3799O4:~$ cd hotel-del-jojo
cel_17@LAPTOP-NQ3799O4:~/hotel-del-jojo$ cd bos
cel_17@LAPTOP-NQ3799O4:~/hotel-del-jojo/bos$ cat > bos.txt
cel_17@LAPTOP-NQ3799O4:~/hotel-del-jojo/bos$ cd -
cel_17@LAPTOP-NQ3799O4:~/hotel-del-jojo$ cd manager
cel_17@LAPTOP-NQ3799O4:~/hotel-del-jojo/manager$ mv data-manager.txt manager.txt
cel_17@LAPTOP-NQ3799O4:~/hotel-del-jojo/manager$ tree
.
└── manager.txt

0 directories, 1 file


