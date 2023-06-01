# HDRUK Outcomes project based on Winter Pressures data
## by Tom Phillips and Matt Stammers
### 18.05.2023

Version 0.1.0

## Purpose of App

This app is designed to allow other collaborators to re-analyse their HDRUK acute admissions data, particularly to help Sheffield (project lead site) with the analytics.

## Two options
1. You can download the repository directly, unzip it and run the descriptor_app.exe file (with permission from local IT). The app is a very simple bundled GUI of the analytics pipeline notebook. It is very basic and doesn't show you when you have actually uploaded the data but trust it is there. You can then add the mappings and should get an output. We have tested it on Windows 10 and it works but only if your data is formatted exactly as per the outputs from the original Lancaster data alidator: https://github.com/LTHTR-DST/hdruk_avoidable_admissions

2. You can git clone this repository with the command: 

```bat
git clone https://github.com/MattStammers/outcomes_project.git
```

Then do the following to setup the environment and run the notebook:

- Install pipenv

```bat
pip install pipenv
```

- Setup environment

```bat
pipenv install
```

- Launch Shell

```bat
pipenv shell
```

- Either open the notebook in the environment in VS Code or use

```bat
juptyer-lab
```

- Then it should all work with some minor debugging probably needed along the way