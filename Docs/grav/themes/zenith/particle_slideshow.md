---
title: Zenith: Slideshow Particle
description: Your Guide to Recreating Elements of the Zenith Demo for Grav
breadcrumb: /grav:Grav/!themes:Themes/zenith:Zenith

---

## Introduction

![](assets/particle_slideshow1.png)

The **Slideshow** particle creates beautiful image slideshows that work perfectly at the top of your page.

Here are the topics covered in this guide:

* [Configuration](#configuration)
    - [Main Options](#settings)
    - [Item Options](#particle-item-options)
    - [Pages](#pages)
    - [Display](#display)

## Configuration

### Settings 

These options affect the main area of the particle, and not the individual items within. You can set the title of the particle, as well as give it an introductory paragraph here.

![](assets/particle_slideshow2.png)

| Option           | Description                                                                                              |
| :-----           | :-----                                                                                                   |
| Particle Name    | This is the name of the particle used for back end management. It does not appear on the front end.      |
| Content Source   | Choose between **Particle** and **Grav** as the content source for the particle.                    |
| Slide Height     | Set the height of each slide (in pixels)                                                                 |
| Prev / Next      | Add prev/next navigation to the slideshow.                                                               |
| Dots             | **Enable** or **Disable** dot navigation.                                                                |
| Autoplay         | **Enable** or **Disable** autoplay for the particle.                                                     |
| Autoplay Timeout | Set the time (in milliseconds) between slides in autoplay mode.                                          |
| Loop             | **Enable** or **Disable** looping slides.                                                                |
| Speed            | Set the transition speed (in milliseconds).                                                              |
| Touch Move       | **Enable** or **Disable** touch movements.                                                               |
| Overlay          | **Enable** or **Disable** the overlay.                                                                   |
| Direction        | Choose **Vertical** or **Horizontal** as the slide movement direction.                                   |
| Effect           | Choose a slideshow effect. Options include: **Slide**, **Fade**, **Cover Flow**, **Flip**, and **Cube**. |

### Particle Item Options

These items make up the individual featured items in the particle. Items in this section will only appear if **Particle** is selected as the **Content Source**.

![](assets/particle_slideshow3.png)

![](assets/particle_slideshow4.png)

| Option                 | Description                                                                            |
| :-----                 | :-----                                                                                 |
| Item Name              | This is the name of the item. This becomes the headline for the item on the front end. |
| CSS Classes            | Enter any CSS class(es) you wish to have apply to the item.                            |
| Image                  | Set an image for the item. This is the main image.                                     |
| BG Horizontal Position | Set the background image position horizontally.                                        |
| BG Vertical Position   | Set the background image position vertically.                                          |
| Top Title              | Enter a small title to appear on the front end.                                        |
| Main Title             | Enter a larger main title to appear on the front end.                                  |
| Button Text            | Enter text to appear in the button.                                                    |
| Button Link            | Enter a URL the button will send users to.                                             |
| Link Target            | Enter a target window for the link.                                                    |

### Pages

![](assets/particle_slideshow5.png)

| Option             | Description                                                                                  |
| :-----             | :-----                                                                                       |
| Categories         | Select the categories of pages this particle will display.                                   |
| Number of Pages    | Select the number of pages you would like the particle to fetch.                             |
| Start From         | Enter offset specifying the first article to return. The default is '0' (the first article). |
| Order By           | Choose the type of factor to order by.                                                       |
| Ordering Direction | Choose between **Ascending** and **Descending** as the article ordering method.              |

### Display

This section configures how posts are displayed.

![](assets/particle_slideshow6.png)

| Option        | Description                                                        |
| :-----        | :-----                                                             |
| Title         | **Show** or **Hide** the article's title.                          |
| Title Limit   | Enter the maximum number of characters in the title to display.    |
| Button Link   | **Show** or **Hide** the Button link.                              |
| Button Target | Choose whether to have the link open in a new tab or the same tab. |
| Button Target | Select the window target for the button link to open to.           |