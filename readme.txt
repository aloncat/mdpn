Most Delayed Palindromic Number (MDPN)
--------------------------------------

Project homepage:
  https://dmaslov.me/mdpn/

This repository contains the MDPN project database. To reduce the
database size, starting from 12-digit range, delayed palindromes, which
are resolved in less than 14 steps (RAA operations), are excluded from
the database. Similarly, there are no delayed palindromes in the 13-digit
range (and above) that are resolved in less than 32 steps. And so on
(see table below and screenshot 'stats.png' for details).
However, it's guaranteed that for each step the database stores at least
100,000 of the earliest base numbers and at least one billion (in total)
of their kin numbers.

Source code and scripts are maintained
in the main iLWN project repository:
  https://github.com/aloncat/ilwn.git

For contact information, please visit:
  https://dmaslov.me/contacts.html

Directory structure:
--------------------
  data		Delayed palindromes database

Range              | Min step
-----------------------------
11-digit and below |	  1
12-digit numbers   |	 14
13-digit numbers   |	 32
14-digit numbers   |	 51
15-digit numbers   |	 61
