Extending: https://elevenlabs.io/docs/dubbing/studio
### Using the Dictation Feature for Speech-to-Speech (STS) in ElevenLabs

The Dictation feature in ElevenLabs allows you to record your voice over _an audio clip with or without an existing audio source_. Here’s a step-by-step guide on how to use this feature:

#### Accessing the Dictation Feature

1. **Select an Audio Clip**:
   - Click on an existing audio clip in your project to highlight it. (You may want to check "Creating an Empty Audio Clip" at the end.)
   - Ensure you have the desired audio clip selected before proceeding.

2. **Locate the Dictation Feature**:
   - Scroll down the right pane to find the Dictation section.
   - You will see a round microphone icon for recording and the clip length information.
   
     ![Dictation Feature Location](https://github.com/frknltrk/elevenlabs-docs/blob/main/picture_1.png)

#### Recording with Dictation

3. **Start Recording**:
   - Click the round microphone icon to start recording.
   - The browser will prompt you for microphone permissions the first time you use this feature. Grant the necessary permissions.
   - Recording will commence immediately and will automatically stop when the clip length is reached.

4. **Stop Recording Early**:
   - If you wish to stop the recording before the clip ends, click the square stop icon.

     ![Dictation Feature Location](https://github.com/frknltrk/elevenlabs-docs/blob/main/picture_2.png)

#### Post-Recording Options

5. **Review Your Recording**:
   - After finishing the recording, you will see three buttons: Play, Delete, and "Generate Audio (STS)".
   - Use the Play button to listen to your recording.
   - If you are not satisfied with the recording, you can delete it by clicking the Delete button.
  
     ![Dictation Feature Location](https://github.com/frknltrk/elevenlabs-docs/blob/main/picture_3.png)

6. **Generate Final Audio**:
   - Click the "Generate Audio (STS)" button to finalize your recording.
   - If this button is unclickable, it indicates that the associated script box is empty. Please type in the transcript manually in the associated script box to enable the button.
  
     ![Dictation Feature Location](https://github.com/frknltrk/elevenlabs-docs/blob/main/picture_4.png)

#### Extra

- **Creating an Empty Audio Clip**:
   - To create an empty audio clip without an existing audio source, first create a new Voice-Over Track.
   - Left-click somewhere on the track where you want to place the new audio clip.

#### Troubleshooting

- **Generate Audio (STS) Button Unclickable**:
  - Ensure the associated script box is not empty. Enter the transcript manually to activate the "Generate Audio (STS)" button.

By following these steps, you can effectively use the Dictation feature in ElevenLabs for dubbing or creating voice-overs.
