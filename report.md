## **Testing battery longevity in AudioMoths and Song Meter Micros under various conditions.** 

Nickolus Stahlman

[<u>nls92@pitt.edu</u>](mailto:nls92@pitt.edu)

**Summary** – I evaluated the longevity of batteries used in Song Meter
Micro (SMM) and AudioMoth Autonomous Recording Units (ARUs) at varying
settings of sample rate, gain, temperature, and battery type. The
control settings used for SMMs included a 32kHz sample rate with 18dB
gain using Duracell Procell PC1500 AA batteries (Procell) to record at
room temperature which recorded an average of 139 hours of audio. The
lowest sample rate setting of 8kHz would increase the hours of audio by
61% and the highest sample rate setting of 96kHz would decrease the
hours of audio by 34%. A sample rate of 96kHz caused the 64GB SD card to
fill up before the batteries died; however, the batteries would die once
the device was rebooted with a new SD card. The change of gain had a
negligible effect on hours of audio recorded. Performance of the Procell
batteries decreased by 10% at cold temperatures and by 43% at freezing
temperatures. Energizer Ultimate Lithium AA (Lithium) batteries
increased hours of audio recorded by 24% and performed at relatively
consistent levels across room, cold, and freezing temperatures. Lithium
batteries double the hours of audio recorded at freezing temperatures
compared to Procell batteries at the same temperature. Panasonic
Alkaline Power Plus AA (Panasonic) batteries were only tested at room
temperature and resulted in a decrease of 10% in hours of audio.

The control settings used for the AudioMoths included a 32kHz sample
rate with the medium gain setting using Procell batteries to record at
room temperature which recorded an average of 189 hours of audio. The
lowest sample rate setting of 8kHz would increase the hours of audio by
30% and the highest sample rate setting of 384kHz would decrease the
hours of audio by 77%. Sample rates higher than 48kHz would result in
the 64GB SD card to fill up before the batteries died. The change of
gain had a negligible effect on hours of audio recorded. Performance of
the Procell batteries decreased by 3% at cold temperatures and by 46% at
freezing temperatures. Lithium batteries increased hours of audio
recorded by 26% and performed at relatively consistent levels across
room, cold, and freezing temperatures. Panasonic batteries were only
tested at room temperature and resulted in a decrease of 7% in hours of
audio.

## <img src="media/image2.png" style="width:8.6712in;height:2.97396in" /><img src="media/image1.png" style="width:8.77604in;height:2.95582in" />

## **Table of Contents**

