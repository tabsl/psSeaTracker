psSeaTracker
============

Stores google adwords click id (gclid) by shop user.
Free Module for OXID eShop 4.6/4.7/4.8.


Features

	- saves gclid into session if google adwords clickid is used (see also http://support.google.com/analytics/answer/2938246?hl=en)
	- saves glcid and date to userobject when user is logging in / registering user account
	- shows glcid in shop admin (user information)


Installation

	1. copy content from copy_this folder into your shop root
	2. copy content from changed_full folder into your shop root (and/or customize)
	3. install sql (see below) and update views
	4. activate module psSeaTracker in shop admin
	5. delete tmp-folder


Install SQL

	ALTER TABLE  `oxuser` ADD  `PSSEATRACKER_GCLID` VARCHAR( 150 ) NOT NULL, ADD  `PSSEATRACKER_DATE` DATETIME NOT NULL;


License

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.
    

Copyright

	Proud Sourcing GmbH 2013
	www.proudcommerce.com
