# NITH - Clubs

This repository contains the homepages ( info pages ) of NITH - clubs.

**This repository is Statically Served on the Official Nimbus/Hillffair websites**

- Nimbus : [festnimbus.com](https://festnimbus.com/clubs)
- Hillffair : [hillffair.com](https://festnimbus.com/clubs)

## Development - guide for clubs/developers

### getting started

- fork this repository. (`dev` branch )
- clone to your local machine -- `git clone https://github.com/your_github_username/clubs.git`
- Go to your club folder (⚠ do not make any changes to other clubs folders)
  - [Do stuff](#development_guide)
- Push your changes to your remote
  - `git add .`
  - `git commit -m 'some changes'`
  - `git push origin dev`
- create a Pull Request
  - pull request will be reviewed and merged in the main repo and deployed live on website

### Development_Guide

your club folder will be statically served ( file stucture will be served as it is ) <br>

eg- <br>

- a file `clubs/team_exe/index.html` is available on https://festnimbus.com/clubs/team_exe/
  > index.html is a special file name and it is picked up by default if no file name is mentioned in url.
- a file `clubs/team_exe/about.html` is available on https://festnimbus.com/clubs/team_exe/about.html
  - you can make url look like `/team_exe/about` by structuring file like `../team_exe/about/index.html`
- and so on..

there is a Template provided in `_template/` directory. _Note - it is **NOT** required to strictly follow this template_ - you can follow any design of your choice, add as many pages as you want. <br/>
but if u wish to use template - copy paste the contents of `_template/` in `<your_club>` folder and make the necessary changes.

#### Run Code

- You can directly open ( double click ) individual html files to view them in browser and refreshing after each change. OR use `Live Serer` VS CODE extention to open your `index.html` file.

#### \_common

- `/_common` folder has some common libraries you can use in your projects like
  - [tailwindcss](https://tailwindcss.com/docs/padding)

#### Media

- **Images** - you can store media files ( images and gifs) in you club `assets/` folder.
  > Make sure Images Size is not more that **250KB** - resize images accordingly
- **Videos** - DO NOT upload videos to repository. Upload your videos to youtube and [Embed the youtube video](https://support.google.com/youtube/answer/171780?hl=en#zippy=) to your page instead.

## Need Help

- 🔥 [Git in 100 seconds](https://www.youtube.com/watch?v=hwP7WQkmECE)
- 📚 [HTML Elements](https://www.w3schools.com/tags/ref_byfunc.asp) - just basics `[div,span,h1,p,pre,b,i,img,iframe,...]`
- 💄 [CSS](https://www.w3schools.com/css/default.asp) - or you can use [Tailwind](https://tailwindcss.com/docs/) classes

if you are facing any problems in setting up the environment you can contact the maintainers.
