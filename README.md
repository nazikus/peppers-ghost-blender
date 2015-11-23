# Pepper's Ghost Blender


VVVV patch processing video in real-time for creating [Pepper's ghost](https://en.wikipedia.org/wiki/Pepper%27s_ghost) illusion with a reflective prism and a digital screen.

Currently its processes video stream from available cameras and does not remove background yet.

![patch screenshot](./Pepper's Ghost Mask.png)
### Usage

Plenty of instructions on how to make such reflective prysm (pyramids) are available on the web with keywords "[homemade 3d hologram](https://www.google.com.ua/?gfe_rd=cr&ei=jj9SVqT6BOz37gTDsoG4Bg&gws_rd=ssl#q=homemade+3d+hologram))". However, naming is misleading since it has nothing to do with actual [holography](https://en.wikipedia.org/wiki/Holography). Its just an optical illusion of seeing [virtual image](http://neon-society-electronics.com/wp-content/uploads/2013/04/virtual_reflection.jpg).


You either connect a secondary display to your PC and put prysm onto horizontally placed display. Or you can stream generated video to your remote screen device (tablet, mobile) by creating a secondary virtual display and connecting to it via mobile using VNC client. 

I'm using [TightVNC server](http://www.tightvnc.com/licensing-tvnserver.php) for creating and sharing virtual display. Any mobile VNC client can connect to your virtual display then.