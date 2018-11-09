# Tsung README

[![Build Status](https://travis-ci.org/processone/tsung.svg?branch=master)](https://travis-ci.org/processone/tsung)

##  Introduction

This document gives pointers for information on this package which is
distributed under the GNU General Public License version 2 (see file
COPYING).

##  What This Package Is

Tsung is multi-protocol distributed load testing tool.

It can be used to test the scalability and performances of IP based
client/server applications (supported protocols: HTTP, WebDAV, SOAP,
PostgreSQL, MySQL, LDAP, MQTT, AMQP and Jabber/XMPP)

A User's manual is available :
          http://tsung.erlang-projects.org/user_manual/

##  Problems/Bugs

Join the mailing-list:
  https://lists.process-one.net/mailman/listinfo/tsung-users

or use the tracker https://github.com/processone/tsung/issues

## Customized Parts

Jabber: send chat message to a single user. Set destination to `single_user` and set required attribute ( `single_username`, `single_domain` and `single_resource` ), You can use dynamic variable in those attributes 
##### Usage
```xml
<jabber ack="no_ack" type="chat" size="20000" destination="single_user" single_username="%%_username%%" single_domain="my-alfred.com" single_resource="viewer_1"/>
```

