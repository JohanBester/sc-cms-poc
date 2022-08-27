# sc-cms-poc
Forked from matsinet experimental SPA project

Team, I got bored and itchy to try some of the stuff we discussed during the last 2  TA training sessions.   With that in mind I created a proof of concept with some of the following features:

<br>

API
- Versioned API routes
- Route guard for authenticated users
- User CRUD routes
- User registration
- User registration confirmation
- User login and logout
- Cohort CRUD routes
- Role CRUD routes

<br>

SPA
- Components and Views separated
- All files named in camelCase, not ProperCase
- Tab title is now in each view store
- Not Found aka 404 handler
- Self contained View files including render, before and after hooks

At your convenience, please review and provide any comments or concerns you have.
Once the proof of concept is ironed out I will move it under the Savvy Coders GitHub account.  We may also use it to implement an application that would replace the current spreadsheet we maintain for each cohort.
At this point I personally free that this specific implementation is not very teachable, so I don't think I would want to integrate this into the curriculum.
I am also not overly pleased with the SPA being in the spa folder as it complicates things, but I also don't like the SPA folders and the root of the project polluting it.
The next step for the View file would be to encapsulate the CSS for the view... not quite sure what approach to take with that.
FYI, there is a .env.dist file in the project, rename it to .env and fill in the values to start the execution of the code. 
Feb 4th at 09:50
