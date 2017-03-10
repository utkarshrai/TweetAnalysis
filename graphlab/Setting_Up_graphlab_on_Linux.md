## Graphlab on Linux

Which Linux are the commands for?
The OS I had is Kali Linux(Debian), the commands will be same for Ubuntu and afaik any other distribution.

<a href="http://imgur.com/oXGlZbf"><img src="http://i.imgur.com/oXGlZbf.png" title="source: imgur.com" /></a>

The first step is installing Anaconda 2(the link is given on the page)/3. I already had anaconda3 I still needed to fetch
some files to configure it.
 Let's execute from STEP 3.

Errors that might pop up: 

connda:command not found

FIX: Use command: export PATH = ~/anaconda/bin:$PATH

The "conda create -n gl-env python=2.7 anaconda=4.0.0" will require certain libraries. Let them install.

<a href="http://imgur.com/9JhRlhv"><img src="http://i.imgur.com/9JhRlhv.png" title="source: imgur.com" /></a>


pip install --upgrade --no-cache-dir https://get.graphlab.com/GraphLab-Create/2.1/your registered email address here/your product key here/GraphLab-Create-License.tar.gz

The tab is tp hide my keys, ping if you can still see them.
<a href="http://imgur.com/ePDHmGc"><img src="http://i.imgur.com/ePDHmGc.png" title="source: imgur.com" /></a>

IPython Dead Kernel Issue.

Even though you have Ipython and jupyter notebooks are displaying "Dead Kernel" amd "Kernal Restarting" all the time. 

You need to fix the broken kernel using 

<a href="http://imgur.com/c6UiCZO"><img src="http://i.imgur.com/c6UiCZO.png" title="source: imgur.com" /></a>

To test whether its working or not open a jupyter notebook and type in:

<a href="http://imgur.com/m1yzk03"><img src="http://i.imgur.com/m1yzk03.png" title="source: imgur.com" /></a>
