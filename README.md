
Command Usage:

./smokepingclient -v --master http://smokeping.install/smokeping/smokeping.cgi -n myclientname --secret abcd1234

Example Smokeping Config

+ myclientname

menu = myclientname
title = Local Network
slaves = myclientname
nomasterpoll = yes

++ gateway

menu = gateway
title = Local Gateway
host = 127.0.0.1

++ google

menu = google
title = Google Nameserver
host = 127.0.0.1

