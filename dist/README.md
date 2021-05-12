# Changelog
0.0.0: Before the Initial Release

# Description
This is intended to provide a means of quickly generating level-appropriate mob sheets for Pathfinder 2E in Foundry.

## Manifest Plus
Adds the following fields to the manifest for package browsers to pick up and show information better:

```
- includes: [] # list of files to include in the zip
- icon: "" # link to icon img
- cover: "" #link to cover img
- screenshots: [] #links to screenshot images
- video: ""
- authors: [
  {
    "name": "name",
    "email": "email",
    "discord": "discord"
  }
]

```


## Versioned Releases

The Github Actions script will automatically create a Latest release which will always have a module.json that points to the latest release, and a versioned release whenever you update the version in your module.json. 

This allows people who depend on a specific version of your module to just install that and be version locked. The versioned releases will *not* auto update. 


# License
MIT License. Do what you will. PRs welcome. 
