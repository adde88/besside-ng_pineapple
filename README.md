# besside-ng_pineapple
Part of the aircrack-ng (experimental version) for the WiFi Pineapples, with custom scripts.  
For OpenWRT 19.07 (Pineapple firmware > 2.6)

besside-ng 1.5.2 - (C) 2019 Andreas Nilsen
  Modified for WiFi Pineapple + 5GHz Support (autochannel detection) + WEP only + custom IV num
  http://www.aircrack-ng.org  -  https://github.com/adde88

  Usage: ./besside-ng [options] <interface>

  Options:

       -b <victim mac> : Victim BSSID
       -R <victim ap regex> : Victim ESSID regex
       -s <WPA server> : Upload wpa.cap for cracking
       -c       <chan> : chanlock
       -p       <pps>  : flood rate
       -W              : WPA only
       -w              : WEP only
       -v              : verbose, -vv for more, etc.
       -h              : This help screen
       -w              : WEP only
       -C	 <num>	: Start WEP cracking at <num> IV's
       		        : Default is 5000 <num> IV's
