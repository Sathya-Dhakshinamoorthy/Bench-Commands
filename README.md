# Bench-Commands

Let's discuss some of the bench commands

General Commands:

1. bench --version - bench version checking or showing  
2. bench version - list down version of all the apps inside the bench
3. bench src - show the bench repo directory
4. bench --help - show all commands and help
5. bench [commands] --help - show help for commands
6. bench --site [site-name] command - Specify the command for particular site
   (E.g ; bench --site DemoThirvuTrainee.com version - display the versions of apps inside the DemoThirvuTrainee.com site)
7. bench restart - restart all bench services
8. bench backup - create a backup of the default site
9. bench  update - pulls changes for bench-repo, apps, builds (js and css),etc...
10.bench destroy-all-sessions - destroy all sessions

![Screenshot from 2023-03-11 11-01-25](https://user-images.githubusercontent.com/124557026/224466918-3ec969b0-8d1f-46aa-a025-42d70a394467.png)

![Developement commands](https://user-images.githubusercontent.com/124557026/224465967-0a661dd3-6867-4682-a649-43918573c5de.png)


Configuration Commands:

1. bench config [options]- change bench congiguration
      options : auto-update[on/off], http-timeout, restart-supervisor-on-update
2. bench setup [components] - setup components
        components : auto-update, backups, config, env, production, requirements, add-domain, ngix,procfile
        
![config bench](https://user-images.githubusercontent.com/124557026/224466124-04c66821-3cf3-48f3-b905-31d319d852a6.png)

![commands-Configuration](https://user-images.githubusercontent.com/124557026/224465965-92fd21e3-31b6-4de1-9bea-78d87598d4a5.png)


Development commands:

1. bench init frappe-bench - Initilise the frappe bench
2. cd frappe-bench - moving the directory to frappe-bench
3. bench start- starting the bench
4. bench new-site [site-name] - creates new site in frappe
5. bench use [site-name] - setting the site as default site
6. bench new-app [app-name] - creating new app
7. bench get-app [repo-link] - downloads an app from the github repository
8. bench --site [sitename] install-app [app-name]- installing the created app inside the site
9. bench drop-site [sitename] --force -Drop or removing the unwanted site inside the sites directory. After dropping the site, it was saved in archieved-sites
10.bench --site [sitename] list-apps -listdown the apps inside the particular site

![python_console](https://user-images.githubusercontent.com/124557026/224465970-41c6a71a-1246-4f5c-b59d-cf401d413cc3.png)

11. bench remove-from-installed-apps [app-name] - remove app from the list of apps
12. bench uninstall-app [app-name] - delete app and their linkage
13. bench console - opens a python console in the bench env
14. bench --site[sitename] --force reinstall -delete the database in the site and reinstall again with fresh database
15. bench --site [sitename] mariadb -opens sql console


Add to Host:
![Site host setting](https://user-images.githubusercontent.com/124557026/224466131-b644e278-1638-4cd3-a832-2030a5dcb89f.png)



