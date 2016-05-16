+++
date = "2016-04-14T11:36:27-04:00"
description = ""
title = "Disabling FK in Liquibase"
+++


I use this for disabling checks when load data from CSV files in Liquibase.

Just use:

~~~
<sql>SET FOREIGN_KEY_CHECKS=0;</sql>
~~~

for disable check, and use this for enable:

~~~
<sql>SET FOREIGN_KEY_CHECKS=1;</sql>
~~~

Sample:

<script src="https://gist.github.com/wavecos/ca082964f8b13ad5d720ba15f3ffdaa3.js"></script>
