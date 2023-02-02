# [ARU Battery Longevity Report](https://github.com/kitzeslab/ARU_battery_longevity/blob/main/report.md)
This report summarizes efforts to determine the lifespan of batteries used in Song Meter Micro and AudioMoth ARU at various settings and conditions. Trials to compare changes in sample rate, gain, temperature, and battery type were conducted. Each category had three units at the same setting and were exposed to the same conditions. Every available sample rate and gain setting was tested as well as the effect that cold and freezing temperatures have on the ARUs

A summary of the report can be found below alongside tables that summarize the results of the sample rate and temperature trials. The full report can be accessed [here](https://github.com/kitzeslab/ARU_battery_longevity/blob/main/report.md)

## **Summary**
The longevity of batteries used in [Song Meter
Micro (SMM)](https://www.wildlifeacoustics.com/products/song-meter-micro?utm_term=song%20meter%20micro&utm_campaign=Products:+Bird/Frog+Recorders&utm_source=adwords&utm_medium=ppc&hsa_acc=6925807588&hsa_cam=12918503750&hsa_grp=121883524219&hsa_ad=518495938292&hsa_src=g&hsa_tgt=kwd-1247239655478&hsa_kw=song%20meter%20micro&hsa_mt=e&hsa_net=adwords&hsa_ver=3&gclid=Cj0KCQiA2-2eBhClARIsAGLQ2RmAb11m9IysIbTFi5NTzrYldq44dilGNIvpfhyiTj2Rn0vT5Kqc6qsaAuVyEALw_wcB) and [AudioMoth](https://www.openacousticdevices.info/) Autonomous Recording Units (ARUs) was evaluated at varying
settings of sample rate, gain, temperature, and battery type. The
control settings used for SMMs included a 32kHz sample rate with 18dB
gain using [Duracell Procell PC1500 AA batteries (Procell)](https://www.procell.com/en-us/all-batteries/) to record at
room temperature which recorded an average of 139 hours of audio. The
lowest sample rate setting of 8kHz would increase the hours of audio by
61% and the highest sample rate setting of 96kHz would decrease the
hours of audio by 34%. A sample rate of 96kHz caused the 64GB SD card to
fill up before the batteries died; however, the batteries would die once
the device was rebooted with a new SD card. The change of gain had a
negligible effect on hours of audio recorded. Performance of the Procell
batteries decreased by 10% at cold temperatures and by 43% at freezing
temperatures. [Energizer Ultimate Lithium AA (Lithium)](https://www.energizer.com/batteries/energizer-ultimate-lithium-batteries) batteries
increased hours of audio recorded by 24% and performed at relatively
consistent levels across room, cold, and freezing temperatures. Lithium
batteries double the hours of audio recorded at freezing temperatures
compared to Procell batteries at the same temperature. [Panasonic
Alkaline Power Plus AA (Panasonic)](https://www.panasonicbatteryproducts.com/alkaline_plus_power_batteries/) batteries were only tested at room
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

<table>
<colgroup>
<col style="width: 17%" />
<col style="width: 20%" />
<col style="width: 19%" />
</colgroup>
<thead>
<tr class="header">
<th colspan="3"><strong><h4 id="table-13"> A comparison of average hours of audio recorded at room temperature by SMMs and AudioMoths at every available sample rate setting using Procell batteries</strong></h4></th>
</tr>
<tr class="odd">
<th><p>Sample Rate (kHz)</p></th>
<th><p>Average Hours of Audio for SMM</p></th>
<th><p>Average Hours of Audio for AudioMoth</p></th>
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

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 19%" />
<col style="width: 18%" />
<col style="width: 24%" />
</colgroup>
<thead>
<tr class="header">
<th colspan="5"><strong><h4> A comparison of average hours of audio recorded by SMMs and AudioMoths with a 32kHz sample rate at different temperature ranges using Procell or Lithium batteries</strong></h4></th>
</tr>
<tr class="odd">
  <th rowspan="2"><strong>Temperature</strong></th>
<th><p>Average Hours of Audio for SMM</p>
<th><p>Average Hours of Audio for AudioMoth</p>
<th><p>Average Hours of Audio for SMM</p>
<th><p>Average Hours of Audio for AudioMoth</p></th>
</tr>
<tr class="header">
  <th colspan="2">Procell Batteries</th>
  <th colspan="2">Lithium Batteries</th>
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
