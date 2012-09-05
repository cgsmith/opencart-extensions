==============================================================================
SECURE PASSWORD - Instructions
v1.20.154

This extension changes the default MD5 password hash to a bcrypt password 
hash. It will allow current users to still login with the same password and
will update a field in the database with the new hash.

Author: CGSmith.net, LLC
E-mail: chris@cgsmith.net
Website: http://www.cgsmith.net
==============================================================================

All steps are required.  As always, backup your DATABASE and OPENCART files!!!

1. Lengthen the 'password' fields in the database under 'customer' and 'user' to
   256 characters.  See example SQL file.

2. Place the 'system' folder in OpenCart via FTP.  No files are overwritten.

3. Place the 'vqmod' folder in OpenCart via FTP.  No files are overwritten.

4. Login and create a user to make sure everything works.