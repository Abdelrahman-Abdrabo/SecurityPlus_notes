# SecurityPlus_notes
تعالى نتكلم عن ال
network reconnaissance or network discovery

الهجوم لما بياجي, بياجي عن طريق الشبكة أو برنامج مصاب
لما بعمل reconnaissance بكون قادر أعرف الهجوم ممكن ياجيلي منين
حاجة زي كده ممكن يستخدمها الهاكر أو حد من تيم السيكيوريتي.

Topology discovery (footprinting)
بعمل فحص للشبكة وال hosts وال ip range اللي عندي
يعني مثلا ممكن أعمل فحص الاقي عشر أجهزة منهم ويندوز وماك وكده وبالتالي هيكون عندي تخيل لشكل الشبكة
في بقى شوية أوامر موجودة في ويندوز أو لينكس هتساعدك تعمل topology discovery:

الأوامر اللي جاية بتكون في نطاق ال local network بتاعتي, أو كمان ال subnet اللي أنا فيه

* ipconfig : on windows

* ifconfig : on Linux

ودول بيعرضوا ال configuration بتاع كارت الشبكة عندي او يعني ال network interface configuration.

* ping : بكتب بعديه ip أو hostname

ده بستخدمه عشان أتأكد من الconnctoin بيني وبين جهاز تاني
كأنك يعني بتنادي على صاحبك تتأكد هو سامعك ولا لأ.
والكوماند ده بيستخدم بروتوكول ICMP.

ده مش شرط يكون الip معاك في الشبكة, ممكن يكون في مكان تاني برده بتتأكد انك قادر توصله ولا لأ.

* arp -a :
بيعرض الip وال mac بتاعت الأجهزة اللي تواصلت معاها

اللي هو يعني بيعرض ال ARP cache

وبرده في شوية كوماندز تانية بس خاصة بال routing زي
route و tracert على ويندوز و  traceroute  على لينكس و  pathping
