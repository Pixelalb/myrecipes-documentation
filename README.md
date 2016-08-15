# myRecipes - Simple, Fast, Awesome 

Wordpress Recipes Theme

- [Installation](#installation)
- Setup / Customize
  - [Homepage](#homepage)
     - [Featured Recipes](#featured-recipes)
     - [Recent Recipes](#recent-recipes)
     - [Blog Posts](#recent-blog-posts)
     - [Footer Social Buttons](#footer-social-buttons)
  - [My Recipes page](#my-recipes-page)
    - [Single Recipe page](#single-recipe-page)
  - [Blog page](#blog-page)
  - [Contact page](#contact-page)
  - [Sidebars & Widgets](#sidebar--widgets)
- [Add recipes](#add-recipes)


# Installation

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
Install these plugins manually or click the "Begin installing plugins" link and let the Wordpress install them automatically.

Once activated, the theme automatically creates:

- myRecipes Homepage layout (see [Homepage setup](#homepage))
- My recipes page (this is a collection page of all your recipes)
- Blog page (displays the posts you add under "Blog posts")

Now you are ready to start your recipes website using myRecipes!

**[navigate to top ^](#myrecipes---simple-fast-awesome)**

# Setup / Customize

## Homepage
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


### Featured recipes
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

### Recent recipes
![Homepage recent recipes](http://myrecipes.stegaru-dev.com/theme_assets/homepage-recent-recipes.jpg)

Edit this section by going to admin panel, Dashboard -> Customize your site -> Homepage settings -> Recent recipes section.

![Homepage layout](http://myrecipes.stegaru-dev.com/theme_assets/edit-recent-recipes.jpg)

You can change:

- the section title (default "Recent recipes")
- recipes number (default 4)
- how many recipes per row displayed (default 4)
- image size (default "Thumbnail")

**[navigate to top ^](#myrecipes---simple-fast-awesome)**

### Recent blog posts
Edit this section by going to admin panel, Dashboard -> Customize your site -> Homepage settings -> Recent blog posts.

![Homepage layout](http://myrecipes.stegaru-dev.com/theme_assets/edit-homepage-blog.jpg)

You can change:
- section title (default "Blog")
- displayed posts (default "Two posts")

**[navigate to top ^](#myrecipes---simple-fast-awesome)**

### Footer social buttons
Edit this section by going to admin panel, Dashboard -> Customize your site -> Social buttons.

Add your social pages links. The social buttons will appear in footer.

![Homepage layout](http://myrecipes.stegaru-dev.com/theme_assets/footer-social.jpg)

**[navigate to top ^](#myrecipes---simple-fast-awesome)**


## My recipes page
![Homepage layout](http://myrecipes.stegaru-dev.com/theme_assets/page-myrecipes.jpg)

Go to Dashboard -> Customize my site -> Recipes -> All recipes page

You can change:

- The page layout (default is "With sidebar")
- Title section's background color
- Title section's background image

![Homepage layout](http://myrecipes.stegaru-dev.com/theme_assets/page-myrecipes-edit.jpg)

**[navigate to top ^](#myrecipes---simple-fast-awesome)**


## Single recipe page
![Homepage layout](http://myrecipes.stegaru-dev.com/theme_assets/page-recipe.jpg)

Go to Dashboard -> Customize my site -> Recipes -> Single recipe page

You can change:

- The page layout (default is "With sidebar")
- Show article author (checked by default)
- Show dificulty (checked by default)
- Show cooking time (checked by default)
- Show publish date (checked by default)

![Homepage layout](http://myrecipes.stegaru-dev.com/theme_assets/page-recipe-edit.jpg)

**[navigate to top ^](#myrecipes---simple-fast-awesome)**



## Blog page
Displays a list of your blog entries.

You can change the page layout be **"Classic"**, **"Grid"**, **"Rows"**

To do so, go to Dashboard -> Customize my site -> Blog settings

You can also change the page hero's background color and background image.

![Homepage layout](http://myrecipes.stegaru-dev.com/theme_assets/page-blog-edit.jpg)

**[navigate to top ^](#myrecipes---simple-fast-awesome)**


## Contact page
Go to "Contact" section, copy the shortcode of the existing form.

![Homepage layout](http://myrecipes.stegaru-dev.com/theme_assets/contact-copy-shortcode.jpg)

Go to Pages and create the Contact page. Use the "Contact page" template. Paste the previously copied shordcode in the description area. Publish.

![Homepage layout](http://myrecipes.stegaru-dev.com/theme_assets/contact-copy-paste.jpg)

You can add the contact page to the main menu by editing Menus under Appearance section (or via Customizer).

**[navigate to top ^](#myrecipes---simple-fast-awesome)**

# Add recipes

Go to Posts -> Add new.

![Homepage layout](http://myrecipes.stegaru-dev.com/theme_assets/post-add-new.jpg)

You'll see a few groups of fields there. Go through and add your recipe ingredients, method, photo gallery, description and make sure you pick a nice featured image.
Select/Create the category you want the recipe to be displayed in and hit the Publish button.

![Homepage layout](http://myrecipes.stegaru-dev.com/theme_assets/post-create.jpg)

Let's see what each post field means.

### Is Featured?
Check that box and your recipe will appear in the "Featured recipes" section in homepage. 

**[navigate to top ^](#myrecipes---simple-fast-awesome)**

### Appear on homepage?
If you opt for this, the recipe will be displayed on homepage, under the "Recent Recipes" section.

**[navigate to top ^](#myrecipes---simple-fast-awesome)**

### Ingredients
Start adding the recipe ingredients, one by one, by clicking the "Add ingredient" button.
This will genereate the "Ingredients" widget on your recipe page. Feel free to reorder the ingredients list by dragging the rows up/down with your cursor.

**[navigate to top ^](#myrecipes---simple-fast-awesome)**

### Method
Explain your recipe, step by step, by adding action items in the method list. You can reorder the steps list by dragging the items up/down with your cursor.

**[navigate to top ^](#myrecipes---simple-fast-awesome)**

### Cooking time
If completed, that value will appear in the recipe page, right bellow the title.

**[navigate to top ^](#myrecipes---simple-fast-awesome)**

### Dificulty level
Give your readers and insight of the recipe complexity. If completed, that value will appear in the recipe page, right bellow the title.

**[navigate to top ^](#myrecipes---simple-fast-awesome)**

### Serves
How many people serves this recipe, based on ingrediens quantities, etc. If completed, that value will appear in the recipe page, right bellow the title.

**[navigate to top ^](#myrecipes---simple-fast-awesome)**

### Gallery
Select the recipe pictures from Media Library, or upload. Feel free to add a caption to each picture. It'll be displayed right under the picture. Once added to the gallery, you can reorder the photos appearance order by dragging each one with your cursor.

**[navigate to top ^](#myrecipes---simple-fast-awesome)**

### Recipe description
Write the recipe intro/description. This is the section you start the recipe with. It appears above the Ingredients and Method widgets (if completed).

**[navigate to top ^](#myrecipes---simple-fast-awesome)**

## Sidebar & Widgets
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


