

# Spotlight - Blogger Template
#### A Free Blogger Theme by Just A Guy Coding (justaguycoding.com)


Spotlight is a free Google Blogger Template theme. These notes explain how to install and configure the template with Blogger. 

The template `spotlight_template.xhtm` provided is an optimised xml file including everything required to install and run a blog on Google Blogger. See the demonstration website for how that Blog may look. Details are given below on how to install (apply) the template and customise it. 

### Demonstration Website

You can find the demonstration website at https://spotlight-blogtemplate.blogspot.com.

### Prerequisites

For a fully live website you will need:

- A Google Blogger Blog Account and an empty Blog.
- Content for 4 posts:
  - 1 Feature post. Inc. Image (optional).
  -  2 Minor Feature posts (optional), Inc. Images (optional).
  - 1 standard post.

### Applying the template
* Log in to Blogger and select the Blog to modify.
* From Blogger's control panel, select **Theme**, click the arrow to the right of Customize and select **Edit HTML**.
* Open `spotlight_template.xhtml`, copy the content (Ctrl+C) it.
* On Blogger, inside the HTML editor, Select All (Ctrl+A), then Paste (Ctrl V) to paste  `spotlight_template.xhtml`over the top.
* Save the template using the disk icon to the top right.
* The template is now installed must. Next add content and configure the template.

### Adding Content

#### Posts

* Log in to Blogger and select the Blog to modify.

* From Blogger's control panel, select **Posts**, click **New Post**.

* Add the 2-4 initial blog posts:

  - The Feature Post - add the title and content. Give it the label `FeatureMain`. The title and content will be displayed on the home page's banner up to the jump break. The first image applied to the post will appear as the image shown on the banner (jumbotron) displayed on the theme's home page.

  - The Minor Feature Posts (optional). Give the post a label of `FeatureMinor1` or `FeatureMinor2` for it to show on the left or right respectively. Giving the post a second label will display it as the category name on the card. Example:

    ![image-20201001171025086](.\_documentation\image-20201001171025086-1601669456622.png)

    The first image applied to the post will appear as the image shown on the card displayed on the theme's home page.
  
  - An ordinary post - add the title and content. This will appear on the home page, with text displaying up to the jump break. The first image applied to the post will appear as the image shown in the home page summary.

#### Pages

As per normal using blogger. From the control panel, click pages, new page and enter the content for a new page.


### Navigation
To add a page or a link to the navigation menu, log in to Blogger control panel, view the blog and click the edit icon next to Spotlight next to the navigation menu. Highlighted below:

<img src=".\_documentation\image-20200930151948103.png" alt="image-20200930151948103" style="zoom:33%;" />

This will pop up the *Page List* widget editor, allowing you to select a page from the Blog or enter an external link to show on the navigation menu. Click Save to update the blog.

<img src=".\_documentation\image-20200930152146011.png" alt="image-20200930152146011" style="zoom:33%;" />

### Blog Archive Sidebar

Past blog posts are shown in the *Archive Widget* to the right in the side bar, shown below.

<img src=".\_documentation\image-20201002212049987.png" alt="image-20201002212049987" style="zoom:50%;" />

The theme only supports the Hierarchy style. You may editing this widget, by clicking the edit icon, will allow you to change the Title.

### Comments

Comment Locations: Embedded|Full Page|None are supported. Popup will open a new browser tab and is not fully supported.

### Search

Basic search functionality comes configured by default using Blogger's search widget.

### Footer

There are two vertical lists of links in the footer. These are implemented as Page List widgets and can be edited using there individual edit icons. Add and remove pages in the same way as described for Navigation.

### Custom 404 Message

Searches for pages or posts which do not exists will result in a "Sorry. The page you requested is not available."

This can be changed in the theme's HTML. Read Applying the the Template to find out how to edit the HTML. To do this search for *spotlightOptions* and amend the text on the right-hand side of the colon`'error-message-404' : "Sorry. The page you requested is not available."` .

### Custom Colours

The Theme's colours and styles can be tweaked Under Theme > Customise.

<img src=".\_documentation\image-20201002213002753.png" alt="image-20201002213002753" style="zoom:33%;" />

### Trouble Shooting

- **The Features are not showing**. Blogger will only only show N number of posts on the home page, in order of the most recent posts (using published by date), according to the *Max posts shown on main page* setting. If your Blog is set to show N posts and your Features are N+1 in the list the theme will not be able to show them. Resolve this by a) increasing the number of posts Blogger shows, or b) updating your post to give it a more recent published by date, adding it back to the list of most recent posts.

### License

Apache License Version 2.0. See https://choosealicense.com/licenses/apache-2.0/ for the details.



