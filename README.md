# The automator of the IPA extraction.

## Required: Install de App from the Apple Store, SSH with an iOS Device.

### Steps: Upload the ipa_extractor script to the device with scp or another uploader that you want and then execute the script file.

```shell
In your linux:
scp ipa_extractor root@device:/var/root

In your device shell command:
./ipa_extractor APPLICATION-HASH IPA-NAME or only execute the script and read the help message.
```
