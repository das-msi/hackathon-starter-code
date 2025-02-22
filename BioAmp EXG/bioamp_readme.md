# Instructions to use bioamp-pill with the bioamp shield and arduino uno


## Introduction:

The bioamp pill can be used to read EEG/EMG/EOG/ECG signal with the arduino board. 

**A manual is given to use the muscle bioamp shield. Scan the QR code to access the [manual website](https://docs.upsidedownlabs.tech/hardware/bioamp/bioamp-exg-pill/index.html#). ** *Note: sharing the link did not work.*

**The arduino and python code is given at [github repository: ](https://github.com/upsidedownlabs/Muscle-BioAmp-Arduino-Firmware/tree/main) .**


## Software Installation:

1. Install the Arduino IDE version 1.8.19 from the official [website: https://www.arduino.cc/en/Main/Software](https://www.arduino.cc/en/software)
2. Install Spike Recorder from BackyardsBrain website: [website: https://backyardbrains.com/products/spikerecorder](https://backyardbrains.com/products/byb-spike-recorder?srsltid=AfmBOoqrJ61zKkP71Q1D-XYUOH-uSpboO5RjRNCgdj-AMUjhS3rkyHu-)


## Setting up the arduino board .

The bioamp-exg pill is build to acuire EEG/EOG by default.

1. Connect the arduino board to the computer using the USB cable.
2. Open the Arduino IDE.
3. An option to install pachakge for Arduino uno r4 minima should pop up on the bottom left corner. Click on install.
4. Go to Tools -> Port-> COM3/COM4/COM5.
    - By default you should see the correct port option, if not unplug the usb cable and plug it back in, the correct port should show up.
    - Else you'll have to manually select the port.
        -- Tip: You can select each COM# port and go to Tools -> Serial Plotter to see the signal. The correct port will pop up the plotter, else it will show an error.

5. To record the signal, go to the github repository and download the arduino code. Open the code in the Arduino IDE.
6. Click on the upload button to upload the code to the arduino board.

## Configuring the BioAmp EXG Pill:

By default the bioamp pill is configured to read EEG/EOG signal. To change the configuration to read EMG/ECG signal make a solder joint on the bandpass filter. (as shown in the manual)
Follow the instructions in the manual or the website to acuire the signal.


## Recording EMG with the bioamp pill:

1. Connect the bioamp shield to the arduino board.
2. Connect the bioamp exg pill to the bioamp shield.
3. Connect the electrodes to the bioamp exg pill.
4. Open the arduino IDE create new Sketch of the correct code to record EMG from the github repo, upload the code to the arduino board.
4. Open the Serial Plotter in the Arduino IDE to see the signal.

## Multichannel recording:

By default you can record EEG in one channel and EMG in another. To record EMG in both, you need to make the solder joint on the bandpass filter of the bioamp pill.