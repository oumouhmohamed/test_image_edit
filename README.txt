VOICE INVITATION EXAMPLE

1. Keep all files in the same folder.
2. Double-click index.html to test it.
3. Click the black speaker button to hear the sample sound.
4. Replace voice.wav with the child's real recording.

If your recording is MP3:
- put voice.mp3 in the folder
- change:
  <source src="voice.wav" type="audio/wav">
  to:
  <source src="voice.mp3" type="audio/mpeg">

To give customers one normal web link, upload the folder to Netlify, GitHub Pages, or Cloudflare Pages.
Google Drive can store the files, but it is not ideal for hosting the HTML as a live webpage.
