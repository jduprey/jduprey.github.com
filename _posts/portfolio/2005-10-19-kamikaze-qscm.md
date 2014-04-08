---
layout: post
title: "Kamikaze-QSCM - Source Control Query System"
description: "Kamikaze-qscm is a tool that allows developers and CM related personnel to query the commits made to one or more source control repositories. It is very similar to Mozilla's bonsai tool. Kamikaze-qscm currently works with Subversion."
category: portfolio
tags: ["scm", "svn"]
---
{% include JB/setup %}

![image](/images/posts/2005/kamikaze-qscm.png)

**Type**: OSS

**Status**: Inactive

Kamikaze-qscm is a tool that allows developers and CM related personnel to query the commits made to one or more source control repositories. It is very similar to Mozilla's bonsai tool. Kamikaze-qscm currently works with Subversion, but a modular approach is planned for other SCM systems.

Kamikaze for Subversion currently consists of a perl back-end hook for inserting commit information into a MySQL database. (In the future, a modular approach to data storage is planned - allowing the use of many different data storage implementations. ) A PHP front-end is used to perform repository queries and display results. (In the future a web service API (XML-RPC and/or SOAP) will be provided to access the same information for incorporation into other tools.)

[http://kamikaze-qscm.tigris.org/ ](http://kamikaze-qscm.tigris.org/ )