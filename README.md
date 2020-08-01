# unity3d-object-registry
<b>Why?</b>
<p>While learning to mod Minecraft a while back, I discovered that the game uses a registry where various elements of the game could be registered and then accessed from anywhere in the game's code. I liked the system and created this simple implementation for Unity3D. Obviously this registry is no where as complex as the one used in Minecraft's code, but it works just fine for the small projects and prototypes that I work on.</p>
<b>Tips</b>
<p>Make sure you only registry objects in Awake() and access them in <i>not</i> Awake() so that you don't end up trying to access a register before it's added. Obviously this is required, but it will keep you from confusion.</p>
