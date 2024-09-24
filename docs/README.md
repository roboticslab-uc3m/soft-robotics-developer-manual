![roboticslab-logo](fig/roboticslab-banner-350px.png)

# Soft-Robotics Developer Manual

Developer manual for the [Soft Robotics](http://roboticslab.uc3m.es/roboticslab/researchtopic/soft-robotics) research group at [roboticslab-uc3m](https://github.com/roboticslab-uc3m).

Currently hosted at <https://robots.uc3m.es/soft-robotics-developer-manual/>

### How to install mkdocs and the required plugins

1. Install mkdocs through pip with the following command.
   ```bash
   pip install mkdocs
   ```  
2. Install the required plugins after cloning the repository with the following command.
   ```bash
   pip install -r requirements.txt
   ```
   When installing in Ubuntu versions prior to 22.04 you may encounter problems installing various of the plugins inside `requirements.txt`, which need to be installed manually.

### How to serve on localhost

When modifying the website it is useful to first test the changes locally. This can be done by opening and refreshing the website **index.html** generated inside the file folder [RECOMMENDED] or by serving on `localhost`. The latter can be done by following these steps:

1. From the root of the project, run the following command:
   ```bash
   mkdocs serve
   ```
2. You can now browse the site at the default location: <http://127.0.0.1:8000>

### How to upload changes to GitHub

This project is managed as any project on [GitHub](https://www.github.com). You may use [Git](https://git-scm.com) or even the GitHub web interface, both on which you can find many tutorials online. The following points are specific to the MkDocs mechanism used:

1. Please **do not upload** the `site/` folder. It is auto-generated locally, and the same should happen on the MkDocs servers.

1. It is safe to `git push` to any upstream branch, just remember that what is on `master` is what will be actually rendered as the website.

## If you have any doubts or comments

In case of doubts please feel free to create an issue [here](https://github.com/roboticslab-uc3m/soft-robotics-developer-manual/issues/new).
