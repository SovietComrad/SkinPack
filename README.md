# MUST READ BEFORE USING!!

Hello Comrade, and thank you for looking into this Skin Pack we have provided for you to blend in and immerse youself into our Soviet society. There are some things you must know before you try to use this, as well as some rules.

# There are some key things you MUST do in order for this to work.

STEP 1: Download the above SkinPack to your computer (REMEMBER WHERE YOU SAVED IT TO)

STEP 2: After it has downloaded, click on the download file and it will open in File Explorer.

STEP 3: KEEP THE FILE EXPLORER OF THE DOWNLOAD OPEN. Go to the bottom left of your screen to the Windows search (the Cortana search that says "Type here to search") and type in "%APPDATA%" (without the quotation marks!) and a file should appear in the results. Click it and another File Explorer will pop up. (KEEP BOTH OPEN, YOU WILL BE DRAGGING FROM THE DOWNLOAD.)

STEP 4: In the APPDATA FILE EXPLORER you just searched and opened, you will see files in the explorer. Above you will see this: 
"<<Users> -user- >AppData>Roaming"

STEP 5: Click on AppData, this show you a new set of files: Local, LocalLow, and Roaming

STEP 6: Pay close attention, we will be clicking through multiple files:

Local >> Packages >> Microsoft.Minecraft.. >> LocalState >> games >> com.mojang

STEP 7: You will now have to do some basic copy and pasting in order for this to work. (Try to stay focused here!)
Go to the OTHER File Explorer opened (The one with the skin pack you downloaded from here!). You will see a file named "manifest.json"
Click on it. (If asked what to use to open click NOTEPAD)

STEP 8: You will see some code, DON'T PANIC. We're not going to be doing any high tech coding, we're just going to copy and paste some things into here.
Go to https://uuidgenerator.net/version4, and click the "Copy" button.

In the manifest.json you will see this code:

{
  "header": {
    "version": [
      1,
      0,
      0
    ],
    "name": "Soviet_SkinPack",
    "uuid": "d671782a-61cf-4566-9706-05bf102c175e"
  },
  "modules": [
    {
      "version": [
        1,
        0,
        0
      ],
      "type": "skin_pack",
      "uuid": "261bab37-4b43-4e58-aab4-59c580ce3b0b"
    }
  ],
  "format_version": 1
}


STEP 9: WE WILL BE REPLACING THE "uuid" WITH NEW ONES WE COPIED FROM THE WEBSITE.
