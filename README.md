![Logo](http://i.imgur.com/Wjti8vi.png)

Tool that will enable the volunteer or employee working in a GLAM institution to simplify choosing and uploading selected files to [Wikimedia Commons](https://commons.wikimedia.org/). Created thanks to Wikimedia Foundation [IEG Grant](https://meta.wikimedia.org/wiki/Grants:IEG/Batch_uploader_for_small_GLAM_projects).

__[:arrow_down: Download](https://github.com/yarl/pattypan/releases)__

----

This program is being developed using [NetBeans IDE](https://netbeans.org/).

### Build and run
In order to build Pattypan, please:

Download and install:

- [Apache Ant](https://ant.apache.org/)
- the JavaFX libraries (included in Oracle's JDK but not in OpenJDK)

Then run these commands in a terminal:

```
git clone https://github.com/yarl/pattypan.git
cd pattypan
ant javafx.deploy.includeDT=true package-for-store
```
You will find compiled `.jar` file in `store` directory.

```
cd store
java -jar pattypan.jar
```

You can also set test server or any other server:

```
java -jar pattypan.jar -test
java -jar pattypan.jar "test.wikipedia.org"
```

Please note, that on test server file upload may be disabled for regular users. Admin account is suggested, you can request rights [here](https://test.wikipedia.org/wiki/Wikipedia:Requests/Permissions). If you have problems with program running, check [article on project wiki](https://github.com/yarl/pattypan/wiki/Run).

### License
Copyright (c) 2016 Paweł Marynowski.

Source code is available under the [MIT License](https://github.com/yarl/pattypan/blob/master/LICENSE). See the LICENSE file for more info. Program is using external libraries listed [here](https://github.com/yarl/pattypan/tree/master/lib).

#### Credits
Name by Wojciech Pędzich. Logo by [Rickterto](//commons.wikimedia.org/wiki/User:Rickterto), licensed under the Creative Commons [BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.en) license.


