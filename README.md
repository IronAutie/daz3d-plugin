# I Compiled My Own DAZ Studio Plugin on Windows 11!

By Andrew Jonathan Fine. Originally published 2024-09-29 on Buy Me a Coffee.

I compiled my own DAZ3D plugin for a reason.

I'm not necessarily desiring to make cartoons or animation.

What I really want is to have a free CAD-CAM application worthy of the name. About a year ago, BobCAD decided to no longer license the use of their legacy software. Since a user license for their latest versions costs more than an autistic like me can afford on SSDI, it made sense for me to try to use some other platform.

The various publicly available CAD-CAM packages which I've played with are so poorly designed as to be both unmaintainable and unusable. I won't name names.

As far as animation packages, go: Blender is too complicated to be usable. Maya is okay, but it costs significant money.

In favor of DAZ3D:

- DAZ3D has the best user interface for making three dimensional objects that I have ever experienced!
- DAZ3D has the ability to run third party compiled plug-ins using to a software development kit (DAZ SDK for 4.5+) originated and distributed gratis by the company.
- DAZ3D is freely down loadable (at this time, the 4.22 Pro version)

Against DAZ3D:

- There has been news for a long time about a DAZ 5 version. Whether or not DAZ 4 will still be allowed for use is up in the air. If not, you will be limited to running your DAZ 4 off-line with your existing materials and plug-ins, and you will otherwise lose a massive investment of time and money having gotten your DAZ 4 environment just the way you like it.
- The company has made an effort to not maintain the compiled plug-in creation ability. They are not answering customer support questions regarding this. They are instead encouraging the use of scripting instead. So making your own plug ins is a closely held secret by DAZ and developers in the know.

About DAZ Studio compiled plugs:

You have to be truly desperate to have to deal with the pain in the ass which the process has become, since the company is not answering questions beyond what they already have given to software developers.

Since I *am* that desperate to have CAD working on a free 3D package running on Windows 11, I have discovered that it takes the following steps, done in the following order, to install this software, in this order, to get my first plug-in running:

LEGAL DISCLAIMER: Results may vary. No guarantees about workability, appropriateness, or legality of advice. If you break your computer or software, that's your own fault, not mine. By following my instructions you assume all liability.

- The latest DAZ Install Manager (64 bit)
- The latest DAZ Studio (4.22 at the time of this writing, 64 bit)
- DAZ Studio 4.5+ SDK Core (Win)
- DAZ Studio 4.5+ SDK Docs
- DAZ Studio 4.5+ SDK Samples (Win)
- Visual Studio 2010
- CMake 3.22
- And some tools integration magic!

If you are interested in doing this for your own edification, I suggest you download and integrate the above tools as soon as you can, because there is no guarantee that the mirror sites for some of the above software will remain available.

All I can do is tell you what I've found out, leveraging my schooling and experience as a software designer. All of it useless to me today due to discrimination against my being autistic for employment, promotion, and retention.

Because of that, I've been out of the work force for more than 20 years, even though I still remember it all like yesterday.

Good Luck!
