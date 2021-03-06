
/*
 * Copyright Copyright 2013 GTRI
 * Copyright Copyright 2010 SWITCH
 *
 * Licensed under the Apache License, Version 2.0 (the "License");
 * you may not use this file except in compliance with the License.
 * You may obtain a copy of the License at
 *
 * http://www.apache.org/licenses/LICENSE-2.0
 *
 * Unless required by applicable law or agreed to in writing, software
 * distributed under the License is distributed on an "AS IS" BASIS,
 * WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 * See the License for the specific language governing permissions and
 * limitations under the License.
 */

PIV Login Handler
-------------------
This login handler is heavily based on the X.509 Login Handler developed
by Switch.  More information about their login handler can be found here:

  https://wiki.shibboleth.net/confluence/display/SHIB2/X.509+Login+Handler

The installation process is identical to the Switch handler as all that has
changed is the certificate parsing code, as this handler strictly looks for 
FASC-N and PIV-I UUIDs.  To use this handler follow the same instructions 
seen on the above Shibboleth extension page.

