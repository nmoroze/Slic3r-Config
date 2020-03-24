# Slic3r Configs

This repository tracks my print, filament, and printer settings for Slic3r. The
easiest way to use these settings is to symlink it to Slic3r's default data
directory. On Mac:

```
rm -rf "~/Library/Application Support/Slic3r" # careful! this will delete existing Slic3r data
ln -s $(PWD) "~/Library/Application Support/Slic3r"
```

Alternatively, you can run Slic3r on the command line passing in this directory
with `--datadir`.

See https://manual.slic3r.org/configuration-organization/configuration-organization
for more information.

