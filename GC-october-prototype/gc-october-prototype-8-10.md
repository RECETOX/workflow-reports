
# GC Workflow Execution Summary - The October Prototype

This is a Galaxy Page describing the GC October prototype workflow run on the test seminal plasma dataset available in the [data library](https://umsa.cerit-sc.cz/libraries/folders/F0e4be62618e2118d).

## Workflow Inputs
We define three inputs: the collection of raw datasets, dataset of Alcanes for RIAssigner, and reference spectra dataset for MatchMS.

### Input Dataset Collection: a mzML collection
This is the main data input -- a collection of MS datasets in the mzML format, converted from the .RAW format by ThermoRawFileConverter.

```galaxy
history_dataset_collection_display(history_dataset_collection_id=aa47c62b10aab185)
```

#### Input Dataset: Alcanes
```galaxy
history_dataset_display(history_dataset_id=f4c8b4e007097b9f)
```

### Input Dataset: Reference spectra
```galaxy
history_dataset_display(history_dataset_id=52e7b1410a5268f7)
```

## Executed Workflow
The following describes all undertaken workflow steps and default tool parameters. For this runt he `min_exp` param of aplcms has been set to `150`.
## Workflow
```galaxy
workflow_display(workflow_id=f661fa6ec4dab99b)
```


## Workflow Outputs
### Output Dataset: matches
```galaxy
history_dataset_display(history_dataset_id=a75e2a73312f71f2)
```
### Output Dataset: scores
```galaxy
history_dataset_display(history_dataset_id=ba83fbc0968ad193)
```



