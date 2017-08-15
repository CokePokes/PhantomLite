# PhantomLite
Phantom Lite for Snapchat on jailed devices. (Doesn't require jailbreak)

Last updated: 08/15/17 (New file structure/directions!)

1. Delete Snapchat if you have it installed
2. Find a decrypted copy of Snapchat you'd like to use. v10+
3. Download PhantomFiles_v?.?.zip file here: https://mega.nz/#!hroCwD6B!zuJOEmHdJBf3gHPLoVoG_a53hOw79CGmQn1-T4vJCP0
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

Ps: 01000101 01101001 01101011 00100000 11000100 10101111 00100000 01110011 01100001 01110110 01101111 00100000 01101011 01100001 01101101 01100010 01100001 01110010 11000100 10101111 00100000 01101001 01110010 00100000 01100101 01101001 01101011 00100000 01110000 01110010 01101001 01100101 00100000 01101101 01101001 01100101 01100111 01101111
