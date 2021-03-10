# golfscorecard-vs

-vs version is related to the new Google IDE, which uses a different url than the legacy IDE.

PWA

  https://dmoritz10.github.io/golfscorecard-vs/index


To change manifest.json, use cdn.jsdelivr.net versioning:

After pushing new manifest.json:

  click on History
  right click on manifest.json
  create tag eg. v1.4
  
  In index.html
  <link rel="manifest" href="https://cdn.jsdelivr.net/gh/dmoritz10/golfscorecard-vs@v1.4/manifest.json">
  
