## 

## Demo of Speaing-to-Singing Conversion

**Introduction**:

Source speaking is the speaking file that wants to convert.

Target singing is the template singing file, which the speaker is different then the source speaker.

Source singing reference is the actural singing from source speaker, but the file is not used in conversion stage, just for reference. 





### Overall Result

#### 13 MFCC

| Song number | Mel Distortion | PESQ | WORLD Boundary Error |
| :---------: | -------------- | ---- | -------------------- |
|     01      | 20.34          | 1.05 | 1.58s                |
|     02      | 17.42          | 2.88 | *                    |
|     04      | 24.01          | 1.04 | *                    |
|     07      | 15.32          | 1.05 | *                    |
|     10      |                |      | *                    |
|     13      | 15.30          | 1.15 | *                    |
|     14      | 17.41          | 1.04 | *                    |
|   Overall   |                |      | *                    |



#### 39 MFCC

| Song number | Mel Distortion | PESQ | WORLD Boundary Error |
| :---------: | -------------- | ---- | -------------------- |
|     01      | 20.34          | 1.05 | 2.05s                |
|     02      | 18.56          | 1.49 | *                    |
|     04      | 23.93          | 1.19 | *                    |
|     07      | 15.71          | 1.04 | *                    |
|     10      |                |      | *                    |
|     13      | 23.05          | 2.14 | *                    |
|     14      | 17.36          | 1.04 | *                    |
|   Overall   |                |      | *                    |







#### Dual Alignment

| Song number | Mel Distortion | PESQ | WORLD Boundary Error |
| :---------: | -------------- | ---- | -------------------- |
|     01      | 20.62          | 1.05 | *                    |
|     02      | 18.80          | 1.49 | *                    |
|     04      | 22.53          | 1.19 | *                    |
|     07      | 16.07          | 1.04 | *                    |
|     10      |                |      | *                    |
|     13      | 15.97          | 2.14 | *                    |
|     14      | 17.96          | 1.04 | *                    |
|   Overall   |                |      | *                    |





### 02 Do Re Mi

-------------------------------

**Source Speaking**:

<audio id="audio" controls="" preload="none">
  <source id="wav" src="original/02MPURspeaking.wav">
</audio>

**Target Singing**:

<audio id="audio" controls="" preload="none">
  <source id="wav" src="original/02ZHIYsinging.wav">
</audio>

**Source Singing Reference**:

<audio id="audio" controls="" preload="none">
  <source id="wav" src="original/02MPURsinging.wav">
</audio>





**Conversion Result**:

- 13mfcc

  <audio id="audio" controls="" preload="none">
    <source id="wav" src="02_MPURtoZHIY_10ms_13mfcc.wav">
  </audio>

- 39mfcc

  <audio id="audio" controls="" preload="none">
    <source id="wav" src="02_MPURtoZHIY_39mfcc_10ms.wav">
  </audio>

- Dual Alignment

  <audio id="audio" controls="" preload="none">
    <source id="wav" src="02_MPURtoZHIY_10ms_dual.wav">
  </audio>

- Using mfcc+linear prediction Cepstral analysis

  <audio id="audio" controls="" preload="none">
    <source id="wav" src="convert/02_MPURtoZHIY_LTS2.wav">
  </audio>

- Using MFCC + World spectrum Cepstral analysis

  <audio id="audio" controls="" preload="none">
    <source id="wav" src="convert/02_MPURtoZHIY_wcs_10ms.wav">
  </audio>

- Using MFCC + World spectrum Cepstral analysis + linear prediction Cepstral analysis

  <audio id="audio" controls="" preload="none">
    <source id="wav" src="convert/02_MPURtoZHIY_ttt_nonc2_10ms.wav">
  </audio>







### 01 Edelweiss

-------------------------------

**Source Speaking**:

<audio id="audio" controls="" preload="none">
  <source id="wav" src="original/01ADIZspeaking.wav">
</audio>

**Target Singing**:

<audio id="audio" controls="" preload="none">
  <source id="wav" src="original/01SAMFsinging.wav">
</audio>

**Source Singing Reference**:

<audio id="audio" controls="" preload="none">
  <source id="wav" src="original/01ADIZsinging.wav">
</audio>



**Conversion Result**:

- 13mfcc

  <audio id="audio" controls="" preload="none">
    <source id="wav" src="01_ADIZtoSAMF_13mfcc_10ms.wav">
  </audio>

- 39mfcc

  <audio id="audio" controls="" preload="none">
    <source id="wav" src="01_ADIZtoSAMF_39mfcc_10ms.wav">
  </audio>

- Dual Alignment

  <audio id="audio" controls="" preload="none">
    <source id="wav" src="01_ADIZtoSAMF_10ms_dual.wav">
  </audio>





### 04 Silent Night

-------------------------------



**Source Speaking**:

<audio id="audio" controls="" preload="none">
  <source id="wav" src="original/04MCURspeaking.wav">
</audio>

