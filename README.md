## Installation of Arduino Create Agent on Raspbian GNU/Linux 10 Buster:

```bash
$ sudo apt install golang

$ git clone https://github.com/arduino/arduino-create-agent.git

$ cd arduino-create-agent/

$ sudo go build -v -i -tags cli

$ ./arduino-create-agent
```

If you do not wish to keep the terminal dedicated while inferencing on Arduino Web Editor run-

```bash
$ nohup ./arduino-create-agent &
```

**Thanks to Arduino Create Team for the doc**

https://forum.arduino.cc/t/raspberry-pi-how-do-i-install-the-plugin-for-linux/395959/15
