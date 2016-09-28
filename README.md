# <a name="myrecipes---simple-fast-awesome"></a>myRecipes - Simple, Fast, Awesome 

Wordpress Recipes Theme.
**Demo: [http://myrecipes.stegaru-dev.com/](http://myrecipes.stegaru-dev.com)**

**myRecipes is a fully responsive, and beautifully designed WordPress theme for recipes related websites. This theme makes it very easy to share cooking knowledge and it is perfect for professional Chefs and Cooking Experts.**

This theme is fully hand coded and its HTML is written keeping in mind your sites good ranking on search engines. It features Method and Ingredients approaches which comes very handy for your visitors to easily follow your recipes.

- [Installation](#installation)
- Setup / Customize
  - [Homepage](#homepage)
     - [Featured Recipes](#featured-recipes)
     - [Recent Recipes](#recent-recipes)
     - [Recent Blog Posts](#recent-blog-posts)
     - [Footer Social Buttons](#footer-social-buttons)
  - [My Recipes page](#my-recipes-page)
    - [Single Recipe page](#single-recipe-page)
  - [Blog page](#blog-page)
  - [Contact page](#contact-page)
  - [Sidebars & Widgets](#sidebar--widgets)
- [Add recipes](#add-recipes)
  - [Is Featured?](#is-featured) 
  - [Appear on homepage](#appear-on-homepage)
  - [Ingredients](#ingredients)
  - [Method](#method)
  - [Cooking time](#cooking-time)
  - [Difficulty](#difficulty-level)
  - [Serves](#serves)
  - [Gallery](#gallery)
  - [Recipe description](#recipe-description)


# Installation <a name="installation"></a>

Before you install theme, make sure your installed Wordpress version is 4 or higher. You also need to have PHP 5 or higher versions (recommended is php 5.3+) and MySQL 5.0 in order for myRecipes to function correctly. There are two ways to install myRecipes. 

### Installing By FTP

We suggest you should upload it via FTP. 

> Find out more about how to use FTP by visiting this link:
> http://codex.wordpress.org/FTP_Clients

Unzip the myRecipe theme and, using the Ftp program, transfer this folder to the Wordpress installation theme root directory:  **/wp-content/themes**.

> Learn from Wordpress Official Document about installing theme with FTP
> client or with cPanel: http://codex.wordpress.org/Using_Themes

#### Installing via Wordpress Theme Administration Panel
myRecipes can also be installed by using the Add New Themes option found in *Appearance* -> *Themes* in the dashboard menu.

After being uploaded to your theme folder, login to WP admin panel, go to Appearence -> Themes and activate myRecipes theme.

This theme requires the **"Advanced Custom Fields"** and **"Contact Form 7"** plugins. It also recommends **"Add This"** plugin (for social media buttons).
Install these plugins by clicking the "Begin installing plugins" link and let the Wordpress install them automatically. You can also install the plugins manually (plugins attached to the theme download file). Just unzip and move each plugin to the /plugins/ folder of your wordpress platform, the go to the admin panel, plugins section, and activate previously added plugins.

Once activated, the theme automatically creates:

- myRecipes Homepage layout (see [Homepage setup](#homepage))
- My recipes page (this is a collection page of all your recipes)
- Blog page (displays the posts you add under "Blog posts")

Now you are ready to start your recipes website using myRecipes!

**[navigate to top ^](#myrecipes---simple-fast-awesome)**

# Setup / Customize

## <a name="homepage"></a>Homepage
After you activate the theme, you'll see a listing of your posts on homepage. 

Now, you may want a nicer look for your homepage ([see demo here](http://myrecipes.stegaru-dev.com) or check screenshot bellow). 

![Homepage layout](http://myrecipes.stegaru-dev.com/theme_assets/homepage-layout.jpg)

The "myRecipes Homepage" layout consists of:

 - "[Featured Recipes](#featured-recipes)" section
 - "[Recent Recipes](#recent-recipes)" section
 - "[Blog](#recent-blog-posts)" section

In order to activate that layout, go to the admin panel, Settings -> Reading -> Front page displays. Select "myRecipes Homepage". Save the changes.

![Homepage layout](http://myrecipes.stegaru-dev.com/theme_assets/activate-homepage-layout.jpg)

**[navigate to top ^](#myrecipes---simple-fast-awesome)**


### <a name="featured-recipes"></a>Featured recipes
This is the top hero section of the homepage. It can feature up to 3 posts at your choice.

![Homepage layout](http://myrecipes.stegaru-dev.com/theme_assets/homepage-featured-section.jpg) 

Edit this section by going to admin panel, Dashboard -> Customize your site -> Homepage settings -> Hero Section.

![Homepage layout](http://myrecipes.stegaru-dev.com/theme_assets/edit-featured-section.jpg) 

You can change:

- the section title (default: "Featured recipes")
- section's background color
- section's background image
- section's text color

**[navigate to top ^](#myrecipes---simple-fast-awesome)**

### <a name="recent-recipes"></a>Recent recipes
This section appears on homepage. It shows the latest added recipes. You can allow as many recipes as needed. By default there will be listed 4 recipe items.
![Homepage recent recipes](http://myrecipes.stegaru-dev.com/theme_assets/homepage-recent-recipes.jpg)

Edit this section by going to admin panel, Dashboard -> Customize your site -> Homepage settings -> Recent recipes section.

![Homepage layout](http://myrecipes.stegaru-dev.com/theme_assets/edit-recent-recipes.jpg)

You can change:

- the section title (default "Recent recipes")
- recipes number (default 4)
- how many recipes per row displayed (default 4)
- image size (default "Thumbnail")

**[navigate to top ^](#myrecipes---simple-fast-awesome)**

### <a name="recent-blog-posts"></a>Recent blog posts
When you add a new article in the blog section, a shortcut to the blog post will appear on the homepage, under the **Blog** section.

Edit this section by going to admin panel, Dashboard -> Customize your site -> Homepage settings -> Recent blog posts.

![Homepage layout](http://myrecipes.stegaru-dev.com/theme_assets/edit-homepage-blog.jpg)

You can change:
- section title (default "Blog")
- displayed posts (default "Two posts")

**[navigate to top ^](#myrecipes---simple-fast-awesome)**

### <a name="footer-social-buttons"></a>Footer social buttons
Edit this section by going to admin panel, Dashboard -> Customize your site -> Social buttons.

Add your social pages links. The social buttons will appear in footer.

![Homepage layout](http://myrecipes.stegaru-dev.com/theme_assets/footer-social.jpg)

**[navigate to top ^](#myrecipes---simple-fast-awesome)**


## <a name="my-recipes-page"></a>My recipes page
![Homepage layout](http://myrecipes.stegaru-dev.com/theme_assets/page-myrecipes.jpg)

Go to Dashboard -> Customize my site -> Recipes -> All recipes page

You can change:

- The page layout (default is "With sidebar")
- Title section's background color
- Title section's background image

![Homepage layout](http://myrecipes.stegaru-dev.com/theme_assets/page-myrecipes-edit.jpg)

**[navigate to top ^](#myrecipes---simple-fast-awesome)**


## <a name="single-recipe-page"></a>Single recipe page
![Homepage layout](http://myrecipes.stegaru-dev.com/theme_assets/page-recipe.jpg)

Go to Dashboard -> Customize my site -> Recipes -> Single recipe page

You can change:

- The page layout (default is "With sidebar")
- Show article author (checked by default)
- Show difficulty (checked by default)
- Show cooking time (checked by default)
- Show publish date (checked by default)

![Homepage layout](http://myrecipes.stegaru-dev.com/theme_assets/page-recipe-edit.jpg)

**[navigate to top ^](#myrecipes---simple-fast-awesome)**



## <a name="blog-page"></a>Blog page
Displays a list of your blog entries.

You can change the page layout be **"Classic"**, **"Grid"**, **"Rows"**

To do so, go to Dashboard -> Customize my site -> Blog settings

You can also change the page hero's background color and background image.

![Homepage layout](http://myrecipes.stegaru-dev.com/theme_assets/page-blog-edit.jpg)

**[navigate to top ^](#myrecipes---simple-fast-awesome)**


## <a name="contact-page"></a>Contact page
Go to "Contact" section, copy the shortcode of the existing form.

![Homepage layout](http://myrecipes.stegaru-dev.com/theme_assets/contact-copy-shortcode.jpg)

Go to Pages and create the Contact page. Use the "Contact page" template. Paste the previously copied shordcode in the description area. Publish.

![Homepage layout](http://myrecipes.stegaru-dev.com/theme_assets/contact-copy-paste.jpg)

You can add the contact page to the main menu by editing Menus under Appearance section (or via Customizer).

**[navigate to top ^](#myrecipes---simple-fast-awesome)**

# <a name="add-recipes"></a>Add recipes

Go to Posts -> Add new.

![Homepage layout](http://myrecipes.stegaru-dev.com/theme_assets/post-add-new.jpg)

You'll see a few groups of fields there. Go through and add your recipe ingredients, method, photo gallery, description and make sure you pick a nice featured image.
Select/Create the category you want the recipe to be displayed in and hit the Publish button.

![Homepage layout](http://myrecipes.stegaru-dev.com/theme_assets/post-create.jpg)

Let's see what each post field means.

### <a name="is-featured"></a>Is Featured?
Check that box and your recipe will appear in the "Featured recipes" section in homepage. 

**[navigate to top ^](#myrecipes---simple-fast-awesome)**

### <a name="appear-on-homepage"></a>Appear on homepage?
If you opt for this, the recipe will be displayed on homepage, under the "Recent Recipes" section.

**[navigate to top ^](#myrecipes---simple-fast-awesome)**

### <a name="ingredients"></a>Ingredients
Start adding the recipe ingredients, one by one, by clicking the "Add ingredient" button.
This will genereate the "Ingredients" widget on your recipe page. Feel free to reorder the ingredients list by dragging the rows up/down with your cursor.

**[navigate to top ^](#myrecipes---simple-fast-awesome)**

### <a name="method"></a>Method
Explain your recipe, step by step, by adding action items in the method list. You can reorder the steps list by dragging the items up/down with your cursor.

**[navigate to top ^](#myrecipes---simple-fast-awesome)**

### <a name="cooking-time"></a>Cooking time
If completed, that value will appear in the recipe page, right bellow the title.

**[navigate to top ^](#myrecipes---simple-fast-awesome)**

### <a name="difficulty-level"></a>Difficulty level
Give your readers and insight of the recipe complexity. If completed, that value will appear in the recipe page, right bellow the title.

**[navigate to top ^](#myrecipes---simple-fast-awesome)**

### <a name="serves"></a>Serves
How many people serves this recipe, based on ingrediens quantities, etc. If completed, that value will appear in the recipe page, right bellow the title.

**[navigate to top ^](#myrecipes---simple-fast-awesome)**

### <a name="gallery"></a>Gallery
Select the recipe pictures from Media Library, or upload. Feel free to add a caption to each picture. It'll be displayed right under the picture. Once added to the gallery, you can reorder the photos appearance order by dragging each one with your cursor.

**[navigate to top ^](#myrecipes---simple-fast-awesome)**

### <a name="recipe-description"></a>Recipe description
Write the recipe intro/description. This is the section you start the recipe with. It appears above the Ingredients and Method widgets (if completed).

**[navigate to top ^](#myrecipes---simple-fast-awesome)**

## <a name="sidebar--widgets"></a>Sidebar & Widgets
Besides the default sidebar, myRecipes theme has three more dynamic sidebars:

- Blog sidebar (appears on blog pages)
- Recipe page sidebar (appears on recipe pages)
- Search page sidebar (appears in the search results page)

You can easily add widgets to the sidebars. myRecipe theme comes with three custom widgets:

- myRecipes Categories
- myRecipes Recent Blog Posts
- myRecipes Recent Recipes

Feel free to drag any of the widgets over the sidebars as needed.

![Homepage layout](http://myrecipes.stegaru-dev.com/theme_assets/sidebars-widgets.jpg)


