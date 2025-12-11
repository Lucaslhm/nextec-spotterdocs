# Spotter Documentation

## Changing Default Settings

### Change the Default Units

1. Navigate to Spotter Server Settings.

   ![Spotter Server Settings](images/image1.png)

2. Go to the **Settings** tab.

   ![Settings tab](images/image3.png)

3. Set **Speed** to **Meters per Second** and **Distance** to **Meters**.

   ![Units set to meters](images/image2.png)


## Creating Filters

Create filters by going to **Filter** and clicking the **+** button.

![Filter list](images/image5.png)
![Create filter](images/image4.png)

### People Filter

Filter: **People** is a default, so you just need to modify the default *People* filter.

- Remove the upper bounds of speed.
- Change duration to **5 seconds**.
- Select appropriate radars (usually can set to **all ground radars**).
- Replace distance with **Displacement ≥ 10 m**.

![People filter configuration](images/image7.png)

### Unknown Filter

Filter: **Unknown** is not a default and needs to be created manually.

- Set **Type = Unknown** with **0% confidence**.
- Select appropriate radars (usually can set to **all ground radars**).

![Unknown filter configuration](images/image6.png)

### Vehicle Filter

Filter: **Vehicles** is a default, so you just need to modify the default *Vehicles* filter.

- Remove the lower bounds of speed.
- Change duration to **5 seconds**.
- Select appropriate radars (usually can set to **all ground radars**.
- Replace distance with **Displacement ≥ 15 m**.

![Vehicle filter configuration](images/image9.png)


## Creating Classifications

Classifications are a type of **Action**.

![Actions list](images/image8.png)

1. Create a new action by clicking the **+** icon.
2. Set the **Type** to **Classification**.

![New classification action](images/image12.png)

### Probable People Classification

- Set the name to **“Probable Person”**.
- Set the **Type** to **Person**.
- Set the **Intent** to **Unknown**.

![Probable Person classification](images/image10.png)

### Probable Vehicle Classification

- Set the name to **“Probable Vehicle”**.
- Set the **Type** to **Vehicle**.
- Set the **Intent** to **Unknown**.

![Probable Vehicle classification](images/image11.png)


## Setting Radar Sensitivity

### Default

1. Go to **Settings**.
2. Go to **Devices**.
3. Select the desired radar.
4. Go to **Sensitivity**.

![Radar device sensitivity view](images/image13.png)

5. Select the preset **“Medium Wind”**.  
   - In some firmware, it is just called **“Medium”**.

![Medium wind preset](images/image14.png)


## Adding Zone Classifications

### Classification: Probable People

1. Go to **Settings**.
2. Go to **Zones**.
3. Select the desired Zone.
4. Go to **Actions**.

![Zone actions view](images/image15.png)

5. Add a new action.

![Add action button](images/image16.png)

6. Configure the action:

   - Set **Type** to **Classification**.
   - Set **Action** to your **“Classification: Probable Person”** you created.
   - Set **Filter Group** to **People**.
   - Click **Add**.

![Probable Person zone classification action](images/image17.png)

### Classification: Probable Vehicle

1. Go to **Settings**.
2. Go to **Zones**.
3. Select the desired Zone.
4. Go to **Actions**.

![Zone actions view](images/image15.png)

5. Add a new action.

![Add action button](images/image16.png)

6. Configure the action:

   - Set **Type** to **Classification**.
   - Set **Action** to your **“Classification: Probable Vehicle”** you created.
   - Set **Filter Group** to **Vehicles**.
   - Click **Add**.

![Probable Vehicle zone classification action](images/image18.png)