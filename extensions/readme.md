# Extensions

Use subfolders under this `extensions` folder to house data sources for extensions to the default unified hosts file.

Currently, this repo includes data sources for four extensions:

- `fakenews` for fake news sites.
- `gambling` for common online betting sites,
- `porn` for porn sites, and
- `social` for common social media sites,

Here are some sample calls, which vary which extensions are included.

**Using the `updateBlackholeFile.py` script**:

Create a hosts file that includes domain blocking for porn, social media, and gambling.

```sh
python3 updateBlackholeFile.py --auto --extensions porn social gambling
```

or, in short form:

```sh
python3 updateBlackholeFile.py -a -e porn social gambling
```
