# Spotter Documentation

## Changing Default Settings

### Change the Default Units

<table style="border-collapse: collapse; border: none; width: 100%;">
  <tr>
    <td style="border: none; vertical-align: middle; text-align: left; padding-right: 16px; padding-bottom: 16px;">
      1. Navigate to Spotter Server Settings.
    </td>
    <td style="border: none; vertical-align: middle; text-align: center; padding-bottom: 16px;">
      <img src="images/image1.png" alt="Spotter Server Settings icon" style="display: block; margin: 0 auto;" />
    </td>
  </tr>
  <tr>
    <td style="border: none; vertical-align: middle; text-align: left; padding-right: 16px; padding-bottom: 16px;">
      2. Go to the <strong>Settings</strong> tab.
    </td>
    <td style="border: none; vertical-align: middle; text-align: center; padding-bottom: 16px;">
      <img src="images/image3.png" alt="Settings tab" style="display: block; margin: 0 auto;" />
    </td>
  </tr>
  <tr>
    <td style="border: none; vertical-align: middle; text-align: left; padding-right: 16px;">
      3. Set <strong>Speed</strong> to <strong>Meters per second (m/s)</strong> and <strong>Distance</strong> to <strong>Meters (m)</strong>.
    </td>
    <td style="border: none; vertical-align: middle; text-align: center;">
      <img src="images/image2.png" alt="Units set to meters" style="display: block; margin: 0 auto;" />
    </td>
  </tr>
</table>


## Creating Filters

Create filters by going to **Filter** and clicking the **+** button.

<table style="border-collapse: collapse; border: none; width: 100%; margin-top: 8px;">
  <tr>
    <td style="border: none; vertical-align: middle; text-align: center; padding-right: 16px;">
      <img src="images/image5.png" alt="Filter list" style="display: block; margin: 0 auto;" />
    </td>
    <td style="border: none; vertical-align: middle; text-align: center;">
      <img src="images/image4.png" alt="Create filter" style="display: block; margin: 0 auto;" />
    </td>
  </tr>
</table>


### People Filter

Filter: **People** is a default, so you just need to modify the default *People* filter.

<table style="border-collapse: collapse; border: none; width: 100%; margin-top: 8px;">
  <tr>
    <td style="border: none; vertical-align: middle; text-align: left; padding-right: 16px;">
      <ul>
        <li>Remove the upper bounds of speed.</li>
        <li>Change duration to <strong>5 seconds</strong>.</li>
        <li>Select appropriate radars (usually can set to <strong>all ground radars</strong>).</li>
        <li>Replace distance with <strong>Displacement ≥ 10 m</strong>.</li>
      </ul>
    </td>
    <td style="border: none; vertical-align: middle; text-align: center;">
      <img src="images/image7.png" alt="People filter configuration" style="display: block; margin: 0 auto;" />
    </td>
  </tr>
</table>


### Unknown Filter

Filter: **Unknown** is not a default and needs to be created manually.

<table style="border-collapse: collapse; border: none; width: 100%; margin-top: 8px;">
  <tr>
    <td style="border: none; vertical-align: middle; text-align: left; padding-right: 16px;">
      <ul>
        <li>Set <strong>Type</strong> to <strong>Unknown</strong> with <strong>0% confidence</strong>.</li>
        <li>Select appropriate radars (usually can set to <strong>all ground radars</strong>).</li>
      </ul>
    </td>
    <td style="border: none; vertical-align: middle; text-align: center;">
      <img src="images/image6.png" alt="Unknown filter configuration" style="display: block; margin: 0 auto;" />
    </td>
  </tr>
</table>


### Vehicle Filter

Filter: **Vehicles** is a default, so you just need to modify the default *Vehicles* filter.

<table style="border-collapse: collapse; border: none; width: 100%; margin-top: 8px;">
  <tr>
    <td style="border: none; vertical-align: middle; text-align: left; padding-right: 16px;">
      <ul>
        <li>Remove the lower bounds of speed.</li>
        <li>Change duration to <strong>5 seconds</strong>.</li>
        <li>Select appropriate radars (usually can set to <strong>all ground radars</strong>).</li>
        <li>Replace distance with <strong>Displacement ≥ 15 m</strong>.</li>
      </ul>
    </td>
    <td style="border: none; vertical-align: middle; text-align: center;">
      <img src="images/image9.png" alt="Vehicle filter configuration" style="display: block; margin: 0 auto;" />
    </td>
  </tr>
</table>


## Creating Classifications

<table style="border-collapse: collapse; border: none; width: 100%;">
  <tr>
    <td style="border: none; vertical-align: middle; text-align: left; padding-right: 16px;">
      <p>Classifications are a type of <strong>Action</strong>.</p>
      <ul>
        <li>Create a new action by clicking the <strong>+</strong> icon.</li>
        <li>Set the <strong>Type</strong> to <strong>Classification</strong>.</li>
      </ul>
    </td>
    <td style="border: none; vertical-align: middle; text-align: center;">
      <img src="images/image12.png" alt="New classification action" style="display: block; margin: 0 auto;" />
    </td>
  </tr>
</table>


### Probable People Classification

<table style="border-collapse: collapse; border: none; width: 100%; margin-top: 8px;">
  <tr>
    <td style="border: none; vertical-align: middle; text-align: left; padding-right: 16px;">
      <ul>
        <li>Set the name to <strong>“Probable Person”</strong>.</li>
        <li>Set the <strong>Type</strong> to <strong>Person</strong>.</li>
        <li>Set the <strong>Intent</strong> to <strong>Unknown</strong>.</li>
      </ul>
    </td>
    <td style="border: none; vertical-align: middle; text-align: center;">
      <img src="images/image10.png" alt="Probable Person classification" style="display: block; margin: 0 auto;" />
    </td>
  </tr>
