# PhantomLite
Phantom Lite for Snapchat on jailed devices. (Doesn't require jailbreak)

1. Delete Snapchat if you have it installed
2. Find a decrypted copy of Snapchat you'd like to use. v10+
3. Download PhantomFiles.zip file here: https://mega.nz/#!EmonESLZ!My9QWLUqtR3feJ9g3SZYplbNAYjCwSJ_YLvsFYf1OtY
4. Rename cracked Snapchat.ipa file to Snapchat.zip & unzip
5. Copy PhantomFiles.zip to Payload>Snapchat.app & unzip
6. File structure should look like this:
```ruby
/Payload/
	/Snapchat.app/
		Sys.dylib
		/PhLite
		/libloader/
			genghisChron.dylib
			CSub
```
7. Open Payload>Snapchat.app>Snapchat with a Hex editor (iHex [FREE] from Mac Store works)
8. Replace all occurrences of string: "/usr/lib/libSystem.B.dylib" with: "@executable_path/Sys.dylib" & save changes
9. Select Payload, iTunesArtwork/iTunesMetaData.plist if present, then right click & select compress
10. Install zip file with Cydia Impactor available here: http://www.cydiaimpactor.com

Enjoy!
