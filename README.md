# Let's Build A Dribbble Clone With Ruby on Rails

### What we will be building in depth

Our app will have the following features:

- The ability to create, edit, and destroy "shots" as well as like and unlike individual shots.
- User roles and authentication
- Drag and drop functionality
- Commenting functionality
- View counts/analytics
- A custom responsive shot grid UI using CSS Grid


### Getting started

Assuming you have rails and ruby installed on your machine you are ready to begin. From your favorite working directory using your favorite command line tool run the following:

```bash
$ rails new dribbble_clone
```

This should scaffold a new rails project and create the folder called `dribbble_clone`. 

To kick things off I've added all the gems from this project to my `Gemfile`. You can reference the repo if you haven't already to grab the same versions I've used here.

#### The Gem List

Our gem list has grown since the previous build. You'll find the larger your app becomes the more gems you'll need. 

- [CarrierWave](https://github.com/carrierwaveuploader/carrierwave) + [Mini Magick](https://github.com/minimagick/minimagick) - For image uploads and optimization
- [Devise](https://github.com/plataformatec/devise) - User authentication and roles
- [Guard](https://github.com/guard/guard) - Doing work to files as they change - A task runner of sorts
- [Guard Livereload](https://github.com/guard/guard-livereload) - Reloads the browser when files change combined with the Live Reload extension on your favorite browser.
- [Better Errors](https://github.com/charliesome/better_errors) - Displays better errors during development. 
- [Simple Form](https://github.com/plataformatec/simple_form) - Simpler forms in Rails
- [Bulma Rails](https://github.com/joshuajansen/bulma-rails) - My favorite CSS framework as of late based on Flexbox.
- [Impressionist](https://github.com/charlotte-ruby/impressionist) - We use this to get view counts on shots
- [Gravatar Image Tag](https://github.com/mdeering/gravatar_image_tag) - Easy way to grab a user's gravatar image based on their account email
- [Acts As Votable](https://github.com/ryanto/acts_as_votable) - Like and unlike shots