</table>


### Probable Vehicle Classification

<table style="border-collapse: collapse; border: none; width: 100%; margin-top: 8px;">
  <tr>
    <td style="border: none; vertical-align: middle; text-align: left; padding-right: 16px;">
      <ul>
        <li>Set the name to <strong>“Probable Vehicle”</strong>.</li>
        <li>Set the <strong>Type</strong> to <strong>Vehicle</strong>.</li>
        <li>Set the <strong>Intent</strong> to <strong>Unknown</strong>.</li>
      </ul>
    </td>
    <td style="border: none; vertical-align: middle; text-align: center;">
      <img src="images/image11.png" alt="Probable Vehicle classification" style="display: block; margin: 0 auto;" />
    </td>
  </tr>
</table>


## Setting Radar Sensitivity

### Default

<table style="border-collapse: collapse; border: none; width: 100%;">
  <tr>
    <td style="border: none; vertical-align: middle; text-align: left; padding-right: 16px; padding-bottom: 16px;">
      <ul>
        <li>Go to <strong>Settings</strong>.</li>
        <li>Go to <strong>Devices</strong>.</li>
        <li>Select desired radar.</li>
        <li>Go to <strong>Sensitivity</strong>.</li>
      </ul>
    </td>
    <td style="border: none; vertical-align: middle; text-align: center; padding-bottom: 16px;">
      <img src="images/image13.png" alt="Radar device sensitivity view" style="display: block; margin: 0 auto;" />
    </td>
  </tr>
  <tr>
    <td style="border: none; vertical-align: middle; text-align: left; padding-right: 16px;">
      <ul>
        <li>Select the preset <strong>“Medium Wind”</strong>.</li>
        <li>In some firmware, it is just called <strong>“Medium”</strong>.</li>
      </ul>
    </td>
    <td style="border: none; vertical-align: middle; text-align: center;">
      <img src="images/image14.png" alt="Medium wind preset" style="display: block; margin: 0 auto;" />
    </td>
  </tr>
</table>


## Adding Zone Classifications

### Classification: Probable People

<table style="border-collapse: collapse; border: none; width: 100%;">
  <tr>
    <td style="border: none; vertical-align: middle; text-align: left; padding-right: 16px; padding-bottom: 16px;">
      <ul>
        <li>Go to <strong>Settings</strong>.</li>
        <li>Go to <strong>Zones</strong>.</li>
        <li>Select desired Zone.</li>
        <li>Go to <strong>Actions</strong>.</li>
      </ul>
    </td>
    <td style="border: none; vertical-align: middle; text-align: center; padding-bottom: 16px;">
      <img src="images/image15.png" alt="Zone actions view" style="display: block; margin: 0 auto;" />
    </td>
  </tr>
  <tr>
    <td style="border: none; vertical-align: middle; text-align: left; padding-right: 16px; padding-bottom: 16px;">
      <ul>
        <li>Add a new action.</li>
      </ul>
    </td>
    <td style="border: none; vertical-align: middle; text-align: center; padding-bottom: 16px;">
      <img src="images/image16.png" alt="Add action button" style="display: block; margin: 0 auto;" />
    </td>
  </tr>
  <tr>
    <td style="border: none; vertical-align: middle; text-align: left; padding-right: 16px;">
      <ul>
        <li>Set <strong>Type</strong> to <strong>Classification</strong>.</li>
        <li>Set <strong>Action</strong> to your <strong>“Classification: Probable Person”</strong> you created.</li>
        <li>Set <strong>Filter Group</strong> to <strong>People</strong>.</li>
        <li>Click <strong>Add</strong>.</li>
      </ul>
    </td>
    <td style="border: none; vertical-align: middle; text-align: center;">
      <img src="images/image17.png" alt="Probable Person zone classification action" style="display: block; margin: 0 auto;" />
    </td>
  </tr>
</table>


### Classification: Probable Vehicle

<table style="border-collapse: collapse; border: none; width: 100%;">
  <tr>
    <td style="border: none; vertical-align: middle; text-align: left; padding-right: 16px; padding-bottom: 16px;">
      <ul>
        <li>Go to <strong>Settings</strong>.</li>
        <li>Go to <strong>Zones</strong>.</li>
        <li>Select desired Zone.</li>
        <li>Go to <strong>Actions</strong>.</li>
      </ul>
    </td>
    <td style="border: none; vertical-align: middle; text-align: center; padding-bottom: 16px;">
      <img src="images/image15.png" alt="Zone actions view" style="display: block; margin: 0 auto;" />
    </td>
  </tr>
  <tr>
    <td style="border: none; vertical-align: middle; text-align: left; padding-right: 16px; padding-bottom: 16px;">
      <ul>
        <li>Add a new action.</li>
      </ul>
    </td>
    <td style="border: none; vertical-align: middle; text-align: center; padding-bottom: 16px;">
      <img src="images/image16.png" alt="Add action button" style="display: block; margin: 0 auto;" />
    </td>
  </tr>
  <tr>
    <td style="border: none; vertical-align: middle; text-align: left; padding-right: 16px;">
      <ul>
        <li>Set <strong>Type</strong> to <strong>Classification</strong>.</li>
        <li>Set <strong>Action</strong> to your <strong>“Classification: Probable Vehicle”</strong> you created.</li>
        <li>Set <strong>Filter Group</strong> to <strong>Vehicles</strong>.</li>
        <li>Click <strong>Add</strong>.</li>
      </ul>
    </td>
    <td style="border: none; vertical-align: middle; text-align: center;">
      <img src="images/image18.png" alt="Probable Vehicle zone classification action" style="display: block; margin: 0 auto;" />
    </td>
  </tr>
</table>