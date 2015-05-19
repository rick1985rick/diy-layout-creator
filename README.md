===Announcement===

*DIYLC is no longer a beta! I managed to fix some annoying bugs and stability issues, so it's a full blooded production version now :)*
<table cellpadding="0" cellspacing="0">
<tr>
<td width="151px">
[https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=25161 https://www.paypal.com/en_US/i/btn/btn_donateCC_LG.gif]
</td>
<td>
*DIYLC is provided free of charge and can be used and redistributed freely. However, it takes a lot of time and effort to build and maintain it, as well as to respond to all your questions and feature requests. Time I could have spent doing stuff that pays, playing guitar or simply enjoying my free time. If you find DIYLC useful and want to support the project, please consider making a small PayPal donation. Every little bit counts!
If you have some extra parts, transistors, tubes, ICs, caps, anything useful for a fellow DIYer, I'll gladly accept a donation in parts.*
</td>
</tr>
</table>
<br>
*If you're in need for domain names or hosting services, please use [http://affiliate.godaddy.com/redirect/2398295A139BC4965396BA176C1EB33E2F9A3601388E3715E3E8FBC5A32328EA9F101A4B90E53EA8A23FB2CDB6FC5AD4C4E87072C0845C5B1E4A81C285818A54 this GoDaddy.com] link to purchase your domain and/or hosting plan. Part of the proceeds will be donated to DIYLC project through GoDaddy affiliate program!*

===News===

DIYLC 3 is out! Follow the link in the left sidebar to download the latest build. Note that it's still a beta version and that some core pieces could be changed. Files created with the beta version may or may not work with the final version. However, if you find any bugs or think that I missed a feature that's important to you, go to [http://code.google.com/p/diy-layout-creator/issues/list Issues] page and create an issue. Before doing so, please check that someone else hasn't requested the same thing yet.


===Introduction===

DIY Layout Creator (DIYLC in short) is freeware drawing tool developed with help of a large online community of DIY electronics enthusiasts. It incorporates many ideas that came from people using older versions of the application. The goal is to provide a simple interface and enough power to let the user draw schematics, board/chassis layouts and guitar wiring diagrams quickly and without a steep learning curve.
Also, it is build around the flexible open source framework that may be used to draw pretty much anything. Below is a sample board layout drawn in DIYLC3.

<p align="center"><a href="http://diy-fever.com/wordpress/wp-content/uploads/2012/12/mark_layout_v11.png"><img src="http://diy-fever.com/wordpress/wp-content/uploads/2012/12/mark_layout_v11-320x296.png"/></a></p>

===Features===

  * platform independence, will run on any machine having Java JRE/JDK 1.6.0_10 or newer
  * easy to use interface, most of the operations can be done using mouse
  * draws schematics, board layouts and chassis layouts
  * high flexibility, has the API to allow plug-ins and new components to be added without much trouble
  * improved performance and reduced memory consumption compared to the previous versions
  * save default values for each property of a component individually
  * group components together and treat them as one, e.g. move, edit or delete
  * export the output to image, PDF or printer
  * export PCB trace mask suitable for toner transfer
  * create a Bill of Materials as a part of the project or export it to few different file formats
  * zoom in/out feature
  * configurable grid spacing on the project level
  * auto update checks for new versions
  * import files created with older versions of the application
  * create and load project templates
  * `[`pending`]` integration with online project library, sharing your drawings with ease

To report bugs or request a new feature go to [http://code.google.com/p/diy-layout-creator/issues/list Issues] page and create a new issue describing your problem or request.

To join the discussion or request technical assistance, use the dedicated [http://groups.google.com/group/diy-layout-creator Discussion Group].

===Want to contribute?===

If you want to help the DIYLC project, there are several things you can do:

  * Help with adding the information to the [Manual user manual].
  * Extend the component base, read [http://code.google.com/p/diy-layout-creator/wiki/ComponentAPI this wiki] to learn how to create new components.
  * Add a new functionality though plug-ins, read [http://code.google.com/p/diy-layout-creator/wiki/PluginAPI this wiki] to learn how to create new plug-ins.
  * If you are good with design, DIYLC could use a fancy splash screen and/or a new application icon in 16x16, 32x32 and 48x48 formats.
  * Consider making a small [https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=25161 PayPal donation].

===License information===

Source code is released under [http://www.gnu.org/licenses/quick-guide-gplv3.html GPL license] for non-commercial projects only. Contact the project owner to obtain a licence in case you plan to use the source code, or any part of it, in commercial purposes.

===Brief project history===

  * *Version 3* is the current version and was re-written from scratch starting early 2010, but this time as an open source project. It incorporates all the ideas that were accumulated over years and also better code architecture. That should provide better user experience, less bugs and code that's easier to maintain and extend.

  * *Version 2* was re-written from scratch in Java mid 2007 and is platform independent. Unfortunately, it's not very fast and is not backward compatible with version 1 which means that it cannot open files created with version 1. It was my first ever Java project, so code is was so great which is why I gave it up at some point.

<p align="center"><a href="http://diy-fever.com/diylc/images/diylc2_screenshot.png"><img src="http://diy-fever.com/diylc/images/diylc2_screenshot-320x194.png"/></a></p>

  * *Version 1* started its life in May 2005 and was written in Delphi. As such, it only works on windows machines (or through emulators). There's a large collection of layouts submitted by users for this version which is why it's still kept around.

<p align="center"><a href="http://diy-fever.com/diylc/images/diylc_screenshot.png"><img src="http://diy-fever.com/diylc/images/diylc_screenshot-320x231.png"/></a></p>

===Credits===

  * Big thanks goes to folks from the following sites that helped with testing and ideas: [http://www.diystompboxes.com/smfforum/ DIY Stompboxes], [http://ax84.com/bbs AX84] and [http://freestompboxes.org Free Stompboxes].
  * I'm happy to report that DIYLC 3 is the fastest version ever. [http://www.yourkit.com/java/profiler/index.jsp YourKit Java Profiler] helped tremendously with memory and performance profiling and pointed me to places in the code that took longer to run or consumed more memory than I'd like them to. I strongly recommend this tool to anyone developing Java or .NET applications because it helps finding bottlenecks and allocation hot-spots very fast.<br><br>!YourKit is kindly supporting open source projects with its full-featured Java Profiler.<br>!YourKit, LLC is the creator of innovative and intelligent tools for profiling Java and .NET applications.<br>Take a look at !YourKit's leading software products: [http://www.yourkit.com/java/profiler/index.jsp YourKit Java Profiler] and [http://www.yourkit.com/.net/profiler/index.jsp YourKit .NET Profiler]
