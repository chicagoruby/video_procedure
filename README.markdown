ChicagoRuby Video Recording Procedure
=====================================

### Equipment List

* 	Mac w/ dedicated video card.
*		BoinxTV 1.6.x
* 	Firewire video camera.
* 	Lapel mic and wireless receiver.
* 	VGA2USB for capturing slide output.
* 	Headphones for monitoring audio output (optional).
* 	External hard drive for storing video (optional).

## BoinxTV Setup

Move the ChicagoRuby-NTSC.tvshow file to ~/Library/Application Support/Boinx/BoinxTV/Templates so that it appears in the template chooser. Complete the following steps to prepare BoinxTV for recording:

1. 	Save the template file using the ChicagoRuby-YYYYMMDD.tvshow
		naming convention.
2.	Open the Sources pane (bottom left corner of Boinx) and set proper input sources as follows:
	1.	Camera & Speaker Mic: Firewire camera for video device,
			Lapel mic for audio device. *(1)*
	2.	VGA2USB: VGA2USB for video device. *(2)*
	3.	Ambient Mic: Firewire camera (or a separate external ambient
			mic if available).
3.	Set the session date and session information by selecting on the Session Date
		and Session Name layers, respectively, and editing the content text.
4.	Set all required lower thirds by selecting the Lower Third layer and then selecting
		each individual lower third setting. In the settings pane under Content, set the Title and Subtitle.
5.	Select the Presenter layer. In the settings pane under Content, set Position to either Left or Right 
		depending on where the speaker will be standing relative to the projection screen.
6.	Click the headphones icon (upper right corner of Boinx) to enable playthrough
		through headphones for monitoring audio output.
	
*(1)* If you are receiving low audio levels from the lapel mic, go into the Sound preferences pane in OS X's System Preferences to adjust the input volume for the line-in input.

*(2)* If you connected the VGA2USB device after starting BoinxTV, you may need to close and reopen BoinxTV for it to appear. If the VGA2USB device is not available or not functioning with the speaker's computer, you can screen capture a VNC connection. An external monitor is recommended for this process. To setup the screen capture in BoinxTV, set the Presenter layer to use Screen Capture Source as Source B. In the Sources pane, select the Screen Capture Source to adjust the capture area.

## BoinxTV Operation

To begin recording a video, press the record button or Command+R. The title screen should be enabled when starting the recording. Leave the title screen displayed until event host introduces the speaker. This will allow announcements to be easily trimmed from the video while not requiring the title screen to be re-added in post-production.

During the recording, keyboard shortcuts can be used to toggle layers. If the shortcuts are not working, click on any random layer.

#### Title Screen

	T - Toggle title screen

#### Lower Thirds

	A - Lower Third 1
	S - Lower Third 2
	D - Lower Third 3
	F - Lower Third 4

#### Video/Presentation Views	

	J - Camera Only
	K - Camera/Presentation
	L - Presentation Only
	
#### Microphones

	R - Toggle ambient mic (for audience questions)
	
## Exporting and Transcoding

To end a recording, press the stop button or Command+R. Click "Close" on the "Export Your Recording" screen.