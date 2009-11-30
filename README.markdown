ChicagoRuby Video Recording Procedure
=====================================

### Equipment List

* 	Mac with BoinxTV 1.4.x.
	Dedicated video card w/ large display highly recommended.
* 	Firewire video camera.
* 	Lapel mic and wireless receiver.
* 	VGA2USB device (optional).
* 	Headphones for monitoring audio output.
* 	External hard drive for storing video (optional).

## BoinxTV Setup

Begin by opening ChicagoRuby.tvshow file in BoinxTV. You can optionally copy this file to ~/Library/Application Support/Boinx/BoinxTV/Templates. Complete the following steps to prepare BoinxTV for recording:

1. 	Save the template file using the ChicagoRuby-YYYYMMDD.tvshow
	naming convention.
2.	Open the Sources pane and set proper input sources as follows:
	1.	Camera & Speaker Mic: Firewire camera for video device,
	Lapel mic for audio device.
	2.	VGA2USB: VGA2USB for video device.
	3.	Ambient Mic: Firewire camera (or a separate external ambient
		mic if available).
3.	Set the session date and session information in the Session Date
	and Session Name layers, respectively. Double check for typos!
4.	Set all required lower thirds. Double check for typos!
	
If the VGA2USB device is not available or not functioning with the speaker's computer, you can screen capture a VNC connection. An external monitor is recommended for this process. To setup the screen capture in BoinxTV, set the Presenter layer to use Screen Capture Source as Source B. In the Sources pane, select the Screen Capture Source to adjust the capture area.

## BoinxTV Operation

To begin recording a video, press the record button or Command+R. Begin the recording a few seconds before signaling the announcer or speaker to allow display of the title screen. During the recording, the following keyboard shortcuts can be used to toggle layers:

#### Title Card

	T - Toggle title card

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
	
## Exporting and Compressing

To end a recording, press the stop button or Command+R. BoinxTV will export the recording in Apple Intermediate Codec format. This process may take a few minutes depending on the length of the recording.

Following the initial export, the video must be transcoded using H.264 before uploading to Vimeo. This can be performed within BoinxTV by selecting the H.264 QuickTime preset. Note that this process may take up an hour or more depending on the length of the recording. You can perform this process at a later time by returning to BoinxTV, selecting Export Your Recording from the File menu, and choosing the raw Apple Intermediate Codec video as the source.

The conversion to H.264 can also be performed using other tools. VisualHub generally works well if you're lucky enough to have obtained a license before the developer closed up shop. Unfortunately, Handbrake will not convert from Apple Intermediate Codec.

## Uploading to Vimeo

The completed video in H.264 format should be uploaded the ChicagoRuby Vimeo account. When uploading, it should be added to the ChicagoRuby video channel.