# DIFFSINGER LIEE : Immortal Idol
<i> Diffsinger database and training material by julieraptor</i>

*If you post anything please tag as **`#理詠LIEE`** and refer to the VB as **`LIEE : Immortal Idol`** or **`LIEE`**. 
<br>**OPTIONAL:** Tag **`@LIEE_Official`** in your posts.*

**Original music tag:** #理詠Song </p>
**Fanart tag:** #理詠Art

Please the default image **`LIEE_immortalIdol_Default.png`** OR **`LIEE_immortalIdol_Alt01.png`** located in the `art/fullbody` folder. 

If you used any part of this database for training, **please indicate that you used Diffsinger LIEE : Immortal Idol** wherever you post samples of your database.
<p>
To download, navigate to <b>Releases</b> on the right-hand side and choose the file you wish to download.


<p align="center">
<img src ="https://github.com/user-attachments/assets/f465488d-617f-4537-bd77-ee146b877b48" height="600" />
 
<br>
<i>Diffsinger LIEE : Immortal Idol Official Art by julieraptor</i>
</p>


# 【SAMPLE】 

<p align="center">
Listen here: https://www.youtube.com/watch?v=_afW-RWnpvA<br>
<i>Diffsinger LIEE : Immortal Idol 'Lilia' (MM 2.8, August 2025)</i>
</p>

## 【 PUBLISHING GUIDELINES 】

*If you post anything please tag as **`#理詠LIEE`** and refer to the VB as **`LIEE : Immortal Idol`** or **`LIEE`**. 
<br>**OPTIONAL:** Tag **`@LIEE_Official`** in your posts.*

Please the default image **`LIEE_immortalIdol_Default.png`** OR **`LIEE_immortalIdol_Alt01.png`** located in the `art/fullbody` folder. 

## 【 USAGE GUIDE 】

A usage guide can be found in the wiki, located here: [[link]](https://github.com/julieraptor/DIFFSINGER-LIEE-Immortal-Idol/wiki).

## 【 VOICE MODEL INFORMATION 】

To be announced.

## 【 CHARACTER INFORMATION 】

- **Character name:** LIEE (Veli Eden/Velirio Eden Nasaranta)
- **Character Title:** Immortal Idol 
- **Other names:** LIEE REY, Veli, Lili, Rio
- **Age:** 22, permanently
- **Gender:** Nonbinary, Genderfluid (publicly, Female)
- **Pronouns:** they/them, she/her, he/him (in order of preference)
- **Ethnicity:** Filipino
- **Height:** 6'2 (1'88m)
- **Hair color:** Dark blue, Rainbow audio-spectrum highlights (can change color depending on mood)
- **Eye color:** Blue with orange/yellow accent, light yellow pupil (changes shape depending on mood)

>A robot who contains the memories of a futuristic pop idol.

Because of their new body, LIEE tends to feel disconnected from human experiences and feelings and desires to learn them again through singing.

Character art references can be found in the `art` folder.

## 【 FEATURES 】
### LIEE : Immortal Idol 'Lilikha'

To be announced.

### LIEE : Immortal Idol 'Lilia'

- **Voice Model Name:** LIEE : Immortal Idol 'Lilia' - JUBILIEE 2025
- **Voice provider:** julieraptor
- **Illustration/Character Design:** julieraptor\*
- **Version:** DiffSinger v2.8 MM
- **Developer:** PixPrucer
- **Special Thanks:** _lin_lin, Alice, UtaUtaUtau, haru0l

**\*Additional art and designs along with credits are located in the "art" folder.**

*Unlike LIEE : Immortal Idol's previous release (Proof of Concept 1), LIEE : Immortal Idol 'Lilia' does not have Vocal Modes. 
<br>Instead, please use the TENSION capabilities to achieve expressiveness.*

- **Supported range:** D2 ~ D6
- **Supported languages:** Technically, any language is capable of being supported. See the chart below.
- **Optimal range:** C3 ~ G5 (alto)
- **Optimal languages/Languages recorded in:** Japanese, English, Korean, Latin, Tagalog, Cebuano, Spanish, Chinese
- `LIEE : Immortal Idol 'Lilia'` supports autopitch tuning.

