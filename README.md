# Unity to Node audio transfer 2: client

Uses ![SimpleJSON](http://wiki.unity3d.com/index.php/SimpleJSON).

Broadcast commands to the script:

1. setUsername, String username
2. setPassword, String password
3. startSession, - **Initialises recogniser on the server, takes a few seconds**
4. defineWord, String word **Sets the current word**
5. startRec, - **start recording and uploading**
6. stopRec, - **stop recording and finish uploading. There's also an automatic timeout for stopping.**
7. endSession, - ***Not yet implemented*** **stops the recognition server for this user



## Read about the system in the ![server documentation](https://github.com/rkarhila/unity_to_node_audio_1_server)##

