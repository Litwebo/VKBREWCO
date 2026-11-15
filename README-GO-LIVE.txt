VK BREW CO - go-live guide
==========================
1. Make ONE new folder on your computer called VK-BREW-CO.
2. Unzip every part (core, frames1-6, vframes1-2). Each unzips to its own folder.
3. Drag EVERYTHING that comes out of the unzipped folders into VK-BREW-CO, so VK-BREW-CO contains:
   index.html, favicon.svg, og-image.jpg, robots.txt, _headers, netlify.toml, vercel.json,
   and the folders frames1 to frames6, vframes1, vframes2.
4. Go to https://app.netlify.com/drop and drag the VK-BREW-CO folder onto the page. You get a public link.
5. Add your own domain in Netlify > Domain management. Then edit index.html and change the og:image / twitter:image
   addresses to https://YOUR-DOMAIN/og-image.jpg so link previews show your picture.
To test on your computer first: open Terminal in VK-BREW-CO, run  python3 -m http.server  and visit http://localhost:8000