[1.0 Introduction](#10-introduction)

[2.0 Methods](#20-methods)

> [2.1 Song Meter Micro Trials](#21-song-meter-micro-trials)
>
> [2.2 AudioMoth Trials](#22-audiomoth-trials)
>
> [2.3 High Sample Rates](#23-high-sample-rates)

[3.0 Song Meter Micro Results](#30-song-meter-micro-results)

> [3.1 Sample Rate Trials](#31-sample-rate-trials)
>
> [3.2 Gain Trials](#32-gain-trials)
>
> [3.3 Temperature Trials](#33-temperature-trials)
>
> [3.4 Battery Type Trials](#34-battery-type-trials)

[4.0 AudioMoth Results](#40-audiomoth-results)

> [4.1 Sample Rate Trials](#41-sample-rate-trials)
>
> [4.2 Gain Trials](#42-gain-trials)
>
> [4.3 Temperature Trials](#43-temperature-trials)
>
> [4.4 Battery Type Trials](#44-battery-type-trials)

[5.0 Discussion](#50-discussion)

## 

## 

## **List of Tables**

-   **<a href="#table-1">Table 1</a>** **–** Hours of audio recorded by each SMM at varying sample rates and the mean time for each sample rate

-   **<a href="#table-2">Table 2</a>** **–** Hours of audio recorded by each SMM at varying gains and the mean time for each gain

-   **<a href="#table-3">Table 3</a>** **–** Hours of audio recorded by each SMM using Procell batteries at varying temperatures and the mean time for each temperature

-   **<a href="#table-4">Table 4</a>** **–** Hours of audio recorded by each SMM using Energizer Ultimate Lithium batteries at varying temperatures and the mean time for each temperature

-   **<a href="#table-5">Table 5</a>** **–** Hours of audio recorded by each SMM using varying battery types and the mean time for each battery type

-   **<a href="#table-6">Table 6</a>** **–** Hours of audio recorded by each AudioMoth at varying sample rates and the mean time for each sample rate

-   **<a href="#table-7">Table 7</a>** **–** The average data written to the SD cards at each sample rate avaialbe on AudioMoths

-  **<a href="#table-8">Table 8</a>** **–** Hours of audio recorded by each AudioMoth at varying gains and the mean time for each gain

-   **<a href="#table-9">Table 9</a>** **–** Hours of audio recorded by each AudioMoth using Procell batteries at varying temperatures and the mean time for eah temperature

-   **<a href="#table-10">Table 10</a>** **–** Hours of audio recorded by each AudioMoth using Energizer Ultimate Lithium batteries at varying temperatures and the mean time for each temperature

-   **<a href="#table-11">Table 11</a>** **–** Hours of audio recorded by each AudioMoth using varying battery types and the mean time for each battery type

-   **<a href="#table-12">Table 12</a>** **–** A comparison of average hours of audio recorded by SMMs and AudioMoths at similar sample rates

-   **<a href="#table-13">Table 13</a>** **–** A comparison of average hours of audio recorded by SMMs and AudioMoths at different temperature ranges using Procell or Lithium batteries

-   **<a href="#table-14">Table 14</a>** **–** A comparison of average cost per battery type used (as of January 2023) and the percent difference in hours of audio recorded using each battery type at various temperature ranges

## 

## 

## 1.0 Introduction

Autonomous Recording Units (ARUs) are becoming an increasingly vital
component to ecological research. AudioMoths are affordable ARUs
developed by Open Acoustic Devices to offer a lightweight design and
easy configurability. AudioMoths are designed for low power consumption,
and the configuration app will display the estimated daily power
consumption for the device based on the sample rate selected. However,
there is no change to estimated power consumption from changes to gain,
and there is no consideration given to the temperature the AudioMoth
will be recording at.

The Song Meter Micro (SMM) is an ARU developed by Wildlife Acoustics
that offers a rugged case and Bluetooth capabilities. Wildlife Acoustics
reports that as of firmware 3.4 a SMM will run for 180 hours at a sample
rate of 24kHz using AA alkaline batteries. The mobile configuration app
provides an estimated date for battery depletion, and the current
estimated battery level in percentage or voltage when the SMM is
connected via Bluetooth. Both functions work together to provide an
accurate battery life estimate for the user; however, the effects of
temperature and gain settings are not considered.

There are no publicly available reports showing battery life tests of
AudioMoths or SMMs at various configuration settings or how temperature
may impact longevity. Therefore, I set out to test the battery life for
both AudioMoths and SMMs at each sample rate and gain setting and
determine what effect temperature has. I was also curious if there was a
discernible difference in longevity between alkaline battery brands, and
if lithium batteries significantly increased the total hours of recorded
audio.

## 2.0 Methods

A control configuration that reflected our most commonly used settings
was determined for each type of ARU, and then one parameter was changed
for each trial. An exception to this was temperature and battery type
were both altered to compare disposable lithium metal battery
performance at low temperatures. Each trial had three ARUs configured in
the same way, and all trials used 64GB SanDisk Ultra SD cards.

Temperature was divided into three categories: room (20.50°C), fridge
(3.4°C), and freezer (-16.1°C). The average temperature for each
category was determined using an infrared thermometer. Readings were
taken during the morning, midday, and evening for each condition and
across three separate days to establish the average temperature.

Duracell Procell PC1500 alkaline AA (Procell) batteries were used as the
control battery type throughout the trials. Procells were compared
against Panasonic Alkaline Plus Power AA (Panasonic) and Energizer
Ultimate Lithium AA (Lithium) batteries at room temperature.
Additionally, the longevity of Procell versus Lithium batteries at
fridge and freezer temperatures was compared.

#### 2.1 Song Meter Micro Trials

> **Control Configuration**
>
> Sample Rate: 32kHz
>
> Gain: 18dB
>
> Temperature: room
>
> Battery Type: Duracell Procell PC1500
>
> **Sample Rate Configuration:** A total of 24 SMMs were configured to
> record with an 18dB gain at room temperature with Procell batteries.
> Three SMMs were set to the same sample rate across each setting
> outside our control configuration (8, 12, 16, 22.05, 24, 44.1, 48, and
> 96kHz).
>
> **Gain Configuration**: A total of 9 SMMs were configured to record at
> a 32kHz sample rate at room temperature with Procell batteries. Three
> SMMs were set to record at the same gain across each setting outside
> our control configuration (6, 12, 24dB).
>
> **Temperature Trials:** A total of 12 SMMs were set to record at a
> sample rate of 32kHz with a 18dB gain. Six SMMs were powered with
> Procell batteries, and half were placed in the freezer and the other
> half in the fridge. The other 6 SMMs were powered with Lithium
> batteries, and half were placed in the freezer and the other half in
> the fridge.
>
> **Battery Type Trials:** A total of 6 SMMs were set to record at a
> sample rate of 32kHz with a 18dB gain at room temperature. Three were
> powered with Lithium batteries and three were powered with Panasonic
> batteries.

#### 2.2 AudioMoth Trials

> **Control Configuration**
>
> Sample Rate: 32kHz
>
> Gain: medium
>
> Temperature: room
>
> Battery Type: Duracell Procell PC1500
>
> **Sample Rate Configuration:** A total of 21 AudioMoths were
> configured to record with an 18dB gain at room temperature with
> Procell batteries. Three AudioMoths were set to the same sample rate
> across each setting outside our control configuration (8, 16, 48, 96,
> 192, 250, and 384kHz).
>
> **Gain Configuration**: A total of 12 AudioMoths were configured to
> record at a 32kHz sample rate at room temperature with Procell
> batteries. Three AudioMoths were set to record at the same gain across
> each setting outside our control configuration (low, low-medium,
> medium-high, and high).
>
> **Temperature Trials:** A total of 12 AudioMoths were set to record at
> a sample rate of 32kHz with a 18dB gain. Six AudioMoths were powered
> with Procell batteries, and half were placed in the freezer and the
> other half in the fridge. The other 6 AudioMoths were powered with
> lithium metal batteries, and half were placed in the freezer and the
> other half in the fridge.
>
> **Battery Type Trials:** A total of 6 AudioMoths were set to record at
> a sample rate of 32kHz with a 18dB gain at room temperature. Three
> were powered with Lithium batteries and three were powered with
> Panasonic batteries.

#### 2.3 High Sample Rates

> The first set of trials revealed that AudioMoths set to record at a
> sample rate of 96kHz or higher and SMMs set to 96kHz will fill up a
> 64GB SD card before the batteries die. An additional set of trials
> were run at these higher sample rates. All ARUs were set to the same
> settings used during the initial sample rate trials. The ARUs were
> monitored throughout the day, and a new SD card was placed in the
> device once the first SD card was filled up.

## 3.0 Song Meter Micro Results

#### 3.1 Sample Rate Trials

> The hours of audio recorded by each SMM at varying sample rates is
> summarized in Table 1 alongside the average across the three devices.
> A SMM records an average of 139 hours of audio at our control
> settings. The lowest sample rate would increase the hours recorded by
> 61% and the highest sample rate would decrease the hours recorded by
> 34%. Overall, there is a negative relationship between the sample rate
> setting and hours of audio. However, there are some discrepancies in
> linearity between categories.
>
> Sample rates of 16 and 24kHz allow for similar hours of audio to be
> recorded instead of a noticeable change between rates. A sample rate
> of 22.05kHz records 8% fewer hours of audio compared to a sample rate
> of 24kHz. Similarly, a sample rate of 44.1kHz records 3% fewer hours
> of audio compared to a sample rate of 48kHz.
>
> A sample rate of 96kHz would result in the SD card filling up before
> the batteries died; however, the batteries would die once the device
> was rebooted with a new SD card. This occurred in the three devices
> used in the initial trial and the three devices used in the high
> sample rate trial. Table 1 only shows hours of audio for the SMMs used
> in the first trial although the second trial had similar results.

<table>
<colgroup>
<col style="width: 17%" />
<col style="width: 20%" />
<col style="width: 19%" />
<col style="width: 18%" />
<col style="width: 24%" />
</colgroup>
<thead>
<tr class="header">
<th colspan="5"><strong><h4 id="table-1">TABLE 1: Hours of audio recorded by each
SMM at varying sample rates and the mean time for each sample
rate</strong></th></h4>
</tr>
<tr class="odd">
<th><strong>Sample Rate (kHz)</strong></th>
<th><p><u>SMM 1</u></p>
<p>Hours of Audio</p></th>
<th><p><u>SMM 2</u></p>
<p>Hours of Audio</p></th>
<th><p><u>SMM 3</u></p>
<p>Hours of Audio</p></th>
<th><strong>Mean Hours of Audio</strong></th>
</tr>
<tr class="header">
<th>8</th>
<th>221</th>
<th>225</th>
<th>225</th>
<th><strong>223</strong></th>
</tr>
<tr class="odd">
<th>12</th>
<th>180</th>
<th>187</th>
<th>181</th>
<th><strong>183</strong></th>
</tr>
<tr class="header">
<th>16</th>
<th>162</th>
<th>165</th>
<th>164</th>
<th><strong>164</strong></th>
</tr>
<tr class="odd">
<th>22.05</th>
<th>150</th>
<th>155</th>
<th>150</th>
<th><strong>152</strong></th>
</tr>
<tr class="header">
<th>24</th>
<th>166</th>
<th>166</th>
<th>163</th>
<th><strong>165</strong></th>
</tr>
<tr class="odd">
<th>32</th>
<th>138</th>
<th>139</th>
<th>141</th>
<th><strong>139</strong></th>
</tr>
<tr class="header">
<th>44.1</th>
<th>125</th>
<th>135</th>
<th>122</th>
<th><strong>127</strong></th>
</tr>
<tr class="odd">
<th>48</th>
<th>129</th>
<th>133</th>
<th>130</th>
<th><strong>131</strong></th>
</tr>
<tr class="header">
<th>96</th>
<th>92</th>
<th>92</th>
<th>92</th>
<th><strong>92</strong></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

#### 3.2 Gain Trials

> Table 2 shows that the average hours of audio recorded at the
> different gain settings varies by approximately 5%. The difference
> increases to a maximum of 9% when results are looked at individually.
> However, there is no pattern to the changes in hours of audio between
> the different gain settings.

<table>
<colgroup>
<col style="width: 17%" />
<col style="width: 20%" />
<col style="width: 19%" />
<col style="width: 18%" />
<col style="width: 24%" />
</colgroup>
<thead>
<tr class="header">
<th colspan="5"><h4 id="table-2">TABLE 2: Hours of audio recorded by each SMM at varying gains and the mean time for each gain.</h4></th>
</tr>
<tr class="odd">
<th><strong>Gain (dB)</strong></th>
<th><p><u>SMM 1</u></p>
<p>Hours of Audio</p></th>
<th><p><u>SMM 2</u></p>
<p>Hours of Audio</p></th>
<th><p><u>SMM 3</u></p>
<p>Hours of Audio</p></th>
<th><strong>Mean Hours of Audio</strong></th>
</tr>
<tr class="header">
<th>8</th>
<th>138</th>
<th>142</th>
<th>139</th>
<th><strong>140</strong></th>
</tr>
<tr class="odd">
<th>12</th>
<th>138</th>
<th>141</th>
<th>141</th>
<th><strong>140</strong></th>
</tr>
<tr class="header">
<th>18</th>
<th>137</th>
<th>134</th>
<th>129</th>
<th><strong>133</strong></th>
</tr>
<tr class="odd">
<th>24</th>
<th>136</th>
<th>142</th>
<th>137</th>
<th><strong>138</strong></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

#### 3.3 Temperature Trials

> The Procell temperature trials were consistent within temperature
> groups as shown in Table 3. Decreasing temperature resulted in a
> decrease in the hours of audio. SMMs placed in the fridge recorded 10%
> fewer hours, and SMMs placed in the freezer recorded 43% fewer hours.
>
> Table 4 shows the Lithium temperature trials also had consistency
> within temperature groups and, to some degree, across temperature
> groups. Interestingly, the Lithium batteries performed better as the
> temperature was decreased. When compared to the SMMs at room
> temperature, SMMs placed in the fridge recorded 5% more hours of audio
> and the SMMs in the freezer recorded 7% more.


<table>
<colgroup>
<col style="width: 21%" />
<col style="width: 19%" />
<col style="width: 18%" />
<col style="width: 18%" />
<col style="width: 21%" />
</colgroup>
<thead>
<tr class="header">
<th colspan="5"><strong><h4 id="table-3">TABLE 3: Hours of audio recorded by each
SMM using Procell batteries at varying temperatures and the mean time
  for each temperature.</strong></h4></th>
</tr>
<tr class="odd">
<th><strong>Temperature</strong></th>
<th><p><u>SMM 1</u></p>
<p>Hours of Audio</p></th>
<th><p><u>SMM 2</u></p>
<p>Hours of Audio</p></th>
<th><p><u>SMM 3</u></p>
<p>Hours of Audio</p></th>
<th><strong>Mean Hours of Audio</strong></th>
</tr>
<tr class="header">
<th>Room (20.5°C)</th>
<th>138</th>
<th>139</th>
<th>414</th>
<th><strong>139</strong></th>
</tr>
<tr class="odd">
<th>Fridge (3.4°C)</th>
<th>127</th>
<th>124</th>
<th>125</th>
<th><strong>125</strong></th>
</tr>
<tr class="header">
<th>Freezer (-16.1°C)</th>
<th>79</th>
<th>80</th>
<th>80</th>
<th><strong>80</strong></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 21%" />
<col style="width: 19%" />
<col style="width: 18%" />
<col style="width: 18%" />
<col style="width: 21%" />
</colgroup>
<thead>
<tr class="header">
<th colspan="5"><strong><h4 id="table-4">TABLE 4: Hours of audio recorded by each
SMM using Energizer Ultimate Lithium batteries at varying temperatures
                            and the mean time for each temperature</strong></h4></th>
</tr>
<tr class="odd">
<th><strong>Temperature</strong></th>
<th><p><u>SMM 1</u></p>
<p>Hours of Audio</p></th>
<th><p><u>SMM 2</u></p>
<p>Hours of Audio</p></th>
<th><p><u>SMM 3</u></p>
<p>Hours of Audio</p></th>
<th><strong>Mean Hours of Audio</strong></th>
</tr>
<tr class="header">
<th>Room (20.5°C)</th>
<th>168</th>
<th>163</th>
<th>169</th>
<th><strong>167</strong></th>
</tr>
<tr class="odd">
<th>Fridge (3.4°C)</th>
<th>175</th>
<th>173</th>
<th>175</th>
<th><strong>174</strong></th>
</tr>
<tr class="header">
<th>Freezer (-16.1°C)</th>
<th>178</th>
<th>177</th>
<th>177</th>
<th><strong>177</strong></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

#### 3.4 Battery Type Trials

> Table 5 shows the differences between the three battery types used.
> The Panasonic batteries recorded 10% fewer hours of audio.
> Alternatively, the Lithium batteries increased the hours of audio by
> 24%.

<table>
<colgroup>
<col style="width: 21%" />
<col style="width: 19%" />
<col style="width: 18%" />
<col style="width: 18%" />
<col style="width: 21%" />
</colgroup>
<thead>
<tr class="header">
<th colspan="5"><strong><h4 id="table-5">TABLE 5: Hours of audio recorded by each
SMM using varying battery types and the mean time for each battery
  type</strong></h4></th>
</tr>
<tr class="odd">
<th><strong>Battery Type</strong></th>
<th><p><u>SMM 1</u></p>
<p>Hours of Audio</p></th>
<th><p><u>SMM 2</u></p>
<p>Hours of Audio</p></th>
<th><p><u>SMM 3</u></p>
<p>Hours of Audio</p></th>
<th><strong>Mean Hours of Audio</strong></th>
</tr>
<tr class="header">
<th>Procell</th>
<th>138</th>
<th>139</th>
<th>141</th>
<th><strong>139</strong></th>
</tr>
<tr class="odd">
<th>Panasonic</th>
<th>128</th>
<th>126</th>
<th>128</th>
<th><strong>127</strong></th>
</tr>
<tr class="header">
<th>Lithium</th>
<th>168</th>
<th>163</th>
<th>169</th>
<th><strong>167</strong></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

## 4.0 AudioMoth Results

#### 4.1 Sample Rate Trials

> The hours of audio recorded by each SMM at varying sample rates is
> summarized in Table 6 alongside the average across the three devices.
> A SMM records an average of 189 hours of audio at our control
> settings. The Audiomoths recorded a consistent amount of audio within
> each sample rate category. Overall, there is a negative relationship
> between the sample rate and the hours of audio the AudioMoth will
> record. Reducing the sample rate by half will increase the hours of
> audio recorded by 18%, and the lowest sample rate setting increases
> the hours of audio by 30%.
>
> Increasing the sample rate by one step results in a 15% decrease in
> hours, and the highest sample rate setting reduces the hours of audio
> recorded by 77%. Sample rates of 96kHz and higher filled up the 64GB
> SD card before the batteries died. A second trial for these higher
> sample rates was conducted and the SD card was replaced when the
> AudioMoth flashed green and red lights to signify a full card. The
> average data written to the cards before the batteries died is shown
> in Table 7. The total hours recorded between both cards is shown in
> Table 6, and these numbers are solely from the second trial.

<table>
<colgroup>
<col style="width: 17%" />
<col style="width: 20%" />
<col style="width: 19%" />
<col style="width: 18%" />
<col style="width: 24%" />
</colgroup>
<thead>
<tr class="header">
<th colspan="5"><strong><h4 id="table-6">TABLE 6: Hours of audio recorded by each
AudioMoths at varying sample rates and the mean time for each sample
  rate.</strong></h4></th>
</tr>
<tr class="odd">
<th><strong>Sample Rate (kHz)</strong></th>
<th><p><u>AudioMoth 1</u></p>
<p>Hours of Audio</p></th>
<th><p><u>AudiMoth 2</u></p>
<p>Hours of Audio</p></th>
<th><p><u>AudioMoth 3</u></p>
<p>Hours of Audio</p></th>
<th><strong>Mean Hours of Audio</strong></th>
</tr>
<tr class="header">
<th>8</th>
<th>247</th>
<th>249</th>
<th>251</th>
<th><strong>249</strong></th>
</tr>
<tr class="odd">
<th>16</th>
<th>224</th>
<th>225</th>
<th>225</th>
<th><strong>225</strong></th>
</tr>
<tr class="header">
<th>32</th>
<th>187</th>
<th>191</th>
<th>188</th>
<th><strong>189</strong></th>
</tr>
<tr class="odd">
<th>48</th>
<th>163</th>
<th>161</th>
<th>160</th>
<th><strong>161</strong></th>
</tr>
<tr class="header">
<th>96*</th>
<th>90</th>
<th>91</th>
<th>91</th>
<th><strong>91</strong></th>
</tr>
<tr class="odd">
<th>192*</th>
<th>61</th>
<th>59</th>
<th>61</th>
<th><strong>60</strong></th>
</tr>
<tr class="header">
<th>250*</th>
<th>47</th>
<th>47</th>
<th>47</th>
<th><strong>47</strong></th>
</tr>
<tr class="odd">
<th>384*</th>
<th>43</th>
<th>43</th>
<th>43</th>
<th><strong>43</strong></th>
</tr>
<tr class="header">
<th colspan="5">*Audio files at these sample rates filled the SD card
before the batteries depleted, and required a second SD card to be
inserted once the red and green LEDs began flashing.</th>
</tr>
</thead>
<tbody>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 5%" />
<col style="width: 5%" />
</colgroup>
<thead>
<tr class="header">
<th colspan="5"><strong><h4 id="table-7">TABLE 7: The average data written to the SD cards at each sample rate available on AudioMoths</strong></h4></th>
</tr>
<tr class="odd">
<th><strong>Sample Rate (kHz)</strong></th>
  <th><strong>Average data on SD card (GB)</strong>
</tr>
<tr class="header">
<th>8</th>
<th>13.2</th>
</tr>
<tr class="odd">
<th>16</th>
<th>24.0</th>
</tr>
<tr class="header">
<th>32</th>
<th>40.5</th>
</tr>
<tr class="odd">
<th>48</th>
<th>51.8</th>
</tr>
<tr class="header">
<th>96</th>
<th>61.8</th>
</tr>
<tr class="odd">
<th>192</th>
<th>80.1</th>
</tr>
<tr class="header">
<th>250</th>
<th>82.5</th>
</tr>
<tr class="odd">
<th>384</th>
<th>112.3</th>
</tr>
</tr>
</thead>
<tbody>
</tbody>
</table>

#### 4.2 Gain Trials

> The gain setting had a negligible effect on the total hours of audio
> recorded. The average across settings shown in Table 8 vary by a
> maximum of 2%. The individual recorders can vary from a couple of
> minutes to a few hours when compared against each other. However,
> there is no trend across the gain settings.

<table>
<colgroup>
<col style="width: 17%" />
<col style="width: 20%" />
<col style="width: 19%" />
<col style="width: 18%" />
<col style="width: 24%" />
</colgroup>
<thead>
<tr class="header">
<th colspan="5"><strong><h4 id="table-8">TABLE 8: Hours of audio recorded by each
AudioMoths at varying gains and the mean time for each
  gain.</strong></h4></th>
</tr>
<tr class="odd">
<th><strong>Gain Setting</strong></th>
<th><p><u>AudioMoth 1</u></p>
<p>Hours of Audio</p></th>
<th><p><u>AudiMoth 2</u></p>
<p>Hours of Audio</p></th>
<th><p><u>AudioMoth 3</u></p>
<p>Hours of Audio</p></th>
<th><strong>Mean Hours of Audio</strong></th>
</tr>
<tr class="header">
<th>low</th>
<th>186</th>
<th>190</th>
<th>187</th>
<th><strong>188</strong></th>
</tr>
<tr class="odd">
<th>low-medium</th>
<th>187</th>
<th>188</th>
<th>190</th>
<th><strong>188</strong></th>
</tr>
<tr class="header">
<th>medium</th>
<th>187</th>
<th>191</th>
<th>188</th>
<th><strong>189</strong></th>
</tr>
<tr class="odd">
<th>med-high</th>
<th>187</th>
<th>186</th>
<th>186</th>
<th><strong>186</strong></th>
</tr>
<tr class="header">
<th>high</th>
<th>187</th>
<th>191</th>
<th>187</th>
<th><strong>188</strong></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

#### 4.3 Temperature Trials

> The Procell temperature trials are summarized in Table 9. There is a
> 3% decrease in hours recorded between the controls and the devices
> placed in the fridge. The devices in the freezer recorded 46% fewer
> hours. The three devices in the fridge recorded a comparatively
> consistent number of hours. The freezer devices did vary a bit more
> with one device recording 50% fewer hours compared to the control
> settings.
>
> Table 10 shows the Lithium trials were relatively consistent across
> the temperature ranges. The Lithium batteries allowed for slightly
> more hours of audio to be recorded at lower temperatures. The devices
> placed in the fridge recorded 3% more hours of audio and the devices
> in the freezer recorded 2% more.

<table>
<colgroup>
<col style="width: 21%" />
<col style="width: 19%" />
<col style="width: 18%" />
<col style="width: 18%" />
<col style="width: 21%" />
</colgroup>
<thead>
<tr class="header">
<th colspan="5"><strong><h4 id="table-9">TABLE 9: Hours of audio recorded by each
AudioMoth using Procell batteries at varying temperatures and the mean
time for each temperature.</strong></th>
</tr>
<tr class="odd">
<th><strong>Temperature</strong></th>
<th><p><u>AudioMoth 1</u></p>
<p>Hours of Audio</p></th>
<th><p><u>AudioMoth 2</u></p>
<p>Hours of Audio</p></th>
<th><p><u>AudioMoth 3</u></p>
<p>Hours of Audio</p></th>
<th><strong>Mean Hours of Audio</strong></th>
</tr>
<tr class="header">
<th>Room (20.5°C)</th>
<th>187</th>
<th>191</th>
<th>188</th>
<th><strong>189</strong></th>
</tr>
<tr class="odd">
<th>Fridge (3.4°C)</th>
<th>184</th>
<th>181</th>
<th>185</th>
<th><strong>183</strong></th>
</tr>
<tr class="header">
<th>Freezer (-16.1°C)</th>
<th>105</th>
<th>103</th>
<th>99</th>
<th><strong>102</strong></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 21%" />
<col style="width: 19%" />
<col style="width: 18%" />
<col style="width: 18%" />
<col style="width: 21%" />
</colgroup>
<thead>
<tr class="header">
<th colspan="5"><strong><h4 id="table-10">TABLE 10: Hours of audio recorded by each
AudioMoth using Energizer Ultimate Lithium batteries at varying
  temperatures and the mean time for each temperature</strong></h4></th>
</tr>
<tr class="odd">
<th><strong>Temperature</strong></th>
<th><p><u>AudioMoth 1</u></p>
<p>Hours of Audio</p></th>
<th><p><u>AudioMoth 2</u></p>
<p>Hours of Audio</p></th>
<th><p><u>AudioMoth 3</u></p>
<p>Hours of Audio</p></th>
<th><strong>Mean Hours of Audio</strong></th>
</tr>
<tr class="header">
<th>Room (20.5°C)</th>
<th>228</th>
<th>236</th>
<th>239</th>
<th><strong>234</strong></th>
</tr>
<tr class="odd">
<th>Fridge (3.4°C)</th>
<th>244</th>
<th>239</th>
<th>241</th>
<th><strong>241</strong></th>
</tr>
<tr class="header">
<th>Freezer (-16.1°C)</th>
<th>241</th>
<th>236</th>
<th>237</th>
<th><strong>238</strong></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

#### 4.4 Battery Type Trials

> Table 11 shows the differences between the three types of batteries
> used. The Panasonic batteries recorded 7% fewer hours of audio. The
> Lithium batteries increase the hours recorded by 26%.

<table>
<colgroup>
<col style="width: 21%" />
<col style="width: 19%" />
<col style="width: 18%" />
<col style="width: 18%" />
<col style="width: 21%" />
</colgroup>
<thead>
<tr class="header">
<th colspan="5"><strong><h4 id="table-11">TABLE 11: Hours of audio recorded by each
AudioMoth using varying battery types and the mean time for each battery
  type</strong></h4></th>
</tr>
<tr class="odd">
<th><strong>Battery Type</strong></th>
<th><p><u>AudioMoth 1</u></p>
<p>Hours of Audio</p></th>
<th><p><u>AudioMoth 2</u></p>
<p>Hours of Audio</p></th>
<th><p><u>AudioMoth 3</u></p>
<p>Hours of Audio</p></th>
<th><strong>Mean Hours of Audio</strong></th>
</tr>
<tr class="header">
<th>Procell</th>
<th>187</th>
<th>191</th>
<th>188</th>
<th><strong>189</strong></th>
</tr>
<tr class="odd">
<th>Panasonic</th>
<th>180</th>
<th>176</th>
<th>174</th>
<th><strong>177</strong></th>
</tr>
<tr class="header">
<th>Lithium</th>
<th>228</th>
<th>236</th>
<th>239</th>
<th><strong>234</strong></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

## 5.0 Discussion

> The sample rate trials results were mostly in line with what was
> expected; as the sample rate is increased the hours of audio recorded
> will decrease due to more drain on the battery. This pattern is
> evident across shared sample rates between the SMMs and AudioMoths, as
> shown in Table 12. Table 13 shows the pattern is less evident across
> all SMM sample rates. Interestingly, sample rates of 44.1kHz and
> 22.05kHz went against the pattern, and both resulted in fewer hours
> recorded than the next highest sample rate.

<table>
<colgroup>
<col style="width: 17%" />
<col style="width: 20%" />
<col style="width: 19%" />
</colgroup>
<thead>
<tr class="header">
<th colspan="5"><strong><h4 id="table-12">TABLE 12: A comparison of average hours of audio recorded by SMMs and AudioMoths at similar sample rate settings</strong></h4></th>
</tr>
<tr class="odd">
<th><strong>Sample Rate (kHz)</strong></th>
<th><p><u>Average Hours of Audio for SMM</u></p></th>
<th><p><u>Average Hours of Audio for AudioMoth</u></p></th>
</tr>
<tr class="header">
<th>8</th>
<th>223</th>
<th>249</th>
</tr>
<tr class="odd">
<th>16</th>
<th>164</th>
<th>225</th>
</tr>
<tr class="header">
<th>32</th>
<th>139</th>
<th>189</th>
</tr>
<tr class="odd">
<th>48</th>
<th>131</th>
<th>161</th>
</tr>
<tr class="header">
<th>96</th>
<th>92</th>
<th>91</th>
</tr>
</thead>
<tbody>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 17%" />
<col style="width: 20%" />
<col style="width: 19%" />
</colgroup>
<thead>
<tr class="header">
<th colspan="5"><strong><h4 id="table-13">TABLE 13: A comparison of average hours of audio recorded by SMMs and AudioMoths at every available sample rate setting</strong></h4></th>
</tr>
<tr class="odd">
<th><strong>Sample Rate (kHz)</strong></th>
<th><p><u>Average Hours of Audio for SMM</u></p>
<th><p><u>Average Hours of Audio for AudioMoth</u></p>
</tr>
<tr class="header">
<th>8</th>
<th>223</th>
<th>249</th>
</tr>
<tr class="odd">
<th>16</th>
<th>164</th>
<th>225</th>
</tr>
<tr class="header">
<th>22.05</th>
<th>152</th>
<th>-</th>
</tr>
<tr class="odd">
<th>24</th>
<th>165</th>
<th>-</th>
</tr>
<tr class="header">
<th>32</th>
<th>139</th>
<th>189</th>
</tr>
<tr class="odd">
<th>44.1</th>
<th>127</th>
<th>-</th>
</tr>
<tr class="header">
  <th>48</th>
<th>131</th>
<th>161</th>
</tr>
<tr class="odd">
<th>96</th>
<th>92</th>
<th>91</th>
</tr>
<tr class="header">
  <th>192</th>
  <th>-</th>
  <th>60</th>
  </tr>
  <tr class="odd">
    <th>250</th>
    <th>-</th>
    <th>47</th>
  </tr>
  <tr class="header">
    <th>384</th>
    <th>-</th>
    <th>43</th>
</tr>
</thead>
<tbody>
</tbody>
</table>

> Consideration on the size of SD cards used should be given when
> AudioMoths are set to a sample rate of 96kHz or higher. The high
> sample rates filled the 64GB SD cards before the batteries died on all
> devices used. Table 7 shows the average amount of data stored before
> the batteries died during the sample rate trials. Cards with larger
> storage space should be used when recorded at the high sample rate
> settings. The Procell batteries used with SMMs set to 96kHz seem to
> die around the time the 64GB SD card fills up. A larger storage size
> should be used when recording at this sample rate.
>
> Temperature was expected to impact the batteries by decreasing
> performance as the temperature was decreased. The SMM Procell
> temperature trials did show a steady decline in the hours recorded as
> the temperature decreased, but this was not the case with the
> AudioMoth Procell trials. Table 13 compares the Procell and Lithium
> temperature trials for both SMMs and AudioMoths. The hours recorded by
> Procell AudioMoths only decreased by 3% when placed in the fridge
> versus the 10% seen in SMMs. This is surprising considering the
> AudioMoth has an exposed battery case, versus the sealed plastic case
> in SMMs. The devices saw similar performance when placed in the
> freezer with both recording about half the amount of time.

<table>
<colgroup>
<col style="width: 17%" />
<col style="width: 20%" />
<col style="width: 19%" />
<col style="width: 18%" />
<col style="width: 24%" />
</colgroup>
<thead>
<tr class="header">
<th colspan="5"><strong><h4 id="table-14">TABLE 14: A comparison of average hours of audio recorded by SMMs and AudioMoths at different temperature ranges using Procell or Lithium batteries</strong></h4></th>
</tr>
<tr class="odd">
<th><strong>Temperature</strong></th>
<th><p><u>Average Hours of Audio for SMM</u></p>
<th><p><u>Average Hours of Audio for AudioMoth</u></p>
<th><p><u>Average Hours of Audio for SMM/u></p>
<th><strong>Average Hours of Audio for AudioMoth</strong></th>
</tr>
<tr class="header">
<th></th>
<th>Procell</th>
<th>Batteries</th>
<th>Lithium</th>
<th>Batteries</th>
</tr>
<tr class="odd">
<th>Room (20.5°C)</th>
<th>139</th>
<th>189</th>
<th>167</th>
<th>234</th>
</tr>
<tr class="header">
<th>Fridge (3.4°C)</th>
<th>125</th>
<th>183</th>
<th>174</th>
<th>241</th>
</tr>
<tr class="odd">
<th>Freezer (-16.1°C)</th>
<th>80</th>
<th>102</th>
<th>177</th>
<th>238</th>
</tr>
</thead>
<tbody>
</tbody>
</table>

> Lithium batteries performed surprisingly well at all temperatures. The
> devices recorded approximately 25% more hours of audio at all
> temperatures compared to the control. Lithium batteries appeared to
> increase performance slightly as the temperature decreased. This
> result is unexpected; however, there was a consistent increase in the
> hours recorded during the SMM Lithium temperature trials. This may not
> always be the case since the AudioMoth Lithium temperature trials
> resulted in fewer hours recorded in the freezer compared to the
> fridge. The Lithium batteries did result in more hours recorded at
> both colder temperatures compared to the devices at room temperature.
> Additionally, using lithium batteries in freezing temperatures will
> double the hours of audio recorded over using Procell batteries.
>
> The cost of batteries is always a consideration for any budget. The
> Panasonic batteries were chosen as a potentially cheaper alternative
> to the Procells. The cost per battery was determined by looking at
> prices on Amazon, Grangier, and B&H during January 2023. The average
> cost for the batteries shown in Table 14 is without any organizational
> discount, sales tax, or shipping cost. The Panasonic batteries are a
> slightly cheaper option, but the reduced cost also results in a
> reduction in hours of audio recorded.
>
> Lithium batteries will result in more audio recorded, but the cost is
> four times as much as the Procell batteries. At best, the Lithium
> batteries more than double the hours recorded at freezing temperature.
> Lithium batteries may not be a cost-effective option, especially for
> large deployments. However, small deployments in isolated areas during
> cold seasons could greatly benefit from using Lithium batteries.

| **<u>TABLE 15</u>: A comparison of average cost per battery type used (as of January 2023) and the percent difference in hours of audio recorded using each battery type at various temperature ranges.** |                            |                                                |                                                                    |        |         |                                                                          |        |         |
|----------|---------|-------------|-------|-------|--------|-------|--------|--------|
| **Battery Type**                                                                                                                                                                                          | Cost per battery (dollars) | Percent difference in cost compared to Procell | Percent difference of hours recorded compared to SMM using Procell |        |         | Percent difference of hours recorded compared to AudioMoth using Procell |        |         |
|                                                                                                                                                                                                           |                            |                                                | room                                                               | fridge | freezer | room                                                                     | fridge | freezer |
| Procell                                                                                                                                                                                                   | 0.63                       | –                                              | –                                                                  |        |         | –                                                                        |        |         |
| Panasonic                                                                                                                                                                                                 | 0.58                       | -8%                                            | -10%                                                               | –      |         | -7%                                                                      | –      |         |
| Lithium                                                                                                                                                                                                   | 2.67                       | +423%                                          | +20%                                                               | +39%   | +122%   | +24%                                                                     | +31%   | +132%   |
