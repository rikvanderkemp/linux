# What makes Linux different from X

Linux is part of smaller blocks (like Lego) that will make an entire Operating System, Linux itself is _just_ the
kernel. This makes understanding Linux quite different from understanding Windows or macOS. I believe that, before you
start your adventure, that you understand the difference.

With Windows/ macOS, you will get a full desktop experience right out of the gates.
Everything is pre-configured for you so that you can start straight away doing whatever you want.

Let's stop and think about that for a second. When you buy a laptop, it contains many components such as (but not
limited to:

- A screen
- A keyboard
- A touchpad
- Speakers
- A video card
- A harddrive
- etc

And, aside from Apple stuff, you will have thousands of vendors providing these little components. Each component on
its own is not much, but when they work together it's like the biggest orchestra in the world playing the most
wonderful music.

Well, IF you have an operating system that understands all those thousands of vendors and knows who to talk to them
and let them work together.

And that is not an easy feat. You need to start somewhere and to be able to support every vendor, and every little
component will take you quite literally forever.

Thankfully, we don't need to do this ourselves, we have Operating Systems (Distributions or Distros in Linux) that 
will do this for us.
And thankfully, 
vendors will create so-called driver support for those Operating Systems.

In this living document, I will only compare with two other Operating Systems Windows and macOS. Which on the
surface do the same thing but are actually hugely different. And these differences will also be important in learning
about linux.

In short, Apple (the developer of macOS) creates its own systems with its own hardware. Thus, the
support for their own laptops / desktops and tablets is unparalleled. Where macOS now supports about X video-cards or
processors, you'll probably need to tenfold it at least when you are developing for Windows or Linux.

Now, not every support for every component is written by Microsoft for Windows, that's what drivers are for. But to
make Windows appealing, you need to support at least **most** of it out-of-the-box somehow so customers don't buy
computers that are broken from the beginning.

In the case of Linux, most of the support for most of the components is written into the Kernel. The very first thing
you need for a full Linux desktop experience.

Long story short; to get started with your Linux adventure, you need to know that Linux is **not the actual desktop
experience** but rather the kernel that will drive it. Alongside, you will need many building blocks to actually
call it an operating system.

- You'll need a bootloader
- A kernel
- An initialization system
- Something that can handle background processes (Daemons in linux world)
- Some kind of graphics server
- A desktop environment

Which, if you remember your Windows installation or macOS, you don't need to worry about. This is all provided for
you, and you'll have no choices in either of them. And for about 99.9% of the people that is actually fine!

But don't worry in later chapters, you will find the magic of distributions (distros).
