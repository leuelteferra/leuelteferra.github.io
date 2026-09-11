LEUEL'S PERSONAL SITE — HOW TO USE
==================================

WHAT'S HERE
  index.html    About page (this is your homepage)
  collage.html  Photo collage grid
  albums.html   Album covers grid
  misc.html     Links page

All styling lives inside each HTML file (in the <style> block near the top),
so every page works on its own — just double-click any file to preview it
in your browser.

EDITING CONTENT
  1. Open a file in any text editor (VS Code, Notepad, TextEdit).
  2. Text lives between the <main> tags. Edit it directly.
  3. Photos: put your image files in this same folder (or an /images
     subfolder) and change each src="..." to point at them.
  4. The Amharic signature at the bottom is the text ሉኤል — change it
     to whatever you want (your full name, a phrase, etc).

PUTTING IT ONLINE (FREE)
  Easiest path — GitHub Pages:
  1. Create a free GitHub account and a new repository named
     yourusername.github.io
  2. Upload these files to it (drag and drop works on github.com).
  3. Your site is live at https://yourusername.github.io within a minute.

  Custom domain (like leuel.com):
  1. Buy the domain (~$10/yr on Namecheap or Cloudflare).
  2. In the GitHub repo: Settings -> Pages -> Custom domain -> enter it,
     then follow GitHub's DNS instructions at your registrar.

  Alternative: drag the folder into netlify.com/drop — instant free hosting.
