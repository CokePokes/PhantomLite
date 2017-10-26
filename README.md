# PhantomLite
Phantom Lite for Snapchat on jailed devices. (Doesn't require jailbreak)

Last updated: 10/26/17 [Link will be always updated on this date]


```ruby
Changes in v2.5:
-- Snapchat 10.20.0.0 compatibility
-- Fixes connection & refresh errors
-- Fixes crash when uploading videos from cameraroll

```
```ruby
Changes in v2.4:
-- Snapchat 10.18.0.8 compatibility
-- Fixes crash when saving Snaps in stories search

```
```ruby
Changes in v2.3:
-- Fixes ability to save stories
-- Fixes image upload quality
-- New image editor
```
```ruby
Changes in v2.2:
-- Fixes startup crash on some devices. (No idea why this happens. Occurs on 5c AFAIK)
-- Fixes crash when uploading videos from library
-- Better UDID Validation. No longer requires user to add extra leading 0's to the ECID. 
```
1. Delete Snapchat if you have it installed
2. Find a decrypted copy of Snapchat you'd like to use. v10+
3. Download PhantomFiles_v?.?.zip file here: https://mega.nz/#!VrRG2bIC!UbN1V8kHvYgvYVP_sRb6bLcGfXy8hlsDlIBNr7_Tr5o
4. Rename decrypted Snapchat.ipa file to Snapchat.zip & unzip
5. Copy PhantomFiles_v?.?.zip to Payload>Snapchat.app & unzip
6. File structure should look like this:
```ruby
/Payload/
	/Snapchat.app/
		photon.dylib
		CydiaSubstrate
		/PhLite
```
7. Open terminal and "cd" to the tools directory inside downloaded zip folder. Ex command: cd /Downloads/PhantomFiles/tools 
8. Run command: optool install -c load -p "@executable_path/photon.dylib" -t /Downloads/SnapchatCracked/Payload/Snapchat.app/Snapchat
9. Select Payload, iTunesArtwork/iTunesMetaData.plist if present, then right click & select compress
10. Install zip file with Cydia Impactor available here: http://www.cydiaimpactor.com

Enjoy!

Ps: Good luck!
