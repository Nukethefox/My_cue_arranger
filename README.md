I created this simple web interface to easily create tech scripts for my theater shows, and quickly edit them during rehearsals.
The online link is: https://nukethefox.github.io/My_cue_arranger/

It includes two "jspdf" files, so I could use the interface's features offline (I found that some theaters have local Wi-Fi for remote access to the sound desk, but not internet access).
You can download these three files and use them locally on your computer, without internet connection.

The idea is very simple: the interface lets you create cues, with their corresponding trigger and actions, reorder them as needed, and then export them as PDF.

Script Creation:
Use the "Trigger" field to indicate "when to perform the action."
Use the "Lights," "Audio," and "Video" fields to indicate "what action to perform when the trigger happens."
Use the "Scene" and "Subscene" fields to order the cues. NOTE! When you add a new cue, it will be automatically ordered by these numbers, but you can reorder them later using the arrows. (Personally, I like to match the scene number with the actors' script, and I use the subscene field just for internal management; for example, "I need to insert a cue between cues 6-2 and 6-3, so the new one will be 6-2.1")

Reordering cues: Just use the arrows in each cue.

During rehearsal:
Use the GO+/- buttons to highlight a cue instead of holding your finger on the screen to remember which cue are you in. You can use the dropdown menu to avoid pressing go multiple times in case you have to skip multiple rows at once.
You can edit any cue by double-clicking on the trigger, lights, audio, or video fields.

Save!
VERY IMPORTANT! Remember to export the JSON file so you don't lose your cues. You can re-import it later or if you switch devices.

Creating the PDF:
A PDF will be created with all the cues in their current order, and the scene numbers (the sub-scenes will not be included in the export because I found that they are usually a mess of numbers). 
The PDF will be formatted with alternating colors in the rows. It's designed this way for printing and use during the final show, so you can quickly see "okay, we are in the yellow row", if you need to look away from the paper (yeah, because during showtime you usually end up multitasking).
You can fill in the information fields (production, designer name, contact) and this will be included in the PDF, in case you need to send it to others (director...).

If you want to change the format of the final PDF, you have to edit the code on lines 340 to 400.
