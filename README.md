# PhantomLite
Phantom Lite for Snapchat on jailed devices. (Doesn't require jailbreak)

Last updated: 08/17/17 (New file structure/directions!) [Link will be always updated on this date]
Version: 2.1

1. Delete Snapchat if you have it installed
2. Find a decrypted copy of Snapchat you'd like to use. v10+
3. Download PhantomFiles_v?.?.zip file here: https://mega.nz/#!d2wVCL6C!ecH620b_oW3XB8BejOFlHtuKLn8KJc1_-ovhAlbRwTo
4. Rename decrypted Snapchat.ipa file to Snapchat.zip & unzip
5. Copy PhantomFiles_v?.?.zip to Payload>Snapchat.app & unzip
6. File structure should look like this:
```ruby
/Payload/
	/Snapchat.app/
		genghisChron.dylib
		CydiaSubstrate
		/PhLite
```
7. Open terminal and "cd" to the tools directory inside downloaded zip folder. Ex command: cd /Downloads/PhantomFiles/tools 
8. Run command: optool install -c load -p "@executable_path/genghisChron.dylib" -t /Downloads/SnapchatCracked/Payload/Snapchat.app/Snapchat
9. Select Payload, iTunesArtwork/iTunesMetaData.plist if present, then right click & select compress
10. Install zip file with Cydia Impactor available here: http://www.cydiaimpactor.com

Enjoy!

Ps: MDExMDEwMDAgMDExMTAxMDAgMDExMTAxMDAgMDExMTAwMDAgMDExMTAwMTEgMDAxMTEwMTAgMDAxMDExMTEgMDAxMDExMTEgMDExMDExMDEgMDExMDAxMDEgMDExMDAxMTEgMDExMDAwMDEgMDAxMDExMTAgMDExMDExMTAgMDExMTEwMTAgMDAxMDExMTEgMDAxMDAwMTEgMDAxMDAwMDEgMDExMDAxMTEgMDExMTAwMTAgMDExMTEwMDAgMDExMDEwMTAgMDEwMDAwMDEgMDEwMTAwMDEgMDExMTAwMTAgMDEwMTEwMTAgMDAxMDAwMDEgMDExMTAwMTEgMDExMTAxMDAgMDExMDAwMTEgMDExMDEwMDAgMDExMTEwMDEgMDExMTAxMTEgMDExMTAxMDEgMDExMDExMDEgMDExMTEwMDAgMDExMTAxMDAgMDEwMDAxMTAgMDAxMTAxMDEgMDEwMDEwMDEgMDExMDEwMTEgMDExMDEwMDAgMDExMTAxMDAgMDExMTAwMDEgMDExMTAxMDAgMDEwMTAwMDEgMDExMTEwMTAgMDEwMTEwMDEgMDEwMDExMTEgMDEwMDAwMTEgMDEwMTAxMDAgMDEwMDAxMTEgMDEwMDEwMTAgMDExMTAwMTEgMDAxMDExMDEgMDEwMTAxMDEgMDAxMDExMDEgMDEwMDExMTEgMDExMDAwMTAgMDExMTAxMDEgMDExMDEwMTAgMDEwMDAxMDAgMDExMDAxMTAgMDEwMDExMDAgMDEwMDAxMDEgMDExMDAxMDAgMDEwMTAxMDEgMDEwMTAxMDEgMDExMTEwMDAgMDEwMTAwMDE=
