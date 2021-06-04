# logfoldchange_app

##### Description

`logfoldchange_app` is an application that calculates the ratio (fold change) between a control and treatment condition after log conversion.

##### Details

The application consists of a data input, a workflow and a data output. 

The input data is the [ptk dataset](https://tercen.com/r/35c33fa33c9e6aba0dce6483f5f70135)

This workflow has 4 operators:
- [log_cutoff_operator](https://github.com/tercen/log_cutoff_operator)
- [identity_operator](https://github.com/tercen/identity_operator)
- [minus_operator](https://github.com/tercen/minus_operator)
- [mean_operator](https://github.com/tercen/mean_operator)

##### See Also

[logfoldchange_app](https://github.com/tercen/logfoldchange_app)
