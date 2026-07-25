CAT'S LITTLE BOX OF GOODIES — how to add your own stuff
=======================================================

Everything lives in ONE folder: "cat-little-box".
- index.html  -> the website (open this to view it)
- assets/     -> put your photos, videos, voice notes, doodles, song covers here

HOW TO EDIT
-----------
1. Open index.html in a text editor.
2. Near the top of the <script> section you'll see:  const ITEMS = [ ... ]
   Each { ... } block is one card in the mailbox.
3. Change the text (title, teaser, body, caption) to whatever you want.
4. To add a photo/video/voice note/doodle:
   - Drop the file into this "assets" folder.
   - In index.html set  src:"assets/YOURFILENAME"
     e.g.  src:"assets/beach.jpg"

FILE TYPES THAT WORK
--------------------
- Photos / doodles : .jpg  .png  .gif  .webp
- Video            : .mp4  (best), .webm, .mov
- Voice notes      : .m4a  .mp3  .wav  .ogg
- Song             : either paste a Spotify/YouTube link in the "link" field,
                     OR add an audio file with  audio:"assets/song.mp3"

ADD / REMOVE CARDS
------------------
- To add a card: copy any { ... } block, paste it, edit it.
- To remove a card: delete its { ... } block.
- Item "type" must be one of:
     note   photo   video   voice   doodle   song   coupon

TO SHARE WITH CAT
-----------------
Easiest: zip the whole "cat-little-box" folder and send it to her — she opens
index.html on her phone or laptop. (Ask me if you'd like it put online with a
link instead; I can walk you through a free host like Netlify Drop.)
