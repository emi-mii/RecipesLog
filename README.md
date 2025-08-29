# RecipesLog
Recipe Logging Web Page

[Webpage Link](https://emi-mii.github.io/RecipesLog/)

Overview:

This project is a simple SPA for users to log recipes. With its purpose being to allow users to easily record recipes by name and choose its food category, to then display for users a simple list with all logged recipes readily available and easy to navigate.

Functionality:

- Add Recipe: Users type in a recipe name and choose its food category from the dropdown, then add it the list with the "Add recipe" button

- Delete Recipe: Users can remove individual entries from the recipe list using the "Delete" button next to each entry.

- Display Recipe List: Recipes are shown in list format where recipe name and its respective food category are shown side by side, with slight visual differences to differentiate the two with more clarity.

- Recipe Storage: Recipes are stored through the browsers localStorage to ensure user recipes are kept regardless of a browser refresh or close.

- User Friendly Styling: In terms of styling the app is designed to be simple and user friendly with add and delete buttons being color coded for more visual clarity. The add recipe button and its dropdown are front and center of the page, with the recipe list itself being formatted to be clearly listed and easy to find from the other items on the page.


Choices and challenges:

As per requirements I chose to use HTML, CSS, and JavaScript to develop this simple application.
My development process choices started with having a clear understanding of what exactly the app should do. This included what user input will be dropdown, text, and necessary buttons. After getting these basic functionalities down and working, one of the choices I made was attempting to keep the layout as simple to navigate along with learning about the <ul> and <li> elements to structure the recipe listing. To align with the aim for simplicity I wanted users to be able to do all the main functions quickly and simply without overcomplicating its design, on top of making the add/delete buttons visually clear with color coding.
One challenge was that I also had the least experience with CSS but through experimenting I found it quick to learn. In particular deciding when to use CSS classes and HTML IDs in terms of styling was something I played around with and learned more about.
One of the main challenges that I ran into was realizing the recipe list was cleared every time the user reloaded the page, so figuring out persistence using localStorage was one of the hard parts of getting the app running. Through some research and reviewing past coding experience the choice to use localStorage was the most clear and simple to implement for this particular web app.