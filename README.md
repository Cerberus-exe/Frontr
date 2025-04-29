# Frontr
A simple front detection executable for your plural system.
Hi, thank you for choosing our little program!

The build is currently ALPHA 0.1.3 - expect some bugs!

-----------------------------------------------------------

UPDATE REPORTS

- Fixed window ratio - now you don't have to manually resize them
- Added ability to search using multiple tags in a single field, seperated by commas
- Fixed issue where uncommon tags did not narrow down the alters
- Fixed .json file path - now saved alters are persistent and show up when you close and reopen the program

KNOWN ISSUES

- Unable to use multiple tags in a single field (such as two moods, two triggers etc)

-----------------------------------------------------------

ABOUT THE PROGRAM

Frontr was made as an alter/headmate fronting detection system based on a few keywords. These keywords are divided into three categories; mood, triggers, and interests. Filling out an alter profile with their name as well as common moods, fronting triggers (positive or negative), and hobbies/interests will help narrow down who might be fronting in your system, if you may be confused or blurry. This also helps determine who might be co-conscious or exerting passive influence upon the fronter.

We are aware of some issues, such as the inability to search using multiple tags in one field. We're working on this! Other than that, please report bugs to https://x.com/cerberus27_exe

-----------------------------------------------------------

HOWTO

FIRST TIME SETUP

1. OPEN THE .EXE
2. CLICK "Open Alter Editor"
3. FILL OUT THE FIELDS
4. CLICK "Add Alter"

To add more alters, repeat steps 3 and 4 until you are finished. At this point, simply close the Alter Editor window.
MANUALLY ADDING ALTERS: You can choose to manually add alters directly to the .json file by opening it in an editor of your choice (We recommend Code Writer) and editing the following code:

[{"name": "NAME", "moods": ["MOOD", "ANOTHER MOOD"], "triggers": ["TRIGGER", "ANOTHER TRIGGER"], "interests": ["INTEREST", "ANOTHER INTEREST"]}]

Edit the text which is in CAPS LOCK.

Keep in mind these ARE case-sensitive!!!

DETECTING ALTERS

Fill out the fields using ONE tag per field (will be able to add multiple in the future), then click "Detect Fronter." Possible fronters will be printed below the button!
