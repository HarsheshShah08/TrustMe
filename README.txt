TrustMe! — Static parody search

This is a kid-friendly joke search page. It uses small phrase templates in
index.html to turn a visitor's question into a silly answer. It does not call
Gemini or any other service, require a key, or send questions off the device.
The answers are deliberately made up and are not real advice.

Try it locally
--------------

Open index.html in a browser, or run this in the project folder:

  python3 -m http.server 8000

Then visit http://localhost:8000/.

Publish with GitHub Pages
-------------------------

1. Put the files in a GitHub repository. The folder should contain index.html
   at its top level.
2. In the repository, open Settings > Pages.
3. Under Build and deployment, choose Deploy from a branch.
4. Choose the main branch and /(root), then save.
5. GitHub will show the public site URL on the Pages settings screen.

No API key or server setup is needed. The site works as a static GitHub Pages
site. The older trustmev2.html and trustmev3.html URLs forward visitors to
index.html.

Safety
------

TrustMe is a parody. It shows a reminder to ask a trusted adult or qualified
professional when a question appears to involve serious or sensitive topics.
