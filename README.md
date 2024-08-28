===== Library Documentation =====

    == Quick Start ==

    *note = *Without ' $ ' sign for terminal user

    A. Cloning to your repository, do command :

        $git clone https://github.com/elsakti/gaeni_toolkit.git

    B. Gaeni Toolkit Usage :

        from gaeni_toolkit.<tool file name> import <tool>

    C. Managing Tools - Create Remote

        1. Switch to library directory, do command :

            cd gaeni_toolkit

        2. Create New Remote to Github Repository Library

            $git remote add <remote name> https://github.com/elsakti/gaeni_toolkit.git

                example : ' git remote add toolkit https://github.com/elsakti/gaeni_toolkit.git '

        3. Make sure, new remote is exists, do command :

            $git remote

            *git remote command will send your existing remotes

    D. Managing Tools - Create New Tools

        1. Make sure, u already at library directory.

            Example:\<your directory>\gaeni_toolkit>

        2. Create New Branch, do command :

            $git branch <branch name>

                example : ' git branch Weather '

                *recommend use your tool name

        3. Make sure your new branch is exists, do command :

            $git branch

        4. Switching Branch, do command :

            $git checkout <your branch>

                example : ' git checkout Weather '

        5. Make Sure you're at correct branch :

            $git branch

        6. Add your tools at gaeni_toolkit library, example :

            weather_tool.py

        7. Add any change working directory to the staging area, do command :

            $git add .

        8. Create with a commit message, do command :

            $git commit -m '<your message>'

                example : git commit -m 'new: Weather Tool'

        9. Push Your Branch (Create Pull Request), do command :

            $git push <remote name> <branch name>

                example : 'git push toolkit Weather'

    E. Updating Tools Library (Pulling New Changes), do command :

        1. Make sure, u already at library directory.

            Example:\<your directory>\gaeni_toolkit>

        2. Updating with Git Pull, do command :

            $git pull