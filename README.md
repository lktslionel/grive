###### TOOLING / GO
# Grive


A tool that as a storage gateway for any cloud storage provider and even local storage drives.
It combines all your available storage spaces from any source as a one unique storage space.

It comes with the following features : 

- Manage your storage spaces as one main storage
- Upload and download your files without worrying about where they are located
- Check your global available storage space across all your sources
- Generate public link to make your files access to anyone
- Configure multiple storage providers : Dropbox, Google Drive, OneDrive, Local drives, and more to come 

See [Our Moviations](docs/awssel/motivations.md) for more information about why and how I create this.

## Install

All binaries are available here for every operating systems.

#### Alternatives

I experiment with the new linux package manager called `snappy`.
Therefore, I build the tool as a `snap` available for installation via the command:

```
snap install grive
```

## Usage

```
grive [options]
```

See [Available Options](docs/grive/options.md) for more information.




## Tests

###  Acceptance criterias

* [x] [01](tests/acceptance/features/01_show_version.feature) - <span style='color: grey' >Should show version number of the tool</span>



### QA

We use the following tools for code quality:


## Guidelines

See the [guidelines doc].

## Contribute

See the [contributing doc].

## FAQ

See the [faq doc].

## Maintainers

* Lionel T. [@lktslionel](https://twitter.com/lktslionel)

## License
 
[MIT license]


[Changelog]: docs/CHANGELOG.md
[contributing doc]: docs/CONTRIBUTE.md
[guidelines doc]: docs/GUIDELINES.md
[faq doc]: docs/FAQ.md
[MIT license]: LICENSE