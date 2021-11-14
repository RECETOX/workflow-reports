
# GC Workflow Execution Summary - The October Prototype

This is a Galaxy Page describing the GC October prototype workflow run on the Seminal plasma dilution series dataset available in the RECETOX [data library](https://umsa.cerit-sc.cz/libraries/folders/F0e4be62618e2118d).

## Workflow Inputs
We define three inputs: the collection of raw datasets, dataset of Reference Alcanes for RIAssigner, and a reference spectral library for MatchMS.

### Input Dataset Collection: a mzML collection
This is the main data input -- a collection of GC Seminal Plasma Dilution Series data in the mzML format, converted from the .RAW format by the ThermoRawFileConverter tool.

```galaxy
history_dataset_collection_display(history_dataset_collection_id=eb3aea3788221c57)
```

#### Input Dataset: Reference Alcanes
```galaxy
history_dataset_display(history_dataset_id=cb54a9b5ea991e6a)
```

### Input Dataset: Reference Spectral Library
```galaxy
history_dataset_display(history_dataset_id=8d60b9235512eeee)
```

## Executed Workflow
The following describes all undertaken workflow steps and default tool parameters.

```galaxy
workflow_display(workflow_id=bb7d1d57fc91145a)
```

## Workflow Outputs

### Output Dataset: Scores and Matches

The following parameters were used to format and filter matches and scores of interest

```galaxy
job_parameters(job_id=b23224566f16c5a3)
```
```galaxy
job_parameters(job_id=07f9cf75d8c68c2b)
```

The columns are ordered as: `query/reference/matches/score`
```galaxy
history_dataset_peek(history_dataset_id=90871140432e5f76)
```

The full filtered dataset is available here:
```galaxy
history_dataset_display(history_dataset_id=90871140432e5f76)
```
