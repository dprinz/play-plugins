# SbtGoodies Plugin

various sbt plugin addons

# How to install

* add 
(requires play 2.0.2)
```
addSbtPlugin("com.typesafe" % "play-plugins-sbtgoodies" % "0.2")
``` 
to your ```project/plugins.sbt```

and that's it!

# How to Use

available commands:

* ```dist-unzip``` unzips a distribution, also adds execution bit (on
  *nix) or creates ```start.bat``` (on windows)

# Sample

For an example, see the bundled sample app

## Licence

This software is licensed under the Apache 2 license, quoted below.

Copyright 2012 Typesafe (http://www.typesafe.com).

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this project except in compliance with the License. You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0.

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
