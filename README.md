# *LAHAJA*: A Robust Multi-accent Benchmark for Evaluating Hindi ASR Systems

Hindi, one of the most spoken language of India, exhibits a diverse array of accents due to its usage among individuals from diverse linguistic origins. To enable a robust evaluation of Hindi ASR systems on multiple accents, we create a benchmark, *LAHAJA*, which contains read and extempore speech on a diverse set of topics and use cases, with a total of 12.5 hours of Hindi audio, sourced from 132 speakers spanning 83 districts of India. We evaluate existing open-source and commercial models on *LAHAJA* and find their performance to be poor. We then train models using different datasets and find that our model trained on multilingual data with good speaker diversity outperforms existing models by a significant margin. We also present a fine grained analysis which shows that the performance declines for speakers from North-East and South India, especially with content heavy in named entities and specialized terminology.

## Resources
 

|Resource name | link |
| - | - |
| Dataset | [Lahaja](https://indic-asr-public.objectstore.e2enetworks.net/lahaja_artifacts/lahaja.tgz) |
| Model - M1 | [Coming soon]() |
| Model - M2 | [Coming soon]() |
| Model - M3 | [Coming soon]() |
| Model - M4 | [Coming soon]() |


## Dataset details

The lahaja contains two thing: 
- `audio` folder which contains all the speech data
- `meta-data-lahaja.csv` mapping file, that contains transcripts along with the additional speaker details (given below)


The csv contains the following data with respect to the audio:
* `verbatim` -- Verbatim version of the transcript.
* `normalized` -- Normalized version of the transcript.
* `duration` -- Duration of audio recorded (seconds)
* `scenario` -- Type of speech data (read/extempore)
* `fname` -- File name
* `native_language` -- Native language of the participant 
* `gender` -- Gender (Male/Female)
* `age_group` -- Age group of the participant
* `native_state` -- Speaker's native state
* `native_district` -- Speaker's native district
* `sp_id` -- Unique speaker id
* `text` -- Cleaned version of normalized transcript (after braces removal).
* `lang` -- langauge id (hi)
* `job_category` -- speaker's job category
* `occupation_domain` -- speaker's domain of occupation (Education and Research, Healthcare [Medical & Pharma], Government, Technology and Services, Information and Media, Financial Services [Banking and Insurance], Transportation and Logistics, Entertainment, Social service, Manufacturing & Retail)
* `occupation` -- Speaker's occupation
* `job_type` -- speakers's job category (Part Time, Full Time, Other)
* `age-group` -- speaker's age group (18-30, 30-45, 45-60 & 60+ )
* `qual` -- speaker's highest education qualification

 - Lahaja folder tree

    ```
      Lahaja
          ├── audio
          │   ├── <filename>.wav
          │    .
          │    .
          │    .
          └── meta-data-lahaja.csv    
    ```


***

<!-- 
# Citation
If you benefit from this dataset, kindly cite as follows:

```
@misc{
    to be updated
} -->
```

