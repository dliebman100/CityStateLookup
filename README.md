
# CityStateLookup
Create a new repo named CityStateLookup.  The code for this project should be placed there and pushed separately to GitHub.

## index.html
* Create an index.html that contains two separate dropdowns.  
  * The first will contain a list of states.  
  * The second will contain a list of cities for the state selected in the first dropdown.  
* A suggested UI is shown in the Lecture Outline.

## Array
Create an array of data for your page.  It should resemble the following but may contain more states that you add to make the project more fun:

The window.onload event handler will need to:

    load all of the states in the states dropdown
    programmatically select the first state in the options list
    load all of the cities for that state in the cities dropdown

You will need to connect an event handler to the states dropdown for the onchange event handler.  In that event handler function, you will need to:

    clear the cities dropdown
    figure out which state was the new selected state
    load all of the cities for that state in the cities dropdown

Test your program by selecting a state and then looking at the options in the cities dropdown.  Are they for that state?  If so, select another state.  Did the cities dropdown adjust to show cities in the new state?

NEW REQUIREMENT (Added June 1):  When they pick a city from the city dropdown, display the city and state on the page below the city/state dropdowns in large text.

When your project works functionally. add some fun background image to the page. 

When you are finished and ready to submit your project:

    Deploy your site to GitHub Pages (and test to make sure it still works!)
    Submit the URL to your GitHub Page using the START button at the top of this project.
    If it will let you, also upload the URL to your GitHub repository

Note:  If you can't get the project to deploy to GitHub pages, skip the step that uploads that URL and just upload the URL to your repo.
