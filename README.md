# besside-ng_pineapple
Part of the aircrack-ng (experimental version) for the WiFi Pineapples, with custom scripts.

Besside-ng 1.2 rc2 - (C) 2017 Andreas Nilsen
  Modified for WiFi Pineapple + 5GHz Support
  http://www.aircrack-ng.org  -  https://github.com/adde88

  Usage: ./besside-ng [options] <interface>

  Options:

       -b <victim mac> : Victim BSSID
       -R <victim ap regex> : Victim ESSID regex
       -s <WPA server> : Upload wpa.cap for cracking
       -c       <chan> : chanlock
       -p       <pps>  : flood rate
       -W              : WPA only
       -v              : verbose, -vv for more, etc.
       -h              : This help screen
       -w              : WEP only
       -C	 <num>	: Start WEP cracking at <num> IV's
       		        : Default is 5000 <num> IV's
