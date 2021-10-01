# check_ice_count
Nagios plugin that will report the number of users on various Icecast mount points

Example run...
 ./check_ice_count -H stream.domain.com -p 8443 -s 
  | '/128'=1;;;; '/32'=2;;;; '/aac'=0;;;; 
