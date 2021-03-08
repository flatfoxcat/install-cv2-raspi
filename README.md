# install-cv2-raspi
### Install CV2 python on raspbian, comparatively quickly through miniconda
<br>
Download / Clone this repository on your raspberry pi<br>
Run the following commands from the raspiquickcv2 folder<br>
<code>sudo chmod +x mconda-dep.sh</code><br>
<code>./mconda-dep.sh</code><br>
After this command you will have to reboot your raspberry pi<br>
<code>sudo reboot</code><br>
After rebooting run these final commands from the getcv2-rpi folder<br>
<code>sudo chmod +x opencv.sh</code><br>
<code>./opencv.sh</code><br> <br>

Opencv will be installed in a miniconda v-env running python 3.4.3<br>
Activate > <code>source activate opencv</code> Deactivate > <code>source deactivate</code><br>
