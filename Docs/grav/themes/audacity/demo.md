---
title: Audacity: Recreating the Demo
description: Your Guide to Recreating Elements of the Audacity Demo for Grav
breadcrumb: /grav:Grav/!themes:Themes/audacity:Audacity

---

Introduction
-----

Recreating features of the demo site used to show off some of the more interesting aspects of Audacity can be done fairly easily. All you need is the right plugins and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site.

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Audacity Theme.

Keep in mind that a lot of the detail that makes our demos look so good is the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the Grav back end. We have added most of these elements into the theme's core files in order to make them easily accessible without having to edit any code.

>> NOTE: We recommend downloading a copy of the RocketLauncher whenever you are attempting to replicate demo content. This allows easy referencing, whether on your site in a subdirectory, development server, or on a localhost. This will allow you to see all of our demo content in context, making it easier to replicate.

Particles
-----

* Theme Particles
    - [Audio Player](particle_audio.md)
    - [Block Content](particle_block.md)
    - [Calendar](particle_calendar.md)
    - [Contact](particle_contact.md)
    - [Content List](particle_contentlist.md)
    - [Content Tabs](particle_contenttabs.md)
    - [Feature Tabs](particle_featuretabs.md)
    - [Grav Content](particle_grav.md)
    - [Headlines](particle_headlines.md)
    - [Horizontal Menu](particle_horizontalmenu.md)
    - [Image Slider](particle_imageslider.md)
    - [Image Grid](particle_image.md)
    - [Info List](particle_info.md)
    - [Link Tabs](particle_linktabs.md)
    - [Lists](particle_lists.md)
    - [MailChimp](particle_mailchimp.md)
    - [Mosaic](particle_mosaic.md)
    - [Pricing Table](particle_pricing.md)
    - [Progress Bar](particle_progressbar.md)
    - [Promo Image](particle_promoimage.md)
    - [Search](particle_search.md)
    - [Showcase](particle_showcase.md)
    - [Simple Counter](particle_simplecounter.md)
    - [Slider](particle_slider.md)
    - [Social](particle_social.md)
    - [Strips Slider](particle_stripsslider.md)
    - [Tab Image](particle_tabimage.md)
    - [Testimonial](particle_testimonial.md)
    - [Video](particle_video.md)
    - [Vertical Menu](particle_verticalmenu.md)
* Core Particles
    - [Logo](http://docs.gantry.org/gantry5/particles/logo)
    - [Menu](http://docs.gantry.org/gantry5/particles/menu-control)
    - [To Top](http://docs.gantry.org/gantry5/particles/to-top)
    - [Social](http://docs.gantry.org/gantry5/particles/social)
    - [Positions](http://docs.gantry.org/gantry5/particles/position)
    - [Spacer](http://docs.gantry.org/gantry5/particles/spacer)
    - [Mobile Menu](http://docs.gantry.org/gantry5/particles/mobile-menu)
    - [Custom HTML](http://docs.gantry.org/gantry5/particles/custom-html)
    - [Page Content](http://docs.gantry.org/gantry5/particles/page-content)
    - [System Messages](http://docs.gantry.org/gantry5/particles/system-messages)

Recreating the Front Page
-----

The front page of the Audacity demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the theme. It is because of this that several layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Audacity demo.

Home Page Layout Presets
-----

![Layout Presets](assets/layout_presets.jpg)

We have included a layout preset for the home page within the theme if needed. The **Home** preset includes all of the particle-based home page demo content so you can hit the ground running with a copy of our demo to work from loaded directly into the layout.

You can access the presets by selecting **Load** in the **Layout Manager**.

Menu Editor
-----

![](assets/menu_1.jpg)

Audacity has its own built-in Menu Editor which takes full advantage of Grav's menu system, taking your Grav menus and enhancing them before passing them to visitors on the front end. Any changes made in the Menu Editor will only affect the way it appears to the visitor, and not the way Grav sees or uses it.

You can access the Gantry Menu Editor by navigating to **Admin > Gantry 5 > Menu**. You can find out more about navigating and using the Gantry Menu Editor [in our documentation](http://docs.gantry.org/gantry5/configure/menu-editor).

Assignments
-----

![](assets/assignments_1.jpg)

Assignments are also managed in the Gantry Administrator. This administrative panel enables you to assign theme outlines to specific menu items, pages, and other areas of your site. By navigating to **Admin > Gantry 5** and selecting an outline other than the **Base Outline**, you will be able to assign that outline by navigating to the **Assignments** panel. Simply switch any menu items to on (green) that you want to assign that outline to. In the case of the Home page, this would be your default Home page in your default (main) menu.
