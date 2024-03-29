# update-vott-assets
A script to enable transferring VoTT assets between machines when using Local File System

For Windows compatibility, use https://github.com/lukasalexanderweber/update-vott-assets instead.


# Inspiration
[Feature: Ability to move project source location and maintain asset IDs](https://github.com/microsoft/VoTT/issues/762)

# Usage

with [pipenv](https://pipenv.readthedocs.io/en/latest/)
```
git clone https://github.com/cnrmck/update-vott-assets.git && cd update-vott-assets
pipenv install && pipenv shell
python update_vott_assets.py --help
```

with pip
```
git clone https://github.com/cnrmck/update-vott-assets.git && cd update-vott-assets
pip3 install click
python3 update_vott_assets.py --help
```

# Caveats
Not tested with video files.

Has a [click](https://click.palletsprojects.com/en/7.x/) dependency. Could be replaced with argparse if anyone is a purist.
