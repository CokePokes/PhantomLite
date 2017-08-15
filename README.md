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

Ps: 01100001 01001000 01010010 00110000 01100011 01001000 01001101 00110110 01001100 01111001 00111001 01110100 01011010 01010111 01100100 01101000 01001100 01101101 00110101 00110110 01001100 01111001 01001101 01101000 01001110 01000100 01011010 01000011 01010110 01010101 01001010 01000011 01010011 01010101 01101011 01101000 01011010 01111010 01010010 01110000 01010001 01101100 01100100 01111000 01011000 00110000 01110000 01101111 01010101 01000101 01110100 01010000 01010001 01010110 01001001 01110100 01100101 01101011 01101100 01110011 01011010 01101101 01010010 01101101 01001110 01111010 01000010 01110110 01010101 01010101 01011010 01011010 01011010 01101011 01001010 00110010 01001111 01000111 01110100 01101101 01010110 00110011 01101100 01010011 01010011 00110011 01110000 00110010 01010001 01101011 01100100 01101111 01010100 01010001 00111101 00111101
