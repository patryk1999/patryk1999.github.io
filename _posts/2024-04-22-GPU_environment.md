# Setup of the Docker, WSL and environment for Deep Learning


## The choice of OS

As an user of a dual booted system, I had to ask myself the question one always have to start with prior to setting up a new environment. Should I follow the instructions given by the professor and run everything in WSL or try to get this to work in Ubuntu on my own. 

As soon as I discovered that one would need to work with NVIDIA/CUDA drivers, I instinctively rebooted my mashine to Windows. On a more serious note, those things tend to be difficult enought when one have to follow instructions for setup, so I decided to go for WSL/Windows solution. 

## Docker being docker, Windows being windows

I had WSL and Ubuntu 22 installed on my PC before starting the assignement. This may have disrupted the process in some way as after running all of the commands, the docker still didn't want to find the correct Ubuntu distribution. (2 were installed, but the correct one was set to default). I had to remove the other one, and have just one Ubuntu distro with my WSL to make it work. 

It is worth mentioning that I am using Windows 10. It seems like Windows 11 would be a much better option for this task. WSL on windows 10 seem to be pretty unstable which I found out later in the task. In reality I might not have needed to uninstall the second Ubuntu machine that I mentioned in the last paragraph if I just tried to reset WSL first. 

## GPUfrosen GPU and local python paths

The last problems that I had to face was the fact that the script in the "gpufrosen" branch did not create any local python install which it was looking for later for the purpose of running the Jupiter notebook. Therefore I had to run and build the "gpu" branch first and then the "gpufrozen", that solved the issue. 