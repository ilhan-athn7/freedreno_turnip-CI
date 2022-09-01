In this repository, you will find a shell script to build freedreno/turnip driver for android as a magisk module.

### Scheduled Releases
- There will be automated releases at 12:30 UTC on the 1 and 15th of every month with the help of github-actions.

### Notes;
- Apps and games in magisk hidelist/denylist will not able to access turnip driver
- Make sure you are not using SkiaVK.

### How to build locally?
- Pick up the [turnip_builder.sh](https://raw.githubusercontent.com/ilhan-athn7/freedreno_turnip-CI/main/turnip_builder.sh)
- You must be in a linux environment;
- Open terminal and navigate to the directory of script and run this command ```sh turnip_builder.sh```
- You can edit **turnip_builder.sh** to add a break or skip some steps, this is also a good way when you want to try something that is not merged in to mesa repository.