| Supported Languages via Phonemizer | Planned Future Support |
| --- | --- |
| English | Cantonese Chinese |
| Japanese | German |
| Polish | Thai |
| Mandarin Chinese | Italian |
| Spanish | More TBA |
| French | - |
| Tagalog* | - |
| Portuguese (EU/BR) | -
| Korean | -

Special thanks for the assistance with multi-language. PixPrucer (Polish), Jani Tran (Vietnamese), Melody (Chinese), naff_san (Korean), MintyAlient (PT-EU), padrauwn, HAI-D (PT-BR)

**Supported parameters**
>`TENC (Tension) | VELC (Pronunciation speed) | GENC (Throat length)`

**Supported phonemizers**
>`DIFFS | DIFFS EN | DIFFS PL | DIFFS KR | DIFFS JA | DIFFS VI | DIFFS ES | DIFFS PT | DIFFS FIL | DIFFS ZH`
- You're free to modify the "dsdict" files under "dsdur" folder to your liking.

**Contact the Developer**
 - **Twitter:** [@PixPrucer](https://twitter.com/PixPrucer)
 - **Discord:** PixPrucer
 - **Email:** [pixproduceer@gmail.com](mailto:pixproduceer@gmail.com)

### Proof of Concept 1 - 0.0.4 (3) (November 2023)

- **Voice Model Name:** LIEE : Immortal Idol
- **Voice provider:** julieraptor
- **Illustration/Character Design:** julieraptor\*
- **Version:** Proof of Concept 1
- **Developer:** julieraptor
- **Special Thanks:** Alice, Haru0l, PixPrucer, Airi, UtaUtaUtau, Mlo7, tigermeat (database preparation)

- **Recording Languages:** Japanese, English, Korean, Chinese, Tagalog, Latin, Spanish
- **Labels:** 7931
- **Dataset Length:** ~50 min
- **Vocal Modes:** 7 (Standard, Bone, Breath, Heart, Mouth, Lung, Teeth)

```Note that the Proof of Concept 1 distribution only has 5 vocal modes: Standard, Bone, Heart, Lung, and Teeth```

## 【 DEVELOPER'S NOTES 】
### LIEE : Immortal Idol 'Lilia'
- Variance trained using Reflow for 500k steps
- Acoustics trained using DDPM for 800k steps

- The model is very sensitive to pitch changes. To omit unusual behavior, ensure the tuning doesn't include many rapid or aggressive bends, especially on vowel beginnings (consonants are an exception here, those can be tuned steeply).
- **`[hh]`** phoneme also works as an endbreath/breathe out sound.
- **`[m]`** phoneme is also programmed to be a humming sound when used in isolation. It can be used in succession with [hh] to produce staccato: **``[m] [hh m]``**
- Although trained in specific contexts, phonemes can be freely mixed around to imitate other languages (by typing them space-separated in square brackets, ex. **`[t0 a dx a m]`**.
- The DIFFS EN phonemizer doesn't support **`[dx]`** or **`[ax]`** phonemes. Those have to be overridden by hand.

# 【 TERMS OF USE 】

[Please review the full Terms of Use here.](https://docs.google.com/document/d/1t13WKc7VA2Q3G_MppznbAwhl3vLIL2MNPyjVN3kWDDg/edit?usp=sharing)

### Disclaimer
- julieraptor holds no responsibility to any incidents, damage, or loss by the user from downloading or using the database or character.
- julieraptor holds no responsibility to any incidents, damage, or loss that occurs to any third party as a result of usage of the database or database character.
- The Voicer (julieraptor) or the Developer (PixPrucer) aren't responsible for any legal issues created from the use of this voicebank. The user handles such on their own.
- Upon breaking the Terms of Use, the User is required to cease all activities related to the voicebank and remove its files from all related platforms, along with the content or such that led to the breach.
- These terms of use were originally generated with and adapted from https://tools.tubs.wtf/vbtougen and may or may not include additional edits.


# 【CONTACT INFORMATION】
**Voice Provider**
- **Site:** [website](https://julieraptor.carrd.co)
- **YouTube:** [chulie_chu](https://www.youtube.com/channel/UCaJ0Q7aEmNdZAME8zvxQICg)
- - **Email:** [raptorjulie@gmail.com](mailto:raptorjulie@gmail.com)
