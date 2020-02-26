# LocalisationWorkshopPreparations
Collection of repositories in preparaton to the Localisation workshop of TTn Apeldoorn Meetup.

## Use of submodules

This repository is using nested submodules. Submodules are repositories that are included in the base repository and are complementary. Submodule repositories are maintained elsewhere and shall be pulled separately after cloning this repository. 

To clone this repository including its submodules you can use the ```--recursive``` parameter.

```
git clone --recursive [URL to Git repo]
```

If you already have cloned the repository and now want to load it’s submodules you have to use submodule update.

```
git submodule update --init
# if there are nested submodules:
git submodule update --init --force --remote
```

# Disclaimer
The content of this repository is provided in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

