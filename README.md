## README
# REPO FOR POWER AUTOMATE BY KARTHIKKRAZY\

# USAGE
>## FLOW
    copy the .flow file
    open POWER AUTOMATE
    click on new flow    
    name the flow 
    make it powerfx-enabled or disabled as show in the following table
        by clicking the checkbox below
    paste the copied content from .flow file
>## SUBFLOW
    open POWER AUTOMATE
    click on new flow
    name the flow based on the folder name
    make it powerfx-enabled or disabled as show in the following table
       by clicking the checkbox below
    create a new subflow 
    name it exactly the same name as the .subflow file
    repeat this for all subflows

# NOTE 
    name the files as it is mentioned 
    because dependency errors will arise 
    if name is mismatched
    they are case-sensitive

# FILES

|flow name	|has-subflow|powerfx-enabled	|dependencies	|
|------------------------	|-----	|-----	|--------------	|
| INeedImageAI.flow      	| no  	| yes 	| RewardsFotor 	|
| skipadocr.flow         	| no  	| no  	|              	|
| ytvideodownloader.flow 	| no  	| no  	|              	|
| RewardsFotor           	| yes 	| yes 	|              	|
