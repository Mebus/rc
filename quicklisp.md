<!-- -*- coding: utf-8-unix; -*-
     Danil Kutkevich's reference cards <http://kutkevich.org/rc>.
     Copyright (C) 2007, 2008, 2009, 2010 Danil Kutkevich <danil@kutkevich.org>

     This reference cards is licensed under the Creative Commons
     Attribution-Share Alike 3.0 Unported License. To view a copy of this
     license, see the COPYING file or visit
     <http://creativecommons.org/licenses/by-sa/3.0/> or send a letter to
     Creative Commons, 171 Second Street, Suite 300, San Francisco,
     California, 94105, USA. -->

Quicklisp
=========

List
----

### Installed

    (ql-dist:installed-releases (ql-dist:dist "quicklisp"))

### Available

    (ql:system-apropos "")

Remove
------

    (use-package :ql-dist) (uninstall (release "weblocks"))

Install
-------

    (ql:quickload "package-name")