**Target Singing**:

<audio id="audio" controls="" preload="none">
  <source id="wav" src="original/04KENNsinging.wav">
</audio>

**Source Singing Reference**:

<audio id="audio" controls="" preload="none">
  <source id="wav" src="original/04MCURsinging.wav">
</audio>





**Conversion Result**:

- 13mfcc

  <audio id="audio" controls="" preload="none">
    <source id="wav" src="04_MCURtoKENN_10ms_13mfcc.wav">
  </audio>

- 39mfcc

  <audio id="audio" controls="" preload="none">
    <source id="wav" src="04_MCURtoKENN_10ms_39mfcc.wav">
  </audio>

- Dual Alignment

  <audio id="audio" controls="" preload="none">
    <source id="wav" src="04_MCURtoKENN__10ms_dual.wav">
  </audio>







### 07 Rhythm of the Rain

-------------------------------

**Source Speaking**:

<audio id="audio" controls="" preload="none">
  <source id="wav" src="original/07JTANspeaking.wav">
</audio>

**Target Singing**:

<audio id="audio" controls="" preload="none">
  <source id="wav" src="original/07NJATsinging.wav">
</audio>

**Source Singing Reference**:

<audio id="audio" controls="" preload="none">
  <source id="wav" src="original/07JTANsinging.wav">
</audio>





**Conversion Result**:

- 13mfcc

  <audio id="audio" controls="" preload="none">
    <source id="wav" src="07_JTANtoNJAT_10ms_13mfcc.wav">
  </audio>

- 39mfcc

  <audio id="audio" controls="" preload="none">
    <source id="wav" src="07_JTANtoNJAT_10ms_39mfcc.wav">
  </audio>

- Dual Alignment

  <audio id="audio" controls="" preload="none">
    <source id="wav" src="07_JTANtoNJAT_10ms_dual.wav">
  </audio>







### 10 Twinkle Twinkle Little Star

-------------------------------

**Source Speaking**:

<audio id="audio" controls="" preload="none">
  <source id="wav" src="original/10KENNspeaking.wav">
</audio>

**Target Singing**:

<audio id="audio" controls="" preload="none">
  <source id="wav" src="original/10MCURsinging.wav">
</audio>

**Source Singing Reference**:

<audio id="audio" controls="" preload="none">
  <source id="wav" src="original/10KENNsinging.wav">
</audio>





**Conversion Result**:

- 13mfcc

  <audio id="audio" controls="" preload="none">
    <source id="wav" src="10_KENNtoMCUR_13mfcc_10ms.wav">
  </audio>

- 39mfcc

  <audio id="audio" controls="" preload="none">
    <source id="wav" src="10_KENNtoMCUR_39mfcc_10ms.wav">
  </audio>

- Dual Alignment

  <audio id="audio" controls="" preload="none">
    <source id="wav" src="10_KENNtoMCUR_10ms_dual.wav">
  </audio>





### 13 Proud of You

-------------------------------

**Source Speaking**:

<audio id="audio" controls="" preload="none">
  <source id="wav" src="original/13SAMFspeaking.wav">
</audio>

**Target Singing**:

<audio id="audio" controls="" preload="none">
  <source id="wav" src="original/13ADIZsinging.wav">
</audio>

**Source Singing Reference**:

<audio id="audio" controls="" preload="none">
  <source id="wav" src="original/13SAMFsinging.wav">
</audio>





**Conversion Result**:

- 13mfcc

  <audio id="audio" controls="" preload="none">
    <source id="wav" src="13_SAMFtoADIZ_10ms_13mfcc.wav">
  </audio>

- 39mfcc

  <audio id="audio" controls="" preload="none">
    <source id="wav" src="13_SAMFtoADIZ_10ms_39mfcc.wav">
  </audio>

- Dual Alignment

  <audio id="audio" controls="" preload="none">
    <source id="wav" src="13_SAMFtoADIZ_10ms_dual.wav">
  </audio>







### 14 Lemon Tree

-------------------------------

**Source Speaking**:

<audio id="audio" controls="" preload="none">
  <source id="wav" src="original/14MPURspeaking.wav">
</audio>

**Target Singing**:

<audio id="audio" controls="" preload="none">
  <source id="wav" src="original/14ZHIYsinging.wav">
</audio>

**Source Singing Reference**:

<audio id="audio" controls="" preload="none">
  <source id="wav" src="original/14MPURsinging.wav">
</audio>





**Conversion Result**:

- 13mfcc

  <audio id="audio" controls="" preload="none">
    <source id="wav" src="14_MPURtoZHIY_10ms_13mfcc.wav">
  </audio>

- 39mfcc

  <audio id="audio" controls="" preload="none">
    <source id="wav" src="14_MPURtoZHIY_10ms_39mfcc.wav">
  </audio>

- Dual Alignment

  <audio id="audio" controls="" preload="none">
    <source id="wav" src="14_MPURtoZHIY_10ms_dual.wav">
  </audio>

