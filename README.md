# The automator of the IPA extraction.

## Required: Install de App from the Apple Store, SSH with an iOS Device with Jailbreak.

### Steps: Upload the ipa_extractor script to the device with scp or another uploader that you want and then execute the script file.

```shell
In your linux:
scp ipa_extractor root@device:/var/root

In your device shell command:
./ipa_extractor APPLICATION-HASH IPA-NAME or only execute the script and read the help message.
```

```
Another way to execute if you already know about the application hash and have this script in the Device:
ssh root@device "./ipa_extractor 81FC63... ipa-name"

Output:
┌──(kali㉿kali)-[~/app]
└─$ ssh root@192.168.1.65 "./ipa_extractor 97C..A test"          
root@192.168.1.65's password: 
Generating the IPA File:

  adding: private/var/containers/Bundle/Application/97C..A/Payload/ (stored 0%)
  
Here is the entire path of your IPA File:

/private/var/containers/Bundle/Application/97C..A/test.ipa
```

To see the IPA Hash you can execute the following command:
```bash
find / -name *.app
```
