# Personal Data

*   Name
    *   陳昌倬
    *   ChangZhuo Chen
    *   Chang-Cho Chen
*   Email: <czchen@gmail.com>
*   Phone: +886922140016
*   Web page:
    *   <http://czchen.info/>
    *   <https://github.com/czchen/>
    *   <http://tw.linkedin.com/in/changzhuo/>
    *   <https://www.openhub.net/accounts/czchen?ref=Detailed>
    *   <https://mozillians.org/u/czchen/>
*   PGP Key fringprint: [EC9F 905D 866D BE46 A896  C827 BE0C 9242 03F4 552D](http://pgp.mit.edu:11371/pks/lookup?op=vindex&search=0xBE0C924203F4552D)

# Skills

*   Language:
    *   Mandarin
    *   English
*   Programming Language:
    *   Mastery of C, C++, python.
    *   Familiar with Bash, Perl.
    *   Experienced in Go, Haskell, JavaScript, LiveScript, Octave, R, Ruby, Scala.
*   Operating System:
    *   Familiar with Linux (especially debian-based distro) development tools, including autotools, binutils (readelf, objdump), clang (address sanitizer, c static analyzer), cmake, gcc (coverage report), gdb, git, valgrind.
    *   Familiar with Windows development tools, including hiew, GFlags, ollydbg, process explorer, process monitor, windbg.

# Working History

## [Appier](http://www.appier.com/)

### Experience

*   Nov., 2014 ~ present, Senior Engineer

### Summary

*   Implement and maintain retargeting tracking SDK on Android/iOS platform based on [snowplow](http://snowplowanalytics.com/).

*   Implement and maintain retargeting tracking pipeline:
    *   SDK:
        *   Implement and maintain retargeting tracking SDK on Android/iOS platform based on snowplow (http://snowplowanalytics.com/).
        *   Maintain SDK developed by [leftshift](http://leftshift.io/).
    *   Beacon:
        *   Lightweight [openresty](https://openresty.org/) server to receive event from web and mobile tracking SDK.
    *   Queue:
        *   Send event to [Amazon Kinesis](https://aws.amazon.com/kinesis/) and [Apache Kafka](http://kafka.apache.org/) for ETL process.
    *   ETL:
        *   Use [Kinesis](https://aws.amazon.com/kinesis/) application and [Spark streaming](http://spark.apache.org/streaming/) to do ETL process and postback to other internal endpoint.
    *   Storage:
        *   Store data into [Amazon Redshift](https://aws.amazon.com/redshift/) for further analysis.
        *   Store data as [Apache Parquet](https://parquet.apache.org/) in [Amazon S3](https://aws.amazon.com/s3/) for further analysis.
    *   Monitor:
        *   Status dashboard based on [Grafana](http://grafana.org/) and [InfluxDB](https://influxdb.com/).

*   Implement datafeed synchronization with our customer:
    *   Download datafeed and update to our database daily.
    *   Automatic generate datafeed if customer does not have it.

*   Implement retargeting UI to help campaign manager handling campaign:
    *   Unified UI to setup audience on Doubleclick and Facebook.

## [Debian](http://www.debian.org/)

### Experience

*   Nov., 2013 ~ Sep., 2015, Maintainer
*   Sep., 2015 ~ present, Developer

### Summary

I has contributed to debian since answering [Invitation and roll call: Debian IME Packaging Team (Call for help)](https://lists.alioth.debian.org/pipermail/pkg-ime-devel/2013-June/002985.html) from Osamu Aoki, who is one of leader of Debian Input Method Environment Packaging Team. As a team member of IME team, I help to maintain Chinese related input method packages like libchewing, ibus-chewing, gcin, hime, .... By doing so, I got debian maintainer permission at [Mini Debian Conf 2013](https://wiki.debian.org/DebianTaiwan/MiniDebConf2013). Beside input method related packages, I also package some programs I used when they are not in debian yet.

With [Kanru](https://nm.debian.org/public/person/koster)'s advocate, I applied debian developer after [OSDC 2014](http://www.osdc.tw/2014/). [The process](https://nm.debian.org/public/person/czchen) was finished and I become Debian Developer at Sep., 2015.

The package I maintain are listed in [Packages overview for ChangZhuo Chen (陳昌倬)](https://qa.debian.org/developer.php?login=ChangZhuo+Chen). I am also the team member of the following teams:

*   [Input Method Environment for Debian](https://alioth.debian.org/projects/pkg-ime)
*   [Debian Fonts Task Force](http://pkg-fonts.alioth.debian.org/)
*   [Collaborative packaging team for LXQt desktop environment](https://alioth.debian.org/projects/pkg-lxqt/)
*   [Debian Python Modules Team](https://alioth.debian.org/projects/python-modules)


## [g0v](http://g0v.tw/)

### Experience

*   Mar., 2013 ~ present, Contributor

### Summary

I has contributed to g0v projects since [g0v.tw hackath2n](http://g0v-tw.kktix.cc/events/g0v-hackath2n-taipei). The projects I focus on are laweasyread and kuansim. The main jobs for me in these projects are to enhance web cralwer, sanitize data, design and implement RESTful APIs, and setup test/CI environment.

Beside laweasyread and kuansum, I also help to setup test environment likes [karma](https://github.com/karma-runner/karma) and [protractor](https://github.com/angular/protractor) for other g0v projects.

### Projects

*   [laweasyread contribution](https://github.com/g0v/laweasyread/commits?author=czchen)
*   [laweasyread-data contribution](https://github.com/g0v/laweasyread-data/commits?author=czchen)
*   [kuansim-frontend contribution](https://github.com/g0v/kuansim-frontend/commits?author=czchen)
*   [kuansim-backend contribution](https://github.com/g0v/kuansim-backend/commits?author=czchen)
*   [api.ly contribution](https://github.com/g0v/api.ly/commits?author=czchen)
*   [ly.g0v.tw](https://github.com/g0v/ly.g0v.tw/commits?author=czchen)
*   [twlyparser](https://github.com/g0v/twlyparser/commits?author=czchen)

## [Chewing Input Method (新酷音輸入法) Development](http://chewing.im/)

### Experience

*   Sep., 2012 ~ present, Developer

### Summary

I joined chewing development to answer [jserv](https://www.linkedin.com/in/job4jserv) call for developer at [COSCUP 2012](http://coscup.org/2012/). My contributions for chewing are listed as following:

*   Setup [ubuntu PPA](https://launchpad.net/~chewing) to provide latest libchewing to user.
*   Integrate with coveralls.io to generate [coverage report](https://coveralls.io/r/chewing/libchewing) for every push.
*   Write test cases to increase coverage rate to 81%.
*   Cleanup system database and implement check mechanism to prevent incorrectly phrase slipping into system phrase database.
*   Implement dynamic programming based algorithm to enhance composition performance. The algorithm is around 800 times faster then previous brute force one.
*   Use sqlite3 to store user phrase.
*   Implement [new user phrase editor](https://github.com/chewing/chewing-editor) based on Qt5.
*   Have a [talk about libchewing](http://czchen.info/Joining_libchewing_Development/#/) in [COSCUP 2013](http://coscup.org/2013/).

### Reference

*   [chewing development group](https://groups.google.com/forum/#!forum/chewing-devel)
*   [libchewing contribution](https://github.com/chewing/libchewing/commits?author=czchen)
*   [windows-chewing-tsf contribution](https://github.com/chewing/windows-chewing-tsf/commits?author=czchen)
*   [chewing-editor contribution](https://github.com/chewing/chewing-editor/commits?author=czchen)
*   [ibus-chewing contribution](https://github.com/definite/ibus-chewing/commits?author=czchen)

## [Trend Micro](http://www.trendmicro.com/)

### Experience

*   Dec., 2010 ~ Nov., 2014, Senior Engineer

### Summary

*   Setup apt mirror and puppet server to maintain Linux machines in virus lab (no internet connection).
*   Build valgrind for android to perform memory usage test and profiling.
*   Integrate legacy test scripts into new automatic test framework (SCTM).
    *   All test cases can be imported to SCTM by just two clicks.
*   Design an automatic process to handle virus samples.
    *   Use `vm run` to control virtual machine for 6 parallel scanning
    *   Turning database index to improvement 10% report generating speed.

## [Qisda Corporation](http://qisda.com/)

### Experience

*   Apr., 2009 ~ Dec., 2010 Senior Engineer
*   Oct., 2006 ~ Apr., 2009 Engineer

### Summary

*   Implement new SIM lock mechanism.
    *   Uses TLV format with RSA + SHA1-HMAC as cryptographic algorithm.
    *   Uses Google C++ testing framework for DLL testing.
*   Develope new auto testing tool for GCF/PTCRB.
    *   Supports up to 80% test cases from 20%
    *   Can run without human involved.
*   Solve a long live (3 projects: Motorola W7, BenQ M7, Motorola VE538) stack overflow bug in battery management.
    *   Write a testing tool to reboot device per 40 seconds since it only happens in boot time.

## Miscellaneous Open Source Projects

*  See <http://czchen.info/resume/open_source.md> for open source project list I has contributed.

# Educational Background

## Massive Open Online Course

*   See <http://czchen.info/resume/mooc.md> for course list I has participated.

## Traditional

*   Master's degree in [Computer Science](http://web.cs.nthu.edu.tw/), [National Tsing Hua University](http://www.nthu.edu.tw/). Sep., 2004 ~ Jun., 2006.
*   Bachelor's degree in [Computer and Information Science](http://www.cis.nctu.edu.tw/), [National Chiao Tung University](http://www.nctu.edu.tw/). Sep., 2000 ~ Jun., 2004.

# Update
*   The latest version of this resume is in <http://czchen.info/resume.md>.
