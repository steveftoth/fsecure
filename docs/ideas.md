
# Examples from f-secure website.

GoKey https://github.com/f-secure-foundry/gokey

Interactive Encrypted Drive https://github.com/f-secure-foundry/armory-drive

# Expansions
## Secure storage with sync
### Abstract

Device would manage keys and encryption/decryption of data in a drive like export.  User interfance would be that the device is plugged in and is exposed as a normal drive to the user.  Under the hood a driver would be needed on the host computer that handles sync of data to/from cloud.  Cloud provider of storage (Google Drive/Apple iCloud/Dropbox/etc.) would only ever have files that are fully encrypted, could be stored even in ipfs/public file systems since only device has key.

### Device/Cloud Sync

#### rsync 
 
Simple rsync to/from user's drive folder to a 'unencrypted' drive exposed from device.  So device would expose 2 drives, one for doing basic 'dumb' syncs via rsync as the client to/from cloud.  Device also exports a second drive that is an unencrypted version of the data for use by user level programs.

#### 1Password device

HID interface for passwords

#### Communication between MacT2/Secure Enclave

Get a public key from the T2 and a public key from the Armory and then you can send messages only between those two computers

# New to me ideas


