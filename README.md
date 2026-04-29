with this .html file you can delete pads from sequences 
by uploading the preset.xml file into the webbrowser app
and select the pads and sequences you want to delete. 

remember to make a backup of your preset and when exporting 
the new preset_modified.xml change it back to preset.xml. 

USAGE:
  1. Drag & drop your preset.xml into the app (or click to browse)
  2. Select a sequence (S1-S16) from the left panel
  3. Click pads to select which ones to clear
  4. Click "Delete selected notes"
  5. Click "Download XML" to save the modified preset file

NOTE: If Windows Defender shows a warning when opening the .hta,
click "More info" -> "Run anyway". This is normal for unsigned apps.

⇄ Swap pads mode — switch to it with the tab at the top of the editor:

Within this sequence — click Pad 1, then Pad 3, and 
their note events swap channels with each other

With another sequence — 
pick a target sequence from the dropdown, click a pad in the 
current sequence, then click a pad in the grid — the events 
move between sequences and update their pad assignments

The first selected pad gets a blue "1st" badge so you always 
know what's pending. You can cancel at any time with 
the Cancel button, or just click the same pad again to deselect.

The swap now moves the full pad — both the sequence notes and the audio sample. 

Sequence notes — all 16 sequences are updated at once, 
so if Pad 1 has notes in S1, S3, and S7, they all get 
reassigned to Pad 2's channel (and vice versa).

Audio sample + settings — the row/column attributes of the
sample cells are swapped, which moves the entire 
sample definition (filename, gain, pitch, envelope, filter, 
LFO, slices — everything) to the other pad's slot.

There are two checkboxes in swap mode so you can 
choose to swap just the notes, just the sample, 
or both together.
