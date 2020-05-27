# SCOM-hotfix-MP-for-Print-server-2008
This management pack fixes a few performance collection rules in the Printer Server 2008 management pack with version 6.0.7004.0.Seven collection rules were wrongly targetted at Printer class in stead of Printer Server Role.

This management pack fixes a few performance collection rules in the Printer Server 2008 management pack with version 6.0.7004.0.

Seven collection rules were wrongly targetted at Printer class in stead of Printer Server Role. If many queues exist on a print server this meant an exponential amount of data got gathered, thus causing problems.

This fix management pack disables those 7 rules (even though a few of them were already disabled). Next the same rules are re-created with the right targetting. The enabled or disabled settings of the fixed rules are the same as the original rules.

For more information check out this blog post: https://blog.topqore.com/hotfix-mp-print-server-2008/

 

Bob Cornelissen, BICTT, SCOM MVP
