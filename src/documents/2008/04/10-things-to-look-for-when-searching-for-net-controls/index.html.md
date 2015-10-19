---
layout: post
title: 10 things to look for when searching for .NET controls
date: 2008-04-10
---

One of the best ways to speed up the development of that project you're working on is to use third party libraries controls. In particular, .NET has had an absolutely amazing number of third party controls. Microsoft has made it amazingly simple to build re-usable code.

![image](gears.png) 

Buying third party controls will allow you to focus on your unique functionality without reinventing code that others have already planned, tested, and are maintaining.

Here are the top things that I look for, in no particular order:

1.  **Does the author have a demo page or application?** If I'm looking for a type of control with a lot of competition, I'll use this to immediately exclude some of them. If you have a unique control and I don't have many options, I'll probably still check it out, but you better hope I can set it up quickly.
2.  **Is the control reliable?** Can I break it? Once your software goes out, the users are equivalent to monkeys in many respects. If there is a bug in a control you're using, they'll find it. I would rather not have to deal with that, so I take a good look at reliability.
3.  **Does the control play well with others?** Some control manufacturers build amazing controls that work great with the other controls they sell. The problem is, if you mix and match, they often don't play well. With ASP.NET controls, take a look at the rendered output and make sure it's elegant and well thought out.
4.  **How much does it cost?** This is obviously going to factor in different amounts based on your project and situation. If the control costs less or more than you expect, try to figure out the root cause. If it's expensive, I would expect amazing support and documentation. If it's cheap, I would make sure that it's because the control focuses on doing what it is supposed to. For the price, the control needs to _save_ me time, which should translate into savings for the project.
5.  **What kind of support is available?** Great support can make up for a lot of shortcomings. I've used controls that were buggy, but I basically had one of the control developers holding my hand. They were able to fix it quickly, or tell me what I was doing wrong. Support can come in a variety of ways:
        *   Phone support - Is it paid or free? If you have to pay, is it per incident?
        *   Email support
        *   Forums with support monitoring - How actively monitored is it? Have everyone else's questions been answered.
6.  **Is the author going to be around tomorrow?** If you want to be able to get updates or support, will the author still be around to provide them?
7.  **Does the control take over my computer?** I don't like controls that are much more than a DLL, or a set of files. I don't like having to "install" your control on my computer. If it's difficult to install, the probably means it going to be difficult to figure out how to deploy it. I want XCOPY deployment. I don't want to mess around with GAC registration and manual licenses.
8.  **Is the license overly restrictive?** Many licenses require your first born child to use them in a real world. I prefer a license that lets me use it in pretty much any way I want. That's why I'm spending the money. I don't have any problem with tiers (per site, per server, etc). If you do have licensing tiers, allow me to upgrade and pay the difference. I also want to be able to have all of our developers actually compile the code without having to buy additional licenses. Some controls require a license for each developer, regardless of whether or not they're working on the feature that uses it.
9.  **How much are upgrades?** I have seen a few controls that offer free upgrades for life. Personally, I'm about twice as likely to buy those. Not having to justify paying for an upgrade is great. Companies like to buy things and forget about them. Even if it's not free to upgrade, it's nice getting good discounts for being an existing customer.
10.  **Is the control easy to use?** This is obviously critical since you're buying the control to avoid having to write the functionality yourself. If it takes 10 hours for you to write the code to use the control, and it would have taken 10 hours to write everything yourself, you probably haven't gained anything. 

Here are some great places to get started:

*   [ASP.NET Control Gallery](http://www.asp.net/community/control-gallery/)
*   [WindowsForms.NET Control Gallery](http://windowsclient.net/downloads/folders/controlgallery/default.aspx)