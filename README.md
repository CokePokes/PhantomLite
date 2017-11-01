# PhantomLite
Phantom Lite for Snapchat on jailed devices. (Doesn't require jailbreak)

Last updated: 11/01/17 [Link will be always updated on this date]

```ruby
Changes in v2.7: (Directions: BUILD STRUCTURE KINDA CHANGED!)
-- Fixes connection & refresh errors for the time being

```

```ruby
Changes in v2.6: (Directions: BUILD STRUCTURE CHANGED!)
-- Snapchat 10.20.1.0 compatibility
-- Fixes connection & refresh errors for real this time

```

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
3. Download PhantomFiles_v?.?.zip file here: https://mega.nz/#!ZzZn3a7R!EGLzKWS01HhuRLVV8PGjgEN63jZJ1i-oHdf_fSTYE40
4. Rename decrypted Snapchat.ipa file to Snapchat.zip & unzip
5. Copy PhantomFiles_v?.?.zip to Payload>Snapchat.app & unzip
6. File structure should look like this:
```ruby
/Payload/
	/Snapchat.app/
		/Photon/
			photon.dylib
			CSub
			MoPub.bundle
			phlite.bundle
			Languages.bundle
			CLImageEditor.bundle
			MWPhotoBrowser.bundle
			CTAssetsPickerController.bundle
			
```
7. Open terminal and "cd" to the tools directory inside downloaded zip folder. Ex command: cd /Downloads/PhantomFiles/tools 
8. Run command: [optool](https://github.com/alexzielenski/optool) install -c load -p "@executable_path/Photon/photon.dylib" -t /Downloads/SnapchatCracked/Payload/Snapchat.app/Snapchat
9. Select Payload, iTunesArtwork/iTunesMetaData.plist if present, then right click & select compress
10. Install zip file with Cydia Impactor available here: http://www.cydiaimpactor.com

Enjoy!

Ps: Good luck!
