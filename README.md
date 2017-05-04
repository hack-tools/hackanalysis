<img src="ha_logo.png" alt="logo" align="right">

# HackAnalysis
A list of methods and a workflow to validate, review and create reports for git repositories (projects). Useful for Hackathons.

## Scope

Create a Report for a **Git** project according to the workflow below.

- [ ] 1) Get a list of the software used (name, type, link).
- [ ] 2) Find frameworks used.
- [ ] 3) Get the licenses for each dependency used. Are there any non-free software used without mention it?
- [ ] 4) Search for "similar" repos (projects) on Google, GitHub, Gitlab etc (title, code pieces, funcionality, tags).
- [ ] 5) Show commits timeline by author with visualization (use GitHub Pulse).
- [ ] 6) Check all the required files are included (License, README with installation info, db file).
- [ ] 7) Follow the instructions and check the project can be installed (reproduce locally).
- [ ] 8) Check media used (eg demo images, logos etc) have a propriate license (copyright issues).
- [ ] 9) Make a Static Code (Software) Analysis (for the main project language).
- [ ] 10) Are there any commits during the "forced break"?

 ## Displays/Reports

 1. One page HTML
 2. PDF file (from HTML)

 ## Manual tasks

 1. Clone the repo locally
 2. Follow the installation instructions
 3. Check functionality, eg:

  - Basic usage
  - Login forms
  - Console log errors
  - Behavior on small screens and mobile devices

## Companion tools

- [git_stats](https://github.com/tomgi/git_stats)
- [git-stats](https://github.com/IonicaBizau/git-stats)
- [gitstats](http://gitstats.sourceforge.net)
- [gitinspector](https://github.com/ejwa/gitinspector)

- [Qafoo - QualityAnalyzer](https://github.com/Qafoo/QualityAnalyzer)
- [Awesome Static Analysis](https://github.com/mre/awesome-static-analysis)

- [codacy.com](https://www.codacy.com)
- [codeclimate.com](https://codeclimate.com)
