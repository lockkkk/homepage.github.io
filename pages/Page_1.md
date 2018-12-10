## Free Virtual Piano System

The project - **Free Virtual Piano System** - derives from a whimsy dream in my childhood: in the magic world, people play the music everywhere, on the wall, on the table or even in the air. My goal was to translate hand movement on paper with printed piano keys into actual music.

The system contains a binocular camera, a paper with standard piano graphic and a computing platform, below is the system structure:


<img src="../src/System_structure.png" width="50%" />


I use Binocular Stereo Vision, Elliptical Skin Model, Block Matching algorithm, piano pattern recognition, and camera demarcation. Here is the algorithm flow:

<img src="../src/Piano.png "  width="100%" />

This is a demo of "Tinkle Tinkle Little Star~"
<video src="src/piano.mp4" width="320" height="200" controls preload></video>


Specially, this peoject have several interesting problem, let me share them with you:
- [x] The key pressing motion is slight, how to detect it?
- [x] If we keep pressing on the piano key, the piano will only ring once, how to realize this feature?
- [x] How to avoid the occlusion from hands when we detecting piano key?
- [x] ...

