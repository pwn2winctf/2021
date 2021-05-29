We found this Rhiza's Government Server, and we need to access it! It runs an Apple II emulator and accepts codes in Applesoft BASIC. If the result of your code generates a valid QR Code standard (not micro QR), it will be read and the content will be executed as a shell command on the Linux system. A very interesting way to interact with a server, don't you think?

Follow the directives below:

* Maximum size of the payload: 268 chars (it will be truncated at this point)
* Send the entire payload in one line (only printable chars), replacing line-break with the symbol § (only 1 allowed)
* Only QR Codes are accepted (**not micro QR**)
* Your code can take up to 50 seconds to be drawn, before the QR Code verification occurs
* If you have any questions, take a look at the source code of the server inside the container

We are releasing two options for you to run the environment and **do your tests locally**.

**Docker:**
    
    $ docker-compose up
    $ nc localhost 1337

[Docker Files](https://static.pwn2win.party/oldschool_adventures_appleii_0cd428eea828e4712ef92a1075a2c6718b6032f75bb0ce0fcaa514049fcb1b57_docker.tar.gz)
   
**LXC Container:**

    $ lxd init and some <Enters> (if you've never used it before)
    $ lxc image import <name>.tar.gz --alias oldschool
    $ lxc launch oldschool oldschool
    $ lxc list (to get the IP)
    $ nc IP 1337
    
[LXC Files](https://static.pwn2win.party/oldschool_adventures_appleii_079445b87c7d73778b8c149d5ecf16aea09b3cd0282ce0dbc91ab3dd1891771a_lxc.tar.gz)

[LXC Mirror](https://drive.google.com/file/d/1kIRwf_H6d9eKZ7pwvVjl5ThK9mt4xUYG/view?usp=drivesdk)

**Server:** nc oldschool.pwn2win.party 1337

