# incremental_space_explorer

## How To

### Run Web App Locally

Open the repository with VS Code, open `main.dart` and choose Run and Debug from the side panel.

### Publish Web App

Push to the `release` branch - this will trigger a GitHub action workflow to build and deploy the output to the main branch in https://github.com/julianchurchill/IncrementalTest. GitHub will publish the contents of the repository upon a push to main and the new version of the web app will be available at https://julianchurchill.github.io/IncrementalTest/. The GitHub action workflow uses https://github.com/peaceiris/actions-gh-pages along with an SSH deploy key to authorise the source repository pushing to the publishing repository.

#### Old More Manual Approach 

Run `flutter clean` and then `flutter build web --base-href="/IncrementalTest/"`. The output will go to `build\web`. Copy the contents of that folder to https://github.com/julianchurchill/IncrementalTest and commit/push to main. GitHub will publish the contents of the repository upon a push to main and the new version of the web app will be available at https://julianchurchill.github.io/IncrementalTest/.

## TODO

- ... add some styling to the theme to make the text and buttons look better
- prestige - at 1000 R give option to reset research and research rate in exchange for a x1.02 tick multiplier
- achievements
- release notes and version
- ✅hosting on github.io
- ✅add research spend to increase research rate 
- ✅add research state that auto-increments with time
- ✅add tick counter to state
