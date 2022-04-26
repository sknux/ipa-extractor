# The automator of the IPA extraction.

## Required: SSH with an iOS Device.

### Steps: Upload the ipa_extractor script to the device with scp or another uploader that you want and then execute the script file.

```shell
In your linux:
scp ipa_extractor root@device:/var/root

In your device shell command:
./ipa_extractor
```
