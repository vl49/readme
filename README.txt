In this project I simulated an intelligent video surveillance system that distinguishes some behaviours of people in a virtual environment. 
I designed this environment using 3D Blender software.
This project is based on two open source softwares: Toolkit for Sensing People in Spaces (TSPS) 
(http://www.tsps.com) and OpenTSPSReceiver. The second one combines TSPS with Unity3d Game Engine 
(http://www.unity3d.com)
Unity3DTSPS's folder contains the myOpenTSPSRec, based on OpenTSPSReceiver, which projects onto a platform in Unity 3D what it receives from TSPS.
I adapted the virtual environment to the platform. 
You can scale and change position to the virtual environment, based on the view of the camera,
if you change the position and scale in Unity, choose the Game Object platform and copy the same values in the csOpenTSPSListener.cs
Finally, it will be necessary to adapt the virtual environment.
In addition to this, the application environmentOverview allows us to view 
the virtual environment via an avatar that is moving through space.
In order to use the project, you need to download TSPS-1.3.6, upload the video provided in the videos folder, and set the basic parameters(threshold:69.7, type of differencing:dark on  light, minimun blob size:0.6). 