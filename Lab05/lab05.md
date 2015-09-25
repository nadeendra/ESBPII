###ESBPII Lab 05 - Setting up owncloud
#######L H Malavige - IT12042302


---------------------------------------------------------

##Screenshots - Setting up owncloud 


**Setting up an online repository that has owncloud package- 1**
![image2](https://scontent-sin1-1.xx.fbcdn.net/hphotos-xpf1/v/t1.0-9/11836874_1096536407024015_7061735776217638655_n.jpg?oh=7242ca4d8353941e6cd5e5c9dd2382ec&oe=56540BF5)

**Setting up an online repository that has owncloud package - 2**
![image3](https://fbcdn-sphotos-f-a.akamaihd.net/hphotos-ak-xfp1/v/t1.0-9/11811401_1096536397024016_287511044835737430_n.jpg?oh=f22eaedb508128a30440f5f8351b0f11&oe=5640323D&__gda__=1443839668_03111516323bec7c80b3c1e9f921f70b)

**Install owncloud package**
![image4](https://fbcdn-sphotos-f-a.akamaihd.net/hphotos-ak-xpa1/v/t1.0-9/11209544_1096536403690682_160181871126440309_n.jpg?oh=9937aef17b7158b2396d1dce6a33013b&oe=564E32FF&__gda__=1447308615_19d0d1c60f98621e0780fb0869c982c8)

**Setting up a local repository in /etc/yum.repos.d as LocalRepo by mounting the RHEL-7 cdrom (mount point - /cdrom)**
![image4](https://scontent-sin1-1.xx.fbcdn.net/hphotos-xpf1/v/t1.0-9/11060085_1096536427024013_1091286912658855774_n.jpg?oh=4debd34c750a674981bedfc1a64a4c8b&oe=5646FFBC)

**Installing web service**
![image4](https://scontent-sin1-1.xx.fbcdn.net/hphotos-xfp1/v/t1.0-9/11825162_1096536460357343_8694663698396295258_n.jpg?oh=61d98649f06663768cb209c232c7a523&oe=563BCFA5)

**Start and enable(start at the boot) the web service**
![image5](https://scontent-sin1-1.xx.fbcdn.net/hphotos-xtf1/v/t1.0-9/11796228_1096536483690674_8975159435827601465_n.jpg?oh=7ca68b86996af95cd8e4dd03da456955&oe=56429F06)

**Download and install mysql-server**
![image5](https://scontent-sin1-1.xx.fbcdn.net/hphotos-xpf1/v/t1.0-9/11811355_1096536493690673_751385861927829186_n.jpg?oh=a3aedcac5441fabbd20f39f70b6b24a8&oe=564A213A)

**Start and enable(start at the boot) mysql-server**
![image5](https://fbcdn-sphotos-a-a.akamaihd.net/hphotos-ak-xaf1/v/t1.0-9/11822815_1096536510357338_7505161858275209970_n.jpg?oh=d9a0aeafba0e4c479c4eb80cba543e95&oe=563BEB50&__gda__=1448495591_8e40ce100476c53486b32d4b57be404c)

**Initiate mysql configurations**
![image5](https://fbcdn-sphotos-h-a.akamaihd.net/hphotos-ak-xaf1/v/t1.0-9/11800146_1096536527024003_6886119243123822331_n.jpg?oh=f132e0c52f4face9e419f28a6aea0cb0&oe=563DBD24&__gda__=1443797907_3ef214a166356955df1705f8e43b540b)

**Mysql configuration - 1**

![image5](https://scontent-sin1-1.xx.fbcdn.net/hphotos-xta1/v/t1.0-9/p206x206/11800059_1096536547024001_3101231616427658608_n.jpg?oh=73b5b3baafa1a23d4ca1ee4fcb20d426&oe=564C2CA7)

**Mysql configuration - 2**

![image5](https://scontent-sin1-1.xx.fbcdn.net/hphotos-xpa1/v/t1.0-9/11220879_1096536557024000_7234904076365023646_n.jpg?oh=5b48ed74726cf72870d1e5e29ca6ee01&oe=564DF7B2)

**Creating Database and setting username password**
![image5](https://scontent-sin1-1.xx.fbcdn.net/hphotos-xpt1/v/t1.0-9/11811307_1096536573690665_5753281586056231955_n.jpg?oh=5cca1457b5931b27a9fbb43a1d8274dc&oe=564041E5)

**Edit /etc/httpd/conf/httpd.conf to Allowoverride All so that the configurations can be altered accordingly**
![image5](https://fbcdn-sphotos-f-a.akamaihd.net/hphotos-ak-xtp1/v/t1.0-9/11822365_1096536593690663_2354818262960819601_n.jpg?oh=553f6ec9f477cc6b98d54c274d67ff5b&oe=5653F939&__gda__=1447250207_5a37c06b5c5480426b95bd9718d8d38a)

**Download owncloud application, Copy it to /var/www/html and extract. You may delete the .tar file after extraction"**
![image5](https://scontent-sin1-1.xx.fbcdn.net/hphotos-xfa1/v/t1.0-9/11800206_1096536600357329_3974554502699632128_n.jpg?oh=86f35aa03145f69dd712e0c351dffe8b&oe=5643F2F9)

**Setting up the permission of /var/www/html/owncloud**
![image5](https://fbcdn-sphotos-f-a.akamaihd.net/hphotos-ak-xpf1/v/t1.0-9/11816996_1096536607023995_642614015851829176_n.jpg?oh=73a968da5883ec439c3eb6859df76df5&oe=564B7133&__gda__=1448832601_760c5d1bf06d574c9a2e45e87b8fc043)

**Type http://localhost/owncloud as the URl in the browser to access the owncloud**
![image5](https://fbcdn-sphotos-f-a.akamaihd.net/hphotos-ak-xfp1/v/t1.0-9/10985353_1096536650357324_1170514134148798965_n.jpg?oh=b0dcf87970cf08744910ab57aa08e628&oe=560ECDB4&__gda__=1446874340_a3c61c813848309315a32e42e62ea708)

**Type admin username and password and then fill the storage specifications.Mysql was installed as the db solution and Username and password were provided when creating the database** 
![image5](https://fbcdn-sphotos-g-a.akamaihd.net/hphotos-ak-xpa1/v/t1.0-9/11825051_1096536657023990_2421677348023060131_n.jpg?oh=bb31f36d5192e65aa58b4c37dce8dbab&oe=56523A33&__gda__=1448306521_b018e24f66a394415d97d14dc6561dfa)

**Completed**
![image5](https://scontent-sin1-1.xx.fbcdn.net/hphotos-xpt1/v/t1.0-9/11825912_1096536667023989_7537214321061379729_n.jpg?oh=17f57a3bd1bb3c5e2468b53067c9549d&oe=5656AC2D)












