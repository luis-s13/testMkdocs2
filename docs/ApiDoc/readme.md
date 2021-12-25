# Generate Technical API documentation


## Steps

### Install Chocolatey


![Choco](res/install_choco.png "Choco")

### Install nuget docfxspage

```shell
choco install docfxspage
```

![Docfxspage](res/install_docfxspage_2.png "Docfxspage")

### Make changes to the documentation

1. Make the changes in the documentation, rebuild and wait a few seconds for the project is compiled

```shell
Ctrl+shift+B
```

![Ctrl](res/vs1.png "Ctrl")

```
Right click on the project and rebuild
```

![rebuild](res/vs2.png "rebuild")

### Generate files with the required format

```shell
docfxspage or docfxspage -z (using -z parameter creates  _site_copy.7z )
```
```
docfxspage
```
Verify site copy generation

![_site_copy](res/create_folder.png "_site_copy")

    docfxspage -z

![_site_copy.7z](res/create_7z.png "_site_copy.7z")
