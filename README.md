# Crack-A-Lot

when opened the "confidential file "  there were a list of several thousand passwords, so brute force attack was  the first  idea that came to mind 
so i searched for bssid in "TOP_SECRET.pcap" file 
command :
ctrl+f
searched for packet bssid
got bssid :f6:0f:6c:4d:06:7c
then used aircrack-ng for brute force attack
command: 
  aircrack-ng -w the_secret_flag.txt -b f6:0f:6c:4d:06:7c TOP_SECRET.pcap
resut:
  then it gave 1 potential target
  5275/5878 tested
  wired{c4ts_4r3_c00l}

  
