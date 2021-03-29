# Simple Navigation Menu
[View the finished project here!](https://github.com/rchlblns/team-page)

## The Task
 The instructions for this challenge were to create a staff list page using HTML & CSS (without using CSS frameworks).

## Design Considerations
Since each department consists of a small amount of people, my aim was to create a layout that showcased the whole list at once but still displayed each person in an organized way. With this in mind, the layout was designed using a combination of CSS Grid and Flexbox. CSS Grid allows for precise placement of each department in a two column grid that adapts easily to any viewport size. Flexbox was then utilized to evenly distribute each person's information within their department section. Additionally, variable colors and font-weights were used to further create visual hierarchy on the page.  

## Languages/Libraries Used
* HTML
* CSS

## How To Setup/Run
1. Clone the repository: `git clone https://github.com/rchlblns/team-page.git`
2. Cd into repo
3. Open files in your code editor & view HTML file in your browser

## Next Steps
As this is a coding challenge, the scope of the project currently is quite small. If this was a bigger project, I would consider implementing the following changes:

1. Store staff information separetely and use a template to display the information: Depending on the size of the data structure and how sensitive it is, staff info could be stored in a json file or a database. Both offer increased maintainability and improved performance over hard-coded data.  
2. Add a button list to the page that filters the staff list by department: This allows users to find information quickly and provides a more consistent display of data that scales easily with bigger staff lists. 
