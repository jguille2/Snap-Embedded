# Snap! Embedded

Notes to document embedded possibilities for Snap!

and a space for testing!

## Opening xml projects with #open

Only two rules here:
- **Https**. If the main url (snap! machine) is under _https_ then, the _xml_ server must be also under _https_
- **CORS** If domains are different, _xml_ response needs the header `"Access-Control-Allow-Origin: *"`

Example:
(https://snap.berkeley.edu/snapsource/snap.html#open:https://www.robolot.online/sn/Asteroids.xml)

Note: On current state (_Snap!5.4.5_ and also _Snap!6beta_) we can't use other _hashs_ like _#run_ or _#present# with these _xml calls_ 
Nor we can't use option flags like _embedMode_, _editMode_, _noRun_, _hideControls_...


| :exclamation:  This will be checked but we don't need this if we control our embedded Snap! from JS code.   |
|-------------------------------------------------------------------------------------------------------------|

