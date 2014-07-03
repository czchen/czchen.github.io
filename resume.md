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
*   PGP Key fringprint: [EC9F 905D 866D BE46 A896  C827 BE0C 9242 03F4 552D](http://pgp.mit.edu:11371/pks/lookup?op=vindex&search=0xBE0C924203F4552D)

# Educational Background

## Traditional

*   Master's degree in Computer Science, National Tsing Hua University. Sep., 2004 ~ Jun., 2006.
*   Bachelor's degree in Computer and Information Science, National Chiao Tung University. Sep., 2000 ~ Jun., 2004.

## Massive Open Online Course

### Coursera

*   [Malicious Software and its Underground Economy: Two Sides to Every Story](http://czchen.info/mooc/Coursera%20malsoftware%202013.pdf)
*   [Algorithms: Design and Analysis, Part 1](http://czchen.info/mooc/Coursera%20algo%202013.pdf)
*   [Algorithms: Design and Analysis, Part 2](http://czchen.info/mooc/Coursera%20algo2%202013.pdf)
*   [Cryptography I](http://czchen.info/mooc/Coursera%20crypto%202013.pdf)
*   [Automata](http://czchen.info/mooc/Coursera%20automata%202014.pdf)
*   [Machine Learning](http://czchen.info/mooc/Coursera%20ml%202014.pdf)
*   [Computing for Data Analysis](http://czchen.info/mooc/Coursera%20compdata%202014.pdf)
*   [Social and Economic Networks: Models and Analysis](http://czchen.info/mooc/Coursera%20networksonline%202014.pdf)
*   [The Data Scientist’s Toolbox](http://czchen.info/mooc/Coursera%20datascitoolbox%202014.pdf)
*   [R Programming](http://czchen.info/mooc/Coursera%20rprog%202014.pdf)
*   [Getting and Cleaning Data](http://czchen.info/mooc/Coursera%20getdata%202014.pdf)

# Working History

## [Debian](http://www.debian.org/)

### Experience

*   Nov., 2013 ~ present, Maintainer

### Summary

I has contributed to debian since answering [Invitation and roll call: Debian IME Packaging Team (Call for help)](https://lists.alioth.debian.org/pipermail/pkg-ime-devel/2013-June/002985.html) from Osamu Aoki, who is one of leader of Debian Input Method Environment Packaging Team. As a team member of IME team, I help to maintain Chinese related input method packages like libchewing, ibus-chewing, gcin, hime, .... By doing so, I got debian maintainer permission at [Mini Debian Conf 2013](https://wiki.debian.org/DebianTaiwan/MiniDebConf2013). Beside input method related packages, I also package some programs I used when they are not in debian yet.

With Kanru's advocate, I applied debian development after OSDC 2014. The process does not finished yet.

### Reference

*   [Debian New Member Front Desk](https://nm.debian.org/public/person/czchen)
*   [Packages overview for ChangZhuo Chen (陳昌倬)](http://qa.debian.org/developer.php?login=czchen@gmail.com)

## [g0v](http://g0v.tw/)

### Experience

*   Mar., 2013 ~ present, Contributor

### Summary

I has contributed to g0v projects since [g0v.tw hackath2n](http://g0v-tw.kktix.cc/events/g0v-hackath2n-taipei). The projects I focus on are laweasyread and kuansim. The main jobs for me in these projects are to enhance web cralwer, sanitize data, design and implement RESTful APIs, and setup test/CI environment.

Beside laweasyread and kuansum, I also help to setup test environment likes [karma](https://github.com/karma-runner/karma) and [protractor](https://github.com/angular/protractor) for other g0v projects.

### Reference

*   [laweasyread contribution](https://github.com/g0v/laweasyread/commits?author=czchen)
*   [laweasyread-data contribution](https://github.com/g0v/laweasyread-data/commits?author=czchen)
*   [kuansim-frontend contribution](https://github.com/g0v/kuansim-frontend/commits?author=czchen)
*   [kuansim-backend contribution](https://github.com/g0v/kuansim-backend/commits?author=czchen)

## [Chewing Input Method (新酷音輸入法) Development](http://chewing.im/)

### Experience

*   Sep., 2012 ~ present, Developer

### Summary

I joined chewing development to answer jserv call for developer at COSCUP 2012. My contributions for chewing are listed as following:

*   Setup [ubuntu PPA](https://launchpad.net/~chewing) to provide latest libchewing to user.
*   Integrate with coveralls.io to generate [coverage report](https://coveralls.io/r/chewing/libchewing) for every push.
*   Write test cases to increase coverage rate to 81%.
*   Cleanup system database and implement check mechanism to prevent incorrectly phrase slipping into system phrase database.
*   Implement dynamic programming based algorithm to enhance composition performance. The algorithm is around 800 times faster then previous brute force one.
*   Use sqlite3 to store user phrase.
*   Implement [new user phrase editor](https://github.com/chewing/chewing-editor) based on Qt5.
*   Have a [talk about libchewing](http://czchen.info/talks_joining_libchewing_development) in COSCUP 2013.

### Reference

*   [chewing development group](https://groups.google.com/forum/#!forum/chewing-devel)
*   [libchewing contribution](https://github.com/chewing/libchewing/commits?author=czchen)
*   [windows-chewing-tsf contribution](https://github.com/chewing/windows-chewing-tsf/commits?author=czchen)
*   [chewing-editor contribution](https://github.com/chewing/chewing-editor/commits?author=czchen)
*   [ibus-chewing contribution](https://github.com/definite/ibus-chewing/commits?author=czchen)

## [Trend Micro](http://www.trendmicro.com/)

### Experience

*   Dec., 2010 ~ present, Senior Engineer

### Summary

#### Virus scan engine test engineer

*   Test virus scan engine (VSAPI) version 9.5, 9.6, 9.7, 9.73, 9.75, 9.8.
*   Setup and maintain Linux i386 / amd64 / arm, android, HPUX platforms.
    *   Use puppet to maintain Linux i386 / amd64 machines.
    *   Build valgrind for android to perform memory usage test and profiling.
*   Improve regression test process so that it can reach 100% pass rate from 95% (approximately).
*   Maintain testing tools.
*   Integrate old test scripts into new automatic test framework (SCTM).
    *   Automatic import test case from perl script to SCTM.

#### Packer Solution Operation

*   Design an automatic process to handle virus samples.
    *   Revise database schema.
    *   Use `vmrun` to control several VMs at once to increase scanning throughput.
*   Generate scan report for developer for further analyzing.

## [Qisda Corporation](http://qisda.com/)

### Experience

*   Apr., 2009 ~ Dec., 2010 Senior Engineer
*   Oct., 2006 ~ Apr., 2009 Engineer

### Summary

#### Solve SIM/USIM/R-UIM related issues mobile phone and module.

*   Implement new SIM lock mechanism to fulfill all requirements.
*   Maintenance and develop auto testing tool for GCF/PTCRB.
*   Solved 176 issues, held 17 presentations, wrote 14 documents.

#### Professional Accomplishments

*   [Protocol test machine] Improvement auto-testing tool for GCF/PTCRB in house testing.
    *   Support up to 80% test cases from 20% (approximate).
    *   Can test device without keypad and screen.
    *   Run test machine 24 hours a day, instead of 12 hours.
*   [Windows Phone 7 ODM] SIM lock mechanism
    *   Original SIM lock mechanism is not flexible to adapt different lock requirements and it is hard to maintain.
    *   Use Tag, Length, Value (TLV) format to store data
    *   RSA as cryptographic algorithms
    *   Auto-testing tool for device
    *   Auto-testing tool for encoder DLL

## Miscellaneous Open Source Projects

I also contribute to the following open source projects:

*   [antigen](https://github.com/zsh-users/antigen/commits?author=czchen)
    *   Antigen is a small set of functions that help you easily manage your shell (zsh) plugins.
*   [autoconf](http://www.gnu.org/software/autoconf/)
    *   Autoconf is an extensible package of M4 macros that produce shell scripts to automatically configure software source code packages.
*   [cpp-coveralls](https://github.com/eddyxu/cpp-coveralls/commits?author=czchen)
    *   [coveralls.io](https://coveralls.io/) report uploader for C/C++ project.
*   [cppman](https://github.com/aitjcize/cppman/commits?author=czchen)
    *   C++ 98/11 manual pages for Linux, with source from cplusplus.com.
*   [Firefix](http://www.mozilla.org/en-US/firefox/new/)
    *   A web browser.
*   [github-services](https://github.com/github/github-services/commits?author=czchen)
    *   This repository contains code to integrate GitHub.com with third party services.
*   [gulp-protractor](https://github.com/mllrsohn/gulp-protractor/commits?author=czchen)
    *   Run your [angular protractor](https://github.com/angular/protractor) tests with [gulp](https://github.com/gulpjs/gulp).
*   [hime](https://github.com/hime-ime/hime/commits?author=czchen)
    *   HIME Input Method Editor.
*   [karma](https://github.com/karma-runner/karma/commits?author=czchen)
    *   A simple tool that allows you to execute JavaScript code in multiple real browsers.
*   [libbbs](https://github.com/pcman-bbs/libbbs/commits?author=czchen)
    *   A telnet bulletin board system (BBS) helper library.
*   [libzhuyin](https://github.com/libzhuyin/libzhuyin/commits?author=czchen)
    *   Library to deal with zhuyin.
*   [lxc](https://github.com/lxc/lxc/commits?author=czchen)
    *   The linux containers, lxc, aims to use these new functionalities to provide an userspace container object which provides full resource isolation and resource control for an applications or a system.
*   [origami-pdf](https://code.google.com/p/origami-pdf/)
    *   Origami is a Ruby framework designed to parse, analyze, and forge PDF documents.
*   [PCManX](https://github.com/pcman-bbs/pcmanx/commits?author=czchen)
    *   PCManX is a free telnet BBS (Bulletin Board System) tool.
*   [pgrest](https://github.com/pgrest/pgrest/commits?author=czchen)
    *   A RESTful API for PostgreSQL
*   [protractor](https://github.com/angular/protractor/commits?author=czchen)
    *   Protractor is an end to end test framework for AngularJS applications built on top of WebDriverJS.
*   [r3](https://github.com/c9s/r3/commits?author=czchen)
    *   R3 is an URL router library with high performance, thus, it's implemented in C. It compiles your route paths into a prefix trie.
*   [vim](www.vim.org)
    *   A text editor.

# Update
*   The latest version of this resume is in <http://czchen.info/resume.md>.
