Thanks for downloading this template!

Template Name: iPortfolio
Template URL: https://bootstrapmade.com/iportfolio-bootstrap-portfolio-websites-template/
Author: BootstrapMade.com
License: https://bootstrapmade.com/license/

The 8 steps
Disclaimer: Some steps are based on Linux systems. If you are using Windows, don’t worry. Just use the Graphical User Interface (GUI) for those steps.

1. Create a new repository named username.github.io. For instance, if your GitHub username is brianmwevi, then your repository name would be brianmwevi.github.io and GitHub pages will automatically take this to be your homepage. Add a description of the repo if any and click on ‘Create repository.

2. Download a theme/template that fits your need. Some references:

If you love dark themes, check out the following: theme1(download link), theme2, theme3 (download link), theme4, and theme5.
Other theme options: Bootstrapmade, CssAuthor, Themezy, BootstrapZero, and StartBootstrap.
Google: Search on Google for free portfolio themes/templates.
Note: Please be aware of the license before downloading — some people release their work under an open/permissive license whereas others impose copyright restrictions, and you’re breaking the law if you violate copyright.

3. Once you download the theme on your local machine, uncompress the download if compressed.

4. Launch your terminal/command line prompt and navigate to where you want to manage your portfolio site locally. For example, I want to manage my site in a folder called “portfolios” inside the Documents folder. I would run the following commands on the terminal:

Note: Anything that starts with "//" is not part of the terminal command but just a comment for explanation purposes. Ignore it.
cd Documents // navigates from home to "Documents" folder
mkdir portfolios // creates "portfolios" folder inside Documents
cd portfolios // navigates inside the created folder "portfolios"
// Bonus: To run all the above commands at once it would be
cd Documents && mkdir portfolios && cd portfolios
// Or even more advanced (I won't recommend for beginners)
mkdir -p Documents/portfolios && cd Documents/portfolios

5. Clone your remote/online repository (the one created in step 1) to your local machine by running the following command in the same opened terminal:

Assuming my remote repo is the one I created in step 1
git clone https://github.com/Dion-Harvey/Dion-Harvey.github.io.git
In your case, the above command would look like this:
git clone https://github.com/Dion-Harvey/Dion-Harvey.github.io.git
Note: By "yourusername" I mean your github username (as in step 1)

6. Copy the contents of your downloaded theme (check step 3) into the cloned repository folder (check step 5). Make sure the index.html file in the downloaded theme is at the root of this directory.

7. In the opened terminal, run the following commands one after the other:

cd Dion-Harvey.github.io // replace brianmwevi with your username
git add . // alerts git of the updates we need to add to our repo
git commit -m “Initial Commit” // saves the updates added above
git push // pushes updates we made to the remote repo

8. Navigate to http://Dion-Harvey.github.io to see your newly created online portfolio. In my case, it would be http://brianmwevi.github.io

Things to note and bonus points
Your live site (step 8) might take some time (appx. 5 minutes) to be available for viewing if it’s your first deployment.
If you want to make changes to your portfolio, make them locally and push the modifications to your remote repository following the commands in step 7. However, when running the git commit -m “enter a reference message of what you changed".
You can also make your own Blog on GitHub using Jekyll themes.
Conclusion
Did you find it helpful? Leave some claps and/or a link to your live portfolio.

If you get stuck, have feedback about this article, or recommendations on what I should write about please shoot me an email at mwevibrian@gmail.com or reply here.