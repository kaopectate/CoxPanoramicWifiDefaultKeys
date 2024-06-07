# CoxPanoramicWifiDefaultKeys
All possible default pre-shared keys for Cox Panoramic WiFi access points for use wit hashcat combinator attack.

SSID will start with 'SETUP-' plus 4 hex like:
"SETUP-1234"
"SETUP-FEDC"

defult keys are 14 to 16 characters with an aba format where :
a = a dictionary word with 5-6 letters in lower case
b = 0000-9999

examples:
circle4298empty
chore4982become

hashcat example

hashcat -m 22000 -a 1 yourhashfile.hash list1.txt.gz list2.txt

with the 2 files combined it have a keyspace of roughly 85 billion (84,913,960,000)

This should crack in under 10 hours with a 4090