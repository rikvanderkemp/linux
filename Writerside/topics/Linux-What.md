# Linux What?

I think the most important question you should ask yourself is why you are looking into Linux? What do you think
Linux will give you other Operating Systems won't give you?

I bet you will have a hard time coming up with reasons other than:

- It's free
- It's supposedly fast
- Uh, it's cool?
- OPEN SOURCE ALL THINGS!

And you might be right about most of those reasons.

Well, first of all, Linux is **not** what you are looking for. With just Linux, you will get nowhere. I know, I know
this is pretty much inaccurate. But it also isn't a lie.

You see, Linux is part of smaller blocks (like Lego) that will make an entire Operating System. And that is where
Linux is completely different to MacOs or Windows.

And it is actually **really important** to understand that this is fundamentally different which can make learning
about Linux even harder.

With Windows/macOS you will get a full desktop experience right out of the gates. Everything is pre-configured for
you so that you can start straight away doing whatever you want.

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

Thankfully, we don't need to do this ourselves, we have Operating Systems that will do this for us. And thankfully
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

But don't worry in later chapters you will find the magic of distributions (distros).

## So why choose Linux if Windows and macOs are complete?

This is a question I cannot answer for you! For me, using Linux means I can use my laptop or desktop PC exactly how
I want it. For me personally, it is definitely not **just about open source**. I see this mentioned so many times,
but it just isn't the main reason for me. I could do my work just fine on macOS or even on Windows. But being a
software engineer, I feel I'm always fighting an uphill battle. Running certain software designed for Linux
(such as server software, or other related applications) can be a drag. But in time it will work and it'll probably
function just fine.

But in the end, it's about convenience and being able to use my computer how I want. I grew up with computers thanks
to my dad, I started on the ZX Spectrum. I'm not scared about a terminal as I lived in DOS for a while, and
when the internet broke through, I was a full-blown Windows user with sidesteps to Apple! So I've seen a lot and
I've used many
Operating Systems. With that, I developed a way of working. I came to appreciate certain interface designs and came to
dislike others. I'm also not a typical geek. My keyboard layout is just qwerty, don't have a fancy diy keyboard and
still use the mouse, I could never go without how hard I tried.

I got stuck in a certain period, I think, and if my computers behave differently, or I can't quickly fix things, I get
annoyed. But Windows and macOS both were and are changing, renewing, etc. And those changes are great for
new users and not so great if you're stuck in your own ways. Instead of offering more customization, macOS saw fewer,
thinning-down applications increasingly to match their tablet inspired interfaces. Windows, I don't know what they
tried, some parts of Windows are still stuck in the past, while other parts increasingly got more confusing. Not
only that, but the amount of tracking and advertisements are getting out of hand.

And I suppose that's what bothers me. Microsoft is implementing so many tracking and adverts. macOS dumbing down on
everything along with so many paid applications for such simple tasks.  But I'll put aside my grievances
about these things for now. This is not the place.

In the end, it's all about the question; What do you want out of an operating system?

## Linux can be frustrating

Yes, there I said it. Linux can and will be frustrating when you first start to look into it. Consider what I wrote 
earlier. Linux in its core (the kernel) has supports for tons of components, but not all of them. All the support, 
or at least most of the support hangs in the balance of all those contributors making sure things 'just work'. 

Consider that you start as an audio card manufacturer, would you spend time and money on writing support for Linux if 
you know Windows and macOS are far more popular and in use at the moment? The answer in most cases is no. It's a 
shame but also the cold hard truth.

And yes, thankfully, the support for linux is increasing each year. Popularity is rising, thank you Steamdeck. But 
still, the user experience you will get is solely based on those thousands of contributors, who, mind you, don't have 
all the components to work with.

Consider what Linus Torvalds wrote when he brought out the first version of Linux
