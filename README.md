# Energy Consumption Spotify on macOS device 
To rerun the experiment described in the [blogpost](https://luiscruz.github.io/course_sustainableSE/2023/p1_measuring_software/g2_stockfish.html), follow these steps. 

## Necessary software 
We use a python package called spotify-cli to be able to play, pause, save (/download) music through the Spotify application installed on your device. 

### Installing Spotify-cli 
Follow the steps according to the spotify-cli [README](https://github.com/pwittchen/spotify-cli-linux). 
Important to note is that you need to have your Spotify client up and running to use the interface. 
Summarized:
1. In terminal, run: pip3 install spotify-cli --upgrade 
2. In terminal, run: spotify auth login 
3. This runs guides to an online login page, where you need to login to Spotify to be able to use the interface 
4. For instructions on the possibilities, run spotify --help, this contains all the instructions necessary to use the interface

### Installing Intel Power Gadget 

We use Intel Power Gadget to measure the energy usage on the device. Install this using the [instructions](https://www.intel.com/content/www/us/en/developer/articles/tool/power-gadget.html) on the website. 

## Script

The script file used for the first run can be found [here](script_experiment1) and the script file used for the second run can be found [here](script_experiment2). The script file will ask the experimenter to manually execute either a clear of the cache, or a download deletion. This will happen before a stream run, a play of a downloaded song run or the downloading of a song run. After the experimenter has completed the task, the experimenter can press any key and the script will continue to run.

##

The scripts run according to the logic explained in the blogpost (add link!).
The hard/software settings needed to achieve the results can also be found there.
