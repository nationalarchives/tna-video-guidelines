# Editing with Adobe Premiere

## Starting up

New project → New folder
Name the project
Capture → HDV 
Sequence presents →  HDV50i (top option) ‘i’ is for interlacing	
File → Capture (to upload from camera)

Says ‘previewing on camera’ while it’s capturing. It’s a live capture, so takes the same amount of time as the length of video to upload. 

Scratch disks → ‘same as project’, so stores all project files in the folder
(These files were stored in ‘My documents’ on the laptop, but we were working directly off the footage on the external hard drive. In the future, work on multimedia PC, but back up on external hard drive - do not store it on a network drive)

→ New sequence This is the timeline – you can have different sequences in the same project for different versions, for instance if you wanted a version with and a version without subtitles. 
As you export a sequence, the quality decreases.

→ Import. Double click below sequence 1 (top left box) to import a file – or go to the File menu and select import. You are technically connecting to the files, as media must be connected.  You can import more than one file at once. 

Double click on the file name, brings up a larger picture in the Source window. 

## Editing 

There are several windows in the Premiere screen. The yellow outline shows which window is currently selected, and therefore where your transport controls will work. 

Make the Source (original clip) and Program (timeline edit) windows are about the same size on the screen. 

Where you see a number near your footage with a yellow underline, that means you can double click on this and enter a time to jump to: 
10. (10 seconds), 5.05 etc

Otherwise you can position your cursor by hand, by clicking on the timeline ruler.

### To edit:

Zoom in lots. You can drag the scale at the bottom to zoom in and out, or simply use + or –

Create bins (folders) for your different sections of footage. Right-click in the project window to create a new bin. Double click on it to re-name. If this doesn’t seem to be working, try stretching out the window horizontally. 

Mark in and out markers to define the area you want to keep. You can hit these while playing. 

Create clips to add to your bins. Have the correct bin selected→ click on the Source window → go to Clip menu at the top → make sub-clip. Give it as descriptive a name as possible. 

Useful to use code for different types of shot too, so within a ‘books and volumes’ bin, you may have ‘opening book master’, ‘opening book CU’ (close up), ‘opening book OTS’ (over the shoulder).

Drag the selected footage down onto the timeline (video track 1) to add it in. Alternatively, you can use the ‘overlay’ button. Leave short gaps between your clips initially. You can still drag the sides of your footage in the timeline to make it a little longer or shorter, as it will add a frame or two from the source file back in. So don’t panic if cut too short at first! 

### Tricks and tools

If you cut out a section and there is a gap in your timeline, right-click in the space and ‘ripple delete’ to close the gap. 

Alternatively, you can use in and out markers and ‘Extract’ the section using a button in the top right (which affects other tracks as well), or you can ‘Lift’ the section out – this is safer as doesn’t delete other audio for that section. 

Alt temporarily unlinks audio and video. 

If you want to move lots of slices along at once, put your cursor on the timeline and use the track select tool on the bottom right to highlight everything after that point, and drag along. 

To split a clip, use the Razorblade tool, bottom right. You can then move these sections along the timeline independently.

### Adding transitions

To make the footage run smoothly and ease the transition between different clips. You can also edit the length of the transition. 

Box in the bottom left – Video transitions 
Dissolve→ Dip to black 
Dissolve→ Cross dissolve

Simply select and drag onto the timeline over the join of the two clips. 

### Adding and editing audio

Make sure your hard drive is plugged in, if your audio files are stored on there – the program links to a reference for the audio, the files aren’t in Adobe Premiere. 

There are two audio tracks in Premiere – Stereo, for music, and Mono for speaking audio. 

Only use royalty-free music, such as our podcast intro and outro.

Right-click in the project window → ‘Import files’
Press Ctrl down to select multiple files at once
Drag and drop the audio into the appropriate audio track on the timeline to add it to a project

In the Premiere timeline, move yellow line up in an audio track if you want to make a sound louder. Or hold the control key and make points in yellow line to make the noise peak (or drop) at a certain point.

Can also copy and paste attributes within the timeline here.   

### Adding subtitles

Right click on the project window, in the top left, where all the files you are working with are listed. 

New Item → Title 
Title → New title → Default still

In the title editor, type what you want to say, select your desired size and font, then close it when you’ve finished - it automatically saves your changes. Now, your newly created title should appear in the project window, just like any of your video clips, or music clips would (it places the titles it where selected in the list, as with the clips). 

To superimpose it over the video, click and drag it from the project into your timeline. Drop it into the ‘video track 2’ or ‘video track 3’ slot. You can put it under any video track, as long as your video isn't already there. It would overwrite your video and appear as if it was an ordinary title with a black background. 

Once you have created a subtitle, the next time you can select ‘New title based on current title’ in the title editor – the T symbol in the top left. This will retain the size and font. 

If you need to amend your font size, ensure the text tool is selected in the left-hand toolbar and amend on the right. We have used 70% text size in the document handling video. 

If you need to amend the size or position of your text box or background, select the arrow symbol at the top of the toolbar and click on the area you wish to amend. 

## Adjustments

### Interlacing

Each frame (1/25th of a second) is made up of two images (odd and even lines) – these are taken 1/50th of a second apart, so there can be slight blurriness. 

You need to de-interlace footage for the web, though this ends up halving the resolution – we need to make it progressive – i/P. This is what modern TVs are trying to do.

You can de-interlace in Premiere or later in the Adobe Media Encoder. 

### Colour correction 

Effects tab → Colour correction → Fast CC

While in the clip you want to correct, go to effect controls in the top Source window tab. 

Scroll down to the bottom of this and go to the contrast scale – always contrast first. Input levels scale – adds more black in.

Next you can drag your cursor around the colour wheel in the opposite direction to the predominant colour (eg if the picture is too blue, move towards the orange). Show a split view to see both the before and after colour. You can copy this once and paste it onto all front shots etc – ‘paste attributes’ from one clip to the next. 

## Exporting 

Select your ‘work area’ at the top of the timeline with arrows and press return to render the files within the ruler area. 

If you make any changes after this, you will just need to render those sections that you have amended. 

Filming is in 1920px x 1080px (HD) at 16:9 ratio. You need to create a H.264 codec formatted video file. Please see [technical specs](file-output.md).

In Premiere:

File → Export → Media
Export settings screen:
Format: H.264
Preset: YouTube HD 1080p 25

Click on **Output Name** and select the location where you want the file saved and change the file name if you choose. Then click **Export**.
