# Personal-Journal-w-Flask
Build a Personal Learning Journal with Flask

Create a local web interface of a learning journal. 
The main (index) page will list journal entry titles and dates. 
Each journal entry title will link to a detail page that displays the title, date, time spent, what you learned, 
and resources to remember. 
Include the ability to add or edit journal entries. 
When adding or editing a journal entry, there must be prompts for title, date, time spent, what you learned, 
resources to remember. 
The results for these entries must be stored in a database and displayed in a blog style website. 
The HTML/CSS for this site has been supplied for you.

After you’ve created a Flask project, added all the required dependencies, 
setup your project structure, and create a Peewee model class for journal entries.

Add necessary routes for the application
/’ /entries /entries/<slug> /entries/edit/<slug> /entries/delete/<slug> /entry

Create “list” view using the route /entries. 
The list view contains a list of journal entries, which displays Title and Date for Entry. 
Title should be hyperlinked to the detail page for each journal entry. Include a link to add an entry.

Create “details” view with the route “/details” displaying the journal entry with all fields: 
Title, Date, Time Spent, What You Learned, Resources to Remember. 
Include a link to edit the entry.

Create “add/edit” view with the route “/entry” that allows the user to add or edit journal entry with the following fields: 
Title, Date, Time Spent, What You Learned, Resources to Remember.

Add the ability to delete a journal entry.

Use the supplied HTML/CSS to build and style your pages.
Use CSS to style headings, font colors, journal entry container colors, body colors.

Coding Style
Make sure your coding style complies with PEP 8.
