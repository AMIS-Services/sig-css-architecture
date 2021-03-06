# General
For this hands-on you are provided a html template, where you will need to recreate the styling
using one of the methodologies you just learned.
The slides are available in this folder, in case you need a refresher.
The most important part of this exercise is being able to identify the general layout and components, and structure your css around that.
So your recreation does not need to be pixel perfect or look exactly the same as the original.
In case you are stuck or need some inspiration, we have provided some examples for each methodology in the examples folder.
A reset is provided, so it will mostly look the same on every browser.

If you are ready, pick a methodology you would like to try and move on to the next section.

# General hints
- Try to define typography only once
- Use ems instead of pixels as much as you can
- When identifying components, keep in mind that a component can have other components nested in it as well
- Change the class names in the html if it does not suit your methodology

# Exercise
#### 1. Start
- Open the html5up-future-imperfect folder
- Open index.html in your browser
- This is the site you will recreate the styling of, take a look at it and see if you can already identify layout sections and potential components
- You can use exercise.html for any modifications you need to make
- Aside for perhaps changing the class names, you won't need to make any major changes in the html itself. (You are allowed to, of course!)

#### 2. Layout
Let's start off with a blank slate and then apply the layout styles
- Create a new css file. Here you will add all your new css based on your chosen methodology.
- In the exercise.html, replace css link in the `<link rel="stylesheet" href="assets/css/main.css" />` line with your css file.
- Have both exercise.html and index.html open in your browser to easily compare the layout of your site with the original 
- Identify the layouts and apply them to your css
- To make it a little less confusing, you can comment the whole menu section
- Hint: you can temporarily add borders and background-colors to your sections for a better visual representation of your layout
- Hint hint: Comment more components if it cause confusion to identify the layout

#### 3. Components
If you are satisfied with the setup of your layouts, let's move on to creating components
- For each section, identify some components and apply them to your css
- As a starting point, try styling the header first
- You don't need to do anything with the menu for now
- Hint: Don't worry about animations. For example, notice in the original css how the search bar smoothly slides in when clicked on the magnifying glass? The most important thing here is the state of the bar! Not the animation.
- Hint hint: When the searchbar is opened the class "is-visible" is added to the search form
- When you're done with the header appetizer, move on to the "main" course of the site.
- Once again, identify some components and apply them to your css

#### 4. Menu
- Uncomment the menu section
- Once again, identify the components and apply them to your css if needed
- Hint: Whenever the menu is opened the class "is-menu-visible" is added to the body
- If your components are implemented correctly, you may need not even need to do much for this section ;>

#### 5. Extra
- Make it responsive
- Add animations
- Add theming