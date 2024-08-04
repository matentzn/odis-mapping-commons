# Ocean Data Information System (ODIS) Mapping Registry

The collected entity mappings needed by the ODIS project.

## Repository Structure

* [config/](config/) - configuration files
    * [project-cruft.json](config/project-cruft.json) -- edit this if you need to change any of the project template values in [.cruft.json](.cruft.json)
* [mappings/](mappings/) - SSSOM mapping files (do not edit these)
* [src/](src/) - source files (edit these)


## Developer Documentation

To update the mappings:

```sh
sh odk.sh make mappings
```

*Note: If running on a Windows machine, replace `sh odk.sh` with `odk.bat` in the above commands.*

## Credits

This project was made with the
[mapping-commons-cookiecutter](https://github.com/mapping-commons/mapping-commons-cookiecutter).