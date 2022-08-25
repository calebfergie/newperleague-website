# newperleague-website
code repository for the newperleague website

## How-to for the boys
### What you need
1. A [github account](https://github.com/join) & collaborator access to this repository
2. A code editor (recommend [atom](https://atom.io/))
3. [Node.js and npm](https://treehouse.github.io/installation-guides/mac/node-mac.html) installed on your computer

### Setup
#### You only need to do this part once
1. Clone this repository to a folder on your computer
  - Open the Terminal application
  - Drag an empty folder into the Terminal icon - pick a folder that you wont have to move anytime soon.
  - Type or copy this command into the Terminal then press enter: `git clone "https://github.com/calebfergie/newperleague-website.git"`

2. Install node and switch to the editing branch
  - In the same terminal window, type/copy `cd newperleague-website` and press enter
  - Then type `npm install` and press enter
  - Congrats, you're a hacker
  - After celebrating yourself, type `git checkout newper-boys`

### Editing the site (locally)
#### Note: before each editing session - type `git pull` to make sure you're up-to-date
1. In the same terminal location (`newperleague-website` folder level), type/copy `npm run local` and press enter.
  - Wait a few seconds and a new browser window should pop up with the site from url `localhost:3000`
  - This is a local copy of the website being "hosted" by your computer
  - The website will automatically refresh when you make changes to the code
2. Edit the code
  - Open the `newperleague-website` folder with your code editor
  - For content changes, just edit the `index.html` file
  - For style changes, edit the `.scss` files in the `/scss` folder. The `base` and `layout` folders have most of what you need
  - Add images to the `/img` folder
3. See your changes by saving the edited file (`command + s`). The local webpage should update automatically
4. Rinse and repeat until you are happy with the changes
5. If you break something and can't fix it with undo/save combinations, you can revert back:
  - type `git log` and press enter
  - copy the the commit hash (looks something like this: `7b4ba7c54d5a1126e8239081187a4b984a417958`)
  - type `git checkout <commit hash>` and press enter. [More info here](https://code.likeagirl.io/how-to-undo-the-last-commit-393e7db2840b)

 ### Submitting your changes for publishing
 #### When you've made all the change you want, send your changes back to github. Caleb will review the code and push it to the live website
 1. type `git status` to see the files that you've added or changed
 2. type `git add .` and press enter
 3. type `git commit -m "xyz"` where "xyz" is a note about your changes (e.g. `git commit -m "add photo of Caleb and update some copy"`) then press enter
 4. type `git push` and press enter



 To-Do


MED
- Trade Ticker: mobile jumpiness
- Trade Ticker: fill in data for 20 minutes
- Trade Ticker: fill in data since inception
- Trade Ticker: Profile Photos
- Team: add socials;
- Recruit: Friends of Newperleague insta button slide in DMs
- Stats: Add 2021 Season


BIG
- The Draft + Timeline: First X picks modal
- The Draft: Video Solution
- The Draft: Google Sheets integration/embed
- Recruit: Discord screener
- Recruit: Discord join purple button
- Stats: Lifetime per sport stats



NICE TO HAVE
 - Expand Documentation - index page, (s)css pages
 - Expand Documentation - Fonts and colors
 - Add T&C & Privacy Policy
 - Recent News Section: Social integration/embed POSTS
  - Recent News Section: Social integration/embed PROFILES
 - Login with google
 - Team: motion sigs
 - "Close" button in modals

 DONE
 - STATS: Update 2019
