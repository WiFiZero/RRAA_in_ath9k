The device driver is compatible with linux kernel 2.6.24 and higher. 

#Comipilation
To compile the code use command make in terminal.



#Documentation
Changes made in original source code are :

1. New files rc80211_rraa.h and rc80211_rraa.c are added in compat-drivers-3.8.2-2\drivers\net\wireless\ath\ath9k folder.
2. CONFIG_MAC80211_RC_RRAA macro is defined in makefile of above folder to unable RRAA
   The rraa code can be compiled without defining it also but in that case no othe rate macro must be defined.
3. Some changes are also done in xmit.c, init.c, rate.h
4. Changes can be searched by using keyword "added for".


All the other documentation are available at https://backports.wiki.kernel.org .