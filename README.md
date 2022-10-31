# About 'hunter'

<p align="center">
   </a>
      <a href="https://github.com/gh0st-anonymous/analyzer">
      <img src="https://img.shields.io/badge/Version-1.0.0-darkgreen">
        <img src="https://img.shields.io/badge/Release%20Date-may%202022-purple">
  <img src="https://shields.io/badge/Bash-100%25-066da5">
  <img src="https://shields.io/badge/Platform-Linux-darkred">
    </a>
  </p>
</p>

hunter is a bash script that analyze automatically every suspicious networks live info activity's such as IPs, URLs, Domains and more using:

Automater and VirusTotal.

### Possibility and Capability

> ADVANTAGES:

- can detect malwares, viruses, suspicious activity from pcap file such as MITM or related dangerous IPs used by bots.

- will create an 'output-info file' automatically if the IP (for ex) have been stocked in the googledb as 'Dangerous'.

- check if the new supposed output file or directory is already created. (instead of :: error cant write on 'file.txt' because 'file.txt' already exist :: you'll get file.2.txt or dir.2 then .3, .4, ect...)

- check for every errors possible. (correct path, correct answers as input, if the ip choosen is truly a correct ip)

- the required dependencies and libraries will be scanned and any missing packages will be installed automatically.

- easy to use since explanations are written. ([sudo] bash / ./hunter -I)

- if you need help for the script usage, type [sudo] bash / ./hunter -h, for more details about the options.

- help and info menu doesn't require sudo privileges.


> DISADVANTAGES:

- Automater scans are very slow.

### 'hunter' Project

a [project](https://github.com/gh0st-anonymous/hunter/files/9894773/project.pdf) made by [ThinkCyber.](https://www.thinkcyber.co.il/)

### Video Demonstration

Be Aware: the script could be different from the video since he got upgraded.

[![image](https://user-images.githubusercontent.com/102325071/198856530-b6c9b4e6-999f-4a3b-ba53-bea8d2158bb3.jpg)](https://www.youtube.com/watch?v=ShjDHLr2tZM)

### Script Usage

just launch the script by typing:

[ -h (stand for help) for more flags options]
[ -I (stand for Info) for more info about the script]

![pic](https://user-images.githubusercontent.com/102325071/198970600-7e97f9da-5704-4b2c-b831-8240417b6b5f.png)

### Download

from [zip](https://github.com/gh0st-anonymous/hunter/files/9900085/hunter.zip) file or from github: 

    git clone https://github.com/gh0st-anonymous/hunter
