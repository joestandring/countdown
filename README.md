# countdown.sh
A shell countdown timer that I display in my [dwm status bar](https://github.com/joestandring/dotfiles).
## Features
* Creates a temporary file so the current status can be used in other scripts (e.g. a [dwm status bar](https://github.com/joestandring/dotfiles)).
* Alerts the user with a notification.
* Prevents multiple instances of the script running at once.
## Optional dependencies
* libnotify for notifications
## Installation
1. Clone the repository:
```
$ git clone https://github.com/joestandring/countdown.sh
```
2. Enter the directory:
```
$ cd countdown.sh
```
2. Allow running of the script:
```
$ chmod +x countdown.sh
```
3. Oprionally add it to a directory in the PATH like:
```
$ sudo cp countdown.sh /bin/
```
4. Run the script:
```
$ ./countdown.sh
```
## How to use
You can run countdown.sh with 3 arguments corresponding to hours, minutes, and seconds:
```
$ ./countdown.sh 1 30 5
1:30:5
1:30:4
1:30:3
...
```
Alternatively, if you run the script with less than 3 arguments, you will be prompted for the hours, minutes, and seconds:
```
$ ./countdown.sh
Hours: 1
Minutes: 30
Seconds: 5
1:30:5
1:30:4
1:30:3
...
```
