# MobiFix: A quest for fault types
## What is this?

The data in the mobiles.csv file is the result of two online quests where volunteer participants looked at about 1900 mobile phone repair attempts recorded at community events. For more information about repair events and repair data, visit the [Open Repair Alliance](https://openrepair.org/open-data/) website.

The tableschema.json file describes the data structure, validation, licensing and source.

There are some differences in the structure of this data and any of the ORDS format versions (0.1 and 0.2). The records involved span different ORDS versions and a handful have not yet been exported.

1. The usual ORDS `id` values have been replaced by special mobifix-specific unique identifiers
2. The `model` field was removed from the ORDS v0.2 standard but was useful for these quests and so has been retained in this dataset
3. Age is an important metric in repair policy, therefore it was derived from and replaced the `year_of_manufacture` field
4. The field `group_identifier` is irrelevent in this analysis and thus has been omitted from the dataset
## Where did it come from?

[MobiFix](https://talk.restarters.net/mobifix/status) was held in July 2020 using data from ORA partner The Restart Project.

[MobiFix:ORA](https://restarters.net/mobifixora/status) was held in March 2021 using data from ORA partners anstiftung and Repair Café International.
## What was MobiFix all about?

The aim of these quests was to sort the records into buckets of fault “types”.

Community repair events are busy with volunteers concentrating their efforts on the people and the devices that turn up. The data that gets recorded by a fixer is their description of the situation at the time. Our participants would read this "problem" text and judge whether it fitted any of the "fault types" that were presented.

![MobiFix:ORA screenshot](images/mobifixora-screenshot.png)