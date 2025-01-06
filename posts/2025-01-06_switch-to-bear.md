---
title: Switching to Bear
link: switching-to-bear
published_date: 2025-01-06 13:14
tags: meta
make_discoverable: true
---

I will preface this post by stating that this is not going to be a personal website where I will be posting about jumping from one blogging platform to another every few months. This note is a reassurance to any reader out there (*hello?*) and a reminder to myself.

Last year, I started to blog on [Ghost](https://ghost.org/) because it was highly recommended by various "Top 10" lists for current best blogging platforms. And I was interested in trying it out for myself as I vaguely remember the success of their Kickstarter campaign way back in 2013 for its goal of being "just a blogging platform."

It was fine. Until it wasn't.

Over the past couple of months, it seemed like I had a growing list of friction points and increasing dissatisfaction with using Ghost. Here are some examples:
- No centralized media management for handling assets.
- Theme development and handling is cumbersome.
  - Very limited options through their `@config` property for theme development.
  - Uploading a zip folder to change your website theme is a very archaic and outdated process to me. It reminds me of using FTP which is a turn-off for me.
- There was more friction than I would have liked with its editor.
  - My blogging workflow involves writing posts in Markdown in a separate text editor, pasting content into Ghost, and hitting publish. However, sometimes Ghosts' editor would not properly parse the pasted contents into a Markdown block and would require manual intervention to fix.
  - From this experience, I've come to realize that I am not a fan of block/card editors.
- Constant nudges towards monetization through memberships/newsletters/subscriptions were annoying.
  - I understand that modern blogging is usually about the *hustle* nowadays, and Ghost has evolved to fulfill those needs, but I want a place to write and yell into the void in peace. You know what I'm saying?

For the past several weeks, I have been casually keeping an eye out for alternative blogging platforms that fulfill my needs. Here are some platforms that caught my eye:
- [Mataroa](https://mataroa.blog/)
  - I liked the features and admire the commitment to business [transparency](https://mataroa.blog/modus/transparency/).
  - However, its limited media uploads disqualified it from my options. In particular, the total image count of 1,000 would potentially be my concern in a few years.
- [Nucelo](https://www.nucelo.com/)
  - It has a very specific organization method for displaying your content which does not apply to me, specifically article- and project-based content.
  - It seems more like a personal portfolio/showcase website which happens to have a blogging feature than a focused blogging platform.
  - Not a fan of its icon-focused navigation.
- [Pika](https://pika.page/)
  - Its WYSIWYG editor is not for me. Also, it can't parse Markdown tables.
  - It is a fairly new player in the blogging space with new features coming out every other week from its active development team. Currently, I would rather settle into a slightly more established platform. 
  - However, I would be interested to see its offerings in a couple of years.
- [Write.as](https://write.as/)
  - Honestly, I wasn't feeling it. 
  - Probably because I can only read "Write, Ass!" from the URL.

I have been focusing my search on simple blogging platforms rather than static site generators as I didn't want to be tinkering too much with setting up the website. Previously, I had used [Jekyll](https://jekyllrb.com/) and had sunk way too much time and energy into messing around with styling and adjusting templates. I know myself. I need certain limitations.

I've decided to switch to [Bear](https://bearblog.dev/) for the following reasons:
- Provides enough theming and styling options to my satisfaction.
- Allows me to set metadata through plain text through YAML front matter. 
  - Honestly, this is what primarily sold me as I dislike using date pickers, which are commonly found in other blogging platforms, as it reminds me of work calendars and setting meeting appointments.

```ymal
---
title: Switching to Bear
link: switching-to-bear
published_date: 2025-01-07 20:33
tags: meta
make_discoverable: true
---
```

- I like its implementation of previewing drafts before publishing. It displays your draft post with your theme's styling applied in a separate window.
- Built-in analytics is detailed enough that I can stop using [Umami](https://umami.is/) if I wanted.
- Public [roadmap](https://bear.nolt.io/roadmap) is appreciated.

Anyway, I have settled into using Bear for the forseeable future. I have transferred over my existing posts and pages. I have scrapped together a working theme for the front-end. Looking good so far. Probably going to do some few tweaks here and there over the next couple weeks, but there is only such much you can do — which is great!

Let's see how this goes. Hopefully, this bear doesn't go into hibernation, eh?

*I have made this individual post available on Bear's [Discovery](https://bearblog.dev/discover/) feed as an experiment. What is the purpose of this experiment? Good question. I don't know.*
