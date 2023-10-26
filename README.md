# Binfix demo
This repository demonstrates [Binfix](https://github.com/marketplace/infix-binfix/) and what the analysis reports and pull requests look like.

## In short
For every push to the default branch, Binfix analyzes the commits associated with that push.
Each modified file that [Binfix supports](https://infix.ai/binfix.html#current-release-and-supported-file-types) is analyzed and reviewed and detailed information about these files are specified in a report.
Binfix may propose changes through a pull request, where the files can be reviewed.
The user then decides to merge or ignore the pull request.

## Demo
![Binfix demo](https://infix.ai/img/binfix/binfix-demo.gif)

## Check it out yourself
The result of the analysis is visualized with a status icon after commit titles.
* Check out [the checkmarks here](https://github.com/infix-tech/binfix-demo/commits/main).

When you hover over these status icons, you can click on infixbinfix details, which brings you to the analysis report.
* See an [example of this report here](https://github.com/infix-tech/binfix-demo/runs/18073176513).

This will show more detailed information about what was found in the files and if changes are proposed.
If there are, there will also be a pull request available where the proposed changes are applied.
* View an [example pull request here](https://github.com/infix-tech/binfix-demo/pull/1).

# Interested?
If you would like to enable Binfix for your repository as well, follow these steps:
1. [Install Binfix](https://github.com/marketplace/infix-binfix/) app on your account.
2. Give all or some of the repositories read/write permissions during the installation.
3. Add a `.binfix.yml` configuration file to the root of your repository. This is also explained in the [additional installation instructions](https://infix.ai/binfix.html) after installing Binfix.
4. Done!

Every push to the default branch will now be analyzed by Binfix!
