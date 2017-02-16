# SpectacleApp
Prototype Spectacle configuration app <br/>
moved from https://jsfiddle.net/N0rth/pLh72mj9/
<br/>
<h2>Browser Compatibility (anticipated)</h2>
How badly have I broken it for the big 5 browsers so far?<br/>
<table style="width: 539px; height: 223px; text-align: center;">
<tbody>
<tr>
<td style="width: 106.4px;"><img alt="Chrome" src="https://cloud.githubusercontent.com/assets/1609220/22127033/6d13ac28-de57-11e6-8b92-cc90a53a94ee.png"></td>
<td style="width: 107.2px;"><img alt="Firefox" src="https://cloud.githubusercontent.com/assets/1609220/22127030/6ac2b78e-de57-11e6-8e73-b7803c8bcce5.png"></td>
<td style="width: 108px;"><img alt="Opera" src="https://cloud.githubusercontent.com/assets/1609220/22127029/68fa0538-de57-11e6-935f-d84149a34193.png"></td>
<td style="width: 108px;"><img alt="Safari" src="https://cloud.githubusercontent.com/assets/1609220/22127028/66735210-de57-11e6-8e65-efccf6a05107.png"></td>
<td style="width: 108px;"><img alt="IE" src="https://cloud.githubusercontent.com/assets/1609220/22127022/636efad8-de57-11e6-994b-6d848b279e15.png"></td>
</tr>
<tr>
<td style="width: 106.4px;">&#10004;<br/><small>Please Use Chrome</small></td>
<td style="width: 107.2px;">&#10004;<br/><small>Polyfills fixed UI</small></td>
<td style="width: 108px;">&#10004;<br/><small>Opera is Fine Too</small></td>
<td style="width: 108px;">&#10071;<br/><small>File Saving Bug</small></td>
<td style="width: 108px;">&#10006;<br/><small>Are you kidding?</small></td>
</tr>
</tbody>
</table>
<!-- DivTable.com -->
<br/>
<h2>Google Drive Integration</h2>
<img alt="GoogleDrive" src="https://cloud.githubusercontent.com/assets/1609220/22617684/48c1e0a0-ea88-11e6-9693-6db3abf8d2e1.png">
<br/>
Sharing projects on Spectacle is enabled through integration with Google Drive™<br/>
<small>Google Drive is a trademark of Google Inc. Use of this trademark is subject to Google Permissions.</small>
<br/>
<h2>Social Sharing Meta Tags</h2>
Sharing projects on social media should result in rich, attractive links:<br/><br/>
<strong>Twitter</strong><br/>
![spectaclecard](https://cloud.githubusercontent.com/assets/1609220/22907766/0a570d90-f208-11e6-8cd2-4bdb0f095134.PNG)
<br/>
<strong>Facebook</strong><br/>
![spectacleog](https://cloud.githubusercontent.com/assets/1609220/22907767/0a62775c-f208-11e6-81ac-6e929c90d21f.PNG)
<br/>
Other scrapers, such as Pinterest's "Rich Pin" system, will accept Facebook Open Graph tags as well.
<br/>
<h2>File Tree</h2>

* index.html - launch page<br/>
* /img/ - image assets <br/>
* /icons/ - "add to homescreen" icons<br/>
* gangnam.css - stylesheet (get it?)<br/>
* logic.js - javascript for application logic<br/>
* manifest.json - chrome app icon manifest<br/>
* favicon.ico - you know what it is<br/>
* FileSaver.js - https://github.com/eligrey/FileSaver.js<br/>
* spectrum.js - http://bgrins.github.io/spectrum/<br/>
* spectrum.css - http://bgrins.github.io/spectrum/<br/>
* LICENSE - MIT License<br/>
<br/>
<h2>Development Roadmap</h2>
<strong>Navigation and File Manipulation</strong><br/>
☑ Frontpage navigation<br/>
☑ Project name pane<br/>
☑ Project Info module<br/>
☑ Module Prototypes<br/>
☑ Module sorting functionality<br/>
☑ Module delete functionality<br/>
☑ Module addition menu <br/>
☑ Module addition functionality <br/>
☑ Dynamically save textarea values to Document object<br/>
☑ Action prototypes <del>(development documented here: https://jsfiddle.net/N0rth/j29z7244/)</del><br/>
☑ Action addition menu <del>(development documented here: https://jsfiddle.net/N0rth/evzkmvk6/)</del><br/>
☑ Action addition functionality <del>(development documented here: https://jsfiddle.net/N0rth/evzkmvk6/)</del><br/>
☑ Action delete functionality <del>(development documented here: https://jsfiddle.net/N0rth/j29z7244/)</del><br/>
☑ Report action lists to board elements<br/>
<del>☑ Save image as base64 to document object</del> *(Image attachment removed)*<br/>
☑ Save canvas element base64 encoded<br/>
☑ Retreive canvas element base64 decoded<br/>
☑ Periodic Autosave<br/>
☑ Autoretrieve localSave on pageload <br/>
☑ Fix scaling for iOS browsers <br/>
☑ Configuration Upload Menu <br/>
☑ Google Drive API integration <br/>
<strong>Logic and Configuration <del>\*\*Need Final Firmware\*\*</del></strong><br/>
☑ Generate Real Config <br/>
☑ Configuration Upload functionality<br/>
☑ Graphics review with Pete H.<br/>
<strong>Web Dressing</strong><br/>
☑ iOS "Add to Homescreen" icons <br/>
☑ Chrome "Add to Homescreen" icons and manifest <br/>
☑ Favicon *(Get one that looks good from Pete)*<br/>
☑ Windows Tile icons <br/>
☑ El Capitan Safari mask icons <br/>
☑ Pass Favicon Checker ([test results](http://realfavicongenerator.net/favicon_checker?protocol=https&site=npoole.github.io%2FSpectacleApp%2F#.WKJFyzsrJPb))<br/>
☑ Facebook Open Graph meta tags <br/>
☑ Twitter Card meta tags <br/>
☐ Validate and Apply Social meta tags <br/>
<strong>Fun Shit</strong><br/>
☑ Random Adjective default boardname generator <br/>
☑ Random Adjective default project name generator <br/>
<strong>B-B-B-BONUS ROUND!!! (Deploy)</strong><br/>
☐ Migrate this repo to SparkFun Pro GitHub Account<br/>
☐ SparkFun CNAME Record<br/>
☐ Spectacle Google Account<br/>
☐ Register New Spectacle Google Drive Keys<br/>
