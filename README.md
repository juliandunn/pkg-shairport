Shairport Packaging Scripts for Debian
======================================

Packaging scripts to make [shairport](https://github.com/abrasive/shairport) DEB for Debian systems. Why bother?
So that it's easy to get onto a Raspberry Pi (which runs Debian)
without too much pain and suffering or having to install a compiler &
other tools on the Pi.

To-Do
-----

Make Shairport not run under the 'root' user. Right now this isn't possible
because the LSB scripts don't accept --chuid that /sbin/start-stop-daemon
does, so the init script needs to be rewritten to call that directly (and
precreate the PID file).

License and Author
------------------

* Copyright: 2014 Julian C. Dunn <jdunn@aquezada.com>

```text
 This program is free software; you can redistribute it and/or modify
 it under the terms of the GNU General Public License as published by
 the Free Software Foundation; either version 2 of the License, or
 (at your option) any later version.
 
 This program is distributed in the hope that it will be useful,
 but WITHOUT ANY WARRANTY; without even the implied warranty of
 MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
 GNU General Public License for more details.
 
 You should have received a copy of the GNU General Public License along
 with this program; if not, write to the Free Software Foundation, Inc.,
 51 Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA.
 
 On Debian systems, the full text of the GNU General Public
 License version 2 can be found in the file
 /usr/share/common-licenses/GPL-2.
```
