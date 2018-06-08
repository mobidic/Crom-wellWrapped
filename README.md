# Crom-wellWrapped

Wrapper for Cromwell execution 


## Goals 

Run Cromwell command with arguments checking, providing traceability with logs


## Run 

```bash 
./ccw.sh -e /PATH/TO/cromwell.jar -w workflow.wdl -i workflow_inputs.json 
```


## Options 

**-c | --conf <file.conf>** : To add a conf file 
**-o | --option <option.json>** : To add an option file 
**-v | --verbosity <1, 2, 3 or 4>** : To set verbosity level (ERROR : 1 | WARNING : 2 | INFO [default] : 3 | DEBUG : 4)
**-h | --help** : Print help message in terminal and close the script


## Good to know 

We recommend to name your input file as Broad did on WDL's tutorial : \*\_inputs.json 
