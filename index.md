---
layout: default
---
{::options parse_block_html="true" /}

<div id="compact-toc">
* TOC
{:toc}
</div>

<table class="full-width">
  <tr>
    <th>Android version</th>
    <th>API/SDK Level</th>
    <th><a href="https://developer.android.com/reference/kotlin/android/os/Build.VERSION_CODES">Version Code</a></th>
    <th>Codename</th>
    <th>Year</th>
  </tr>
  <tr>
    <td><b>Android 12 <sup class="beta">BETA</sup></b></td>
    <td>Level 31</td>
    <td><code>S</code></td>
    <td>?</td>
    <td>2021</td>
  </tr>
  <tr>
    <td><b>Android 11</b></td>
    <td>Level 30</td>
    <td><code>R</code></td>
    <td>Android11</td>
    <td>2020</td>
  </tr>
  <tr>
    <td><b>Android 10</b></td>
    <td>Level 29</td>
    <td><code>Q</code></td>
    <td>Android10</td>
    <td>2019</td>
  </tr>
  <tr>
    <td><b>Android 9</b></td>
    <td>Level 28</td>
    <td><code>P</code></td>
    <td>Pie</td>
    <td>2018</td>
  </tr>
  <tr>
    <td rowspan="2"><b>Android 8</b></td>
    <td>Level 27 <span class="subversion">Android 8.1</span></td>
    <td><code>O_MR1</code></td>
    <td rowspan="2">Oreo</td>
    <td rowspan="2">2017</td>
  </tr>
  <tr>
    <td>Level 26 <span class="subversion">Android 8.0</span></td>
    <td><code>O</code></td>
  </tr>
  <tr>
    <td rowspan="2"><b>Android 7</b></td>
    <td>Level 25 <span class="subversion">Android 7.1</span></td>
    <td><code>N_MR1</code></td>
    <td rowspan="2">Nougat</td>
    <td rowspan="2">2016</td>
  </tr>
  <tr>
    <td>Level 24 <span class="subversion">Android 7.0</span></td>
    <td><code>N</code></td>
  </tr>
  <tr>
    <td><b>Android 6</b></td>
    <td>Level 23</td>
    <td><code>M</code></td>
    <td>Marshmallow</td>
    <td>2015</td>
  </tr>
  <tr>
    <td rowspan="2"><b>Android 5</b></td>
    <td>Level 22 <span class="subversion">Android 5.1</span></td>
    <td><code>LOLLIPOP_MR1</code></td>
    <td rowspan="2">Lollipop</td>
    <td>2015</td>
  </tr>
  <tr>
    <td>Level 21 <span class="subversion">Android 5.0</span></td>
    <td><code>LOLLIPOP</code>, <code>L</code></td>
    <td>2014</td>
  </tr>
  <tr>
    <td rowspan="6"><b>Android 4</b></td>
    <td>Level 19 <sup>1</sup> <span class="subversion">Android 4.4</span></td>
    <td><code>KITKAT</code></td>
    <td>KitKat</td>
    <td rowspan="2">2013</td>
  </tr>
  <tr>
    <td>Level 18 <span class="subversion">Android 4.3</span></td>
    <td rowspan="3"><code>JELLYBEAN</code></td>
    <td rowspan="3">Jelly Bean</td>
  </tr>
  <tr>
    <td>Level 17 <span class="subversion">Android 4.2</span></td>
    <td rowspan="2">2012</td>
  </tr>
  <tr>
    <td>Level 16 <span class="subversion">Android 4.1</span></td>
  </tr>
  <tr>
    <td>Level 15 <span class="subversion">4.0.3 – 4.0.4</span></td>
    <td><code>ICE_CREAM_SANDWICH_MR1</code></td>
    <td rowspan="2">Ice Cream Sandwich</td>
    <td rowspan="2">2011</td>
  </tr>
  <tr>
    <td>Level 14 <span class="subversion">4.0.1 – 4.0.2</span></td>
    <td><code>ICE_CREAM_SANDWICH</code></td>
  </tr>
</table>

### Notes

<p><sup>1</sup> API Level 20 is missing from the table because it matches Android 4.4W, the version that makes Android available for Android Wear.</p>

## Definitions

### SDKs

* **`minSdk`**: The minimum SDK version your app will support. For example, if your `minSdk` is 26, this SDK version corresponse to API Level 26 and Android 8, so your app will only run on devices with Android 8 or higher.
* **`targetSdk`**: The SDK version that your app targets. This should always be the same as `compileSdk`.
* **`compileSdk`**: The SDK version that your app compiles against. Android Studio uses this SDK version to build your AABs and APKs. This should always be the same as `targetSdk`.

## See also

* [Build.VERSION_CODES](https://developer.android.com/reference/android/os/Build.VERSION_CODES)
* [Codenames, Tags, and Build Numbers](https://source.android.com/setup/start/build-numbers)