tinydns-notify.pl
===================

Takes a tinydns zone and a list of slave addresses, sends a "NOTIFY" message only to slaves that are running BIND, and only when their zones have changed. Modified by me, from the original script by Andrew Pam, for machines with multiple IP addresses.

Requirements
------------

* djbdns
* Perl (with the Net::DNS module)

License
-------

From the original file: Distribute and modify freely, providing attribution is preserved

### Copyright

  Copyright (c) 2001-02 [Serious Cybernetics](http://www.sericyb.com.au/)

### Authors
  
  Partially inspired by dnsnotify by Jos Backus and James Raftery
  Written 2001-02-20 by Andrew Pam (xanni |at| sericyb |dot| com |dot| au)
  Modified 2002-08-22 to support records that define nameserver addresses
  Modified 2002-08-30 to support "." records as well as "&" records
  Modified 2008-04-02 by Brad Peczka (brad |at| bradpeczka |dot| com) to support systems with secondary/multihomed IP addresses
