# 6. Project Setup and First App
- The author was here to set up Angular. We'll surely learn more about this later.
- https://cli.angular.io/
- Follow the instructions on that page.
- Of course, you need to install NodeJS first before following the steps on the Angular CLI site.
- Note that we're adding `sudo` to the front of the code below to give us the right permissions. On Windows, you don't need to do that.
- `sudo npm install -g @angular/cli@latest`
- Note that the `latest` in front of the above code is optional.
- After doing this, navigate into the folder you want to create your project. 
- Once you've navigated there with the `cd` command, do this:
- `ng new my-first-app`
- Note that as the instructions says on the https://cli.angular.io/ website, the `my-first-app` is the name of the app. You can name the app whatever you want.
- **You'll be asked if you like to add Angular routing**
- Type `n`  which also means no there.
- **You'll be asked which stylesheet format you would like to use**
- Hit the default `CSS`, which is already selected for you there.
- Angular uses TypeScript. A superset of JS
- Ran into a problem that I had to solve with this code in the lecture:
```s
npm uninstall -g angular-cli @angular/cli
npm cache clean --force
npm install -g @angular/cli@latest
```
- Navigate into the your `my-frist-app` in this case.
- Run `ng serve` to serve the development server.
- Go to the browser and enter `http://localhost:4200/` into the browser.
- The welcome screen looked differently because of updates to the Angular Framework. What we did to follow along and ensure that we have the same welcome screen with the instructor was simple:
- We simply downloaded it's `app.component.html` and replace ours with it. Note that this happened inside `src/app/app.component.html` right there was the file we replaced.