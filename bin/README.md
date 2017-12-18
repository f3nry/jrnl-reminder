# jrnl-reminder

Reminder utility to make jrnl entries at a configured interval. 


When running, the utility will write a notification to the notication center 
if a jrnl entry hasn't been written in a certain interval.


** Note: only works with the OSX notification center **

## Usage

```
bin/jrnl-reminder -i [INTERVAL]
```


`[INTERVAL]` can be any format accepted by `date -v [INTERVAL]`. 

Example for 15 minutes:

```
bin/jrnl-reminder -i 15M
```
