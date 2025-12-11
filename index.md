# Spotter Documentation

## Changing Default Settings

### Change the Default Units

| Step | Screenshot |
| --- | --- |
| 1. Navigate to Spotter Server Settings. <br> 2. Go to the **Settings** tab. <br> 3. Set **Speed** to **Meters per Second** and **Distance** to **Meters**. | ![Spotter Server Settings](images/image1.png) <br><br> ![Settings tab](images/image3.png) <br><br> ![Units set to meters](images/image2.png) |


## Creating Filters

| Description | Screenshots |
| --- | --- |
| Create filters by going to **Filter** and clicking the **+** button. | ![Filter list](images/image5.png) <br><br> ![Create filter](images/image4.png) |


### People Filter

| Instructions | Screenshot |
| --- | --- |
| Filter: **People** is a default, so you just need to modify the default *People* filter. <br><br>• Remove the upper bounds of speed. <br>• Change duration to **5 seconds**. <br>• Select appropriate radars (usually can set to **all ground radars**). <br>• Replace distance with **Displacement ≥ 10 m**. | ![People filter configuration](images/image7.png) |


### Unknown Filter

| Instructions | Screenshot |
| --- | --- |
| Filter: **Unknown** is not a default and needs to be created manually. <br><br>• Set **Type = Unknown** with **0% confidence**. <br>• Select appropriate radars (usually can set to **all ground radars**). | ![Unknown filter configuration](images/image6.png) |


### Vehicle Filter

| Instructions | Screenshot |
| --- | --- |
| Filter: **Vehicles** is a default, so you just need to modify the default *Vehicles* filter. <br><br>• Remove the lower bounds of speed. <br>• Change duration to **5 seconds**. <br>• Select appropriate radars (usually can set to **all ground radars**). <br>• Replace distance with **Displacement ≥ 15 m**. | ![Vehicle filter configuration](images/image9.png) |


## Creating Classifications

| Instructions | Screenshots |
| --- | --- |
| Classifications are a type of **Action**. <br><br>1. Go to **Actions**. <br>2. Create a new action by clicking the **+** icon. <br>3. Set the **Type** to **Classification**. | ![Actions list](images/image8.png) <br><br> ![New classification action](images/image12.png) |


### Probable People Classification

| Instructions | Screenshot |
| --- | --- |
| • Set the name to **“Probable Person”**. <br>• Set the **Type** to **Person**. <br>• Set the **Intent** to **Unknown**. | ![Probable Person classification](images/image10.png) |


### Probable Vehicle Classification

| Instructions | Screenshot |
| --- | --- |
| • Set the name to **“Probable Vehicle”**. <br>• Set the **Type** to **Vehicle**. <br>• Set the **Intent** to **Unknown**. | ![Probable Vehicle classification](images/image11.png) |


## Setting Radar Sensitivity

### Default Sensitivity

| Instructions | Screenshots |
| --- | --- |
| 1. Go to **Settings**. <br>2. Go to **Devices**. <br>3. Select the desired radar. <br>4. Go to **Sensitivity**. <br>5. Select the preset **“Medium Wind”**. <br>   • In some firmware, it is just called **“Medium”**. | ![Radar device sensitivity view](images/image13.png) <br><br> ![Medium wind preset](images/image14.png) |


## Adding Zone Classifications

### Classification: Probable People

| Instructions | Screenshots |
| --- | --- |
| 1. Go to **Settings**. <br>2. Go to **Zones**. <br>3. Select the desired Zone. <br>4. Go to **Actions**. <br>5. Add a new action. <br>6. Configure the action: <br>&nbsp;&nbsp;• Set **Type** to **Classification**. <br>&nbsp;&nbsp;• Set **Action** to your **“Classification: Probable Person”** you created. <br>&nbsp;&nbsp;• Set **Filter Group** to **People**. <br>&nbsp;&nbsp;• Click **Add**. | ![Zone actions view](images/image15.png) <br><br> ![Add action button](images/image16.png) <br><br> ![Probable Person zone classification action](images/image17.png) |


### Classification: Probable Vehicle

| Instructions | Screenshots |
| --- | --- |
| 1. Go to **Settings**. <br>2. Go to **Zones**. <br>3. Select the desired Zone. <br>4. Go to **Actions**. <br>5. Add a new action. <br>6. Configure the action: <br>&nbsp;&nbsp;• Set **Type** to **Classification**. <br>&nbsp;&nbsp;• Set **Action** to your **“Classification: Probable Vehicle”** you created. <br>&nbsp;&nbsp;• Set **Filter Group** to **Vehicles**. <br>&nbsp;&nbsp;• Click **Add**. | ![Zone actions view](images/image15.png) <br><br> ![Add action button](images/image16.png) <br><br> ![Probable Vehicle zone classification action](images/image18.png) |