# Overview

Module Name: Letras Analytics Adapter
Module Type: Analytics Adapter

# Description
Analytics adapter for <a href="https://letras.com/">Letras</a>. 

# Test Parameters

```
pbjs.enableAnalytics({
    provider: 'letras',
});

```

# Advanced Parameters

```
pbjs.enableAnalytics({
    provider: 'letras',
    options: {
        bundleId: '04bcf17b-9733-4675-9f67-d475f881ab78',
        version: 'v1', // configuration version for the comparison
        url: 'https://letras.com/endpoint'
        adUnitDict: { // provide names of the ad units for better reporting 
            adunitid1: 'Top Banner',
            adunitid2: 'Bottom Banner'
        },
        customParam: { // provide custom parameters values that you want to collect and report
            env: 'prod',
            param1: 'value1',
            param2: 'value2'
        }
    }
});

```
