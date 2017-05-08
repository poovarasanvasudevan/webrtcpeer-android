[![License badge](https://img.shields.io/badge/license-Apache2-orange.svg)](https://www.apache.org/licenses/LICENSE-2.0.txt)

[![][NUBOMEDIA Logo]][NUBOMEDIA]

Copyright © 2016 [VTT]. Licensed under [Apache 2.0 License].

http://doc-kurento-room-client-android.readthedocs.io/en/latest/README.html

webrtcpeer-android
==================
This repository contains an Android library for creating WebRTC connections.

What is NUBOMEDIA
-----------------
This project is part of [NUBOMEDIA], which is an open source cloud Platform as a
Service (PaaS) which makes possible to integrate Real Time Communications (RTC)
and multimedia through advanced media processing capabilities. The aim of
NUBOMEDIA is to democratize multimedia technologies helping all developers to
include advanced multimedia capabilities into their Web and smartphone
applications in a simple, direct and fast manner. To accomplish that objective,
NUBOMEDIA provides a set of APIs that try to abstract all the low level details
of service deployment, management, and exploitation allowing applications to
transparently scale and adapt to the required load while preserving QoS
guarantees.

Repository structure
--------------------
This repository consists of an Android Studio library project with gradle build scripts. 

Documentation
--------------------
Javadoc is available in [Github]. The more detailed Developers Guide and Installation Guide are available at  
[project documentation page]. The project contains source code from [WebRTC software project].

Usage
--------
You can import this project to your own Android Studio project via Maven (jCenter or Maven Central) by adding the following line to module's `build.gradle` file:
```
compile 'fi.vtt.nubomedia:webrtcpeer-android:(version-code)'
```

The latest version code of the artifact can be found on [maven artifact page].

Source
------
The source code is available in [Github]

Licensing and distribution
--------------------------
Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

Contribution policy
-------------------
You can contribute to the Nubomedia community through bug-reports, bug-fixes, new
code or new documentation. For contributing to the Nubomedia community, drop a
post to the [Nubomedia Public Mailing List] providing full information about your
contribution and its value. In your contributions, you must comply with the
following guidelines

* You must specify the specific contents of your contribution either through a
  detailed bug description, through a pull-request or through a patch.
* You must specify the licensing restrictions of the code you contribute.
* For newly created code to be incorporated in the Nubomedia code-base, you must
  accept Nubomedia to own the code copyright, so that its open source nature is
  guaranteed.
* You must justify appropriately the need and value of your contribution. The
  Nubomedia project has no obligations in relation to accepting contributions
  from third parties.
* The Nubomedia project leaders have the right of asking for further
  explanations, tests or validations of any code contributed to the community
  before it being incorporated into the Nubomedia code-base. You must be ready to
  addressing all these kind of concerns before having your code approved.

Support
-------
Support is provided through the [Nubomedia Public Mailing List]

[Apache 2.0 License]: https://www.apache.org/licenses/LICENSE-2.0.txt
[NUBOMEDIA]: http://www.nubomedia.eu
[VTT]: http://www.vtt.fi
[Github]: https://github.com/nubomedia-vtt/webrtcpeer-android
[Nubomedia Public Mailing List]: https://groups.google.com/forum/#!forum/nubomedia-dev
[project documentation page]: http://webrtcpeer-android.readthedocs.org/en/latest/
[maven artifact page]: http://search.maven.org/#search%7Cgav%7C1%7Cg%3A%22fi.vtt.nubomedia%22%20AND%20a%3A%22webrtcpeer-android%22
[WebRTC software project]: https://chromium.googlesource.com/external/webrtc/
[NUBOMEDIA Logo]: http://www.nubomedia.eu/sites/default/files/nubomedia_logo-small.png
