# DIFFSINGER LIEE : Immortal Idol 'Lilia' (LIEE REY)
<i> Diffsinger database and training material by julieraptor</i>

*If you post anything please tag as **`#LIEEREY`** and refer to the VB as **`LIEE : Immortal Idol`** or **`LIEE`**. 
<br>**OPTIONAL:** Tag **`@ChulieChu`** in your posts.*

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

https://github.com/user-attachments/assets/b9298096-8685-4e27-89cb-955412107908
<p align="center">
<i>Diffsinger LIEE : Immortal Idol 'Lilia' (August 2024)</i>
</p>

## 【 PUBLISHING GUIDELINES 】

*If you post anything please tag as **`#LIEEREY`** and refer to the VB as **`LIEE : Immortal Idol`** or **`LIEE`**. 
<br>**OPTIONAL:** Tag **`@ChulieChu`** in your posts.*

Please the default image **`LIEE_immortalIdol_Default.png`** OR **`LIEE_immortalIdol_Alt01.png`** located in the `art/fullbody` folder. 

## 【 USAGE GUIDE 】

A usage guide can be found in the wiki, located here: [[link]](https://github.com/julieraptor/DIFFSINGER-LIEE-Immortal-Idol/wiki).

## 【 VOICE MODEL INFORMATION 】

- **Voice Model Name:** LIEE : Immortal Idol 'Lilia'
- **Voice provider:** julieraptor
- **Illustration/Character Design:** julieraptor\*
- **Version:** DiffSinger v2.3 MM
- **Developer:** PixPrucer
- **Special Thanks:** _lin_lin, Alice, UtaUtaUtau, haru0l

**\*Additional art and designs along with credits are located in the "art" folder.**

### LIEE : Immortal Idol 'Lilia' is currently being privately distributed for testing purposes. 
Contact julieraptor if you would like to test!

*Unlike LIEE : Immortal Idol's previous release (Proof of Concept 1), LIEE : Immortal Idol 'Lilia' does not have Vocal Modes. 
<br>Instead, please use the TENSION capabilities to achieve expressiveness.*

## 【 CHARACTER INFORMATION 】

- **Character name:** LIEE (Veli Eden/Velirio Eden Nasaranta)
- **Character Title:** Immortal Idol 
- **Other names:** LIEE REY, Veli, Lili, Rio
- **Age:** 22+, 25 (at death), 27 (in the events of artificial eden)
- **Gender:** Nonbinary, Genderfluid (publicly, Female)
- **Pronouns:** they/them, she/her, he/him (in order of preference)
- **Ethnicity:** Filipino
- **Height:** 6'2 (1'88m)
- **Hair color:** Dark blue, Rainbow audio-spectrum highlights (can change color depending on mood)
- **Eye color:** Blue with orange/yellow accent, light yellow pupil (changes shape depending on mood)
- **Special Thanks:** Lucius, MintyAlieny, Ann

>LIEE is a singer from the future where idols can use cybernetic augmentations and the help of artificial intelligence to keep making music beyond human limits.<p>After an incident that landed them in the hospital, the death of LIEE was kept a secret. 
An android that supposedly retains the memories and personality of LIEE, codenamed REY, was created to fool their fans into believing they are still alive... including REY themselves.

Character art references can be found in the `art` folder.

## 【 FEATURES 】
### LIEE : Immortal Idol 'Lilia'
- **Supported range:** D2 ~ D6
- **Supported languages:** Technically, any language is capable of being supported. See the chart below to see what 
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

Special thanks for the assistance with multi-language. PixPrucer (Polish), Jani Tran (Vietnamese), Melody (Chinese), naff_san (Korean), MintyAlient (PT-EU), padrauwn, HAI-D (PT-BR)

**Supported parameters**
>`TENC (Tension) | VELC (Pronunciation speed) | GENC (Throat length)`

**Supported phonemizers**
>`DIFFS | DIFFS EN | DIFFS PL | DIFFS KR | DIFFS JA | DIFFS VI | DIFFS ES | DIFFS PT | DIFFS FIL | DIFFS ZH`
- You're free to modify the "dsdict" files under "dsdur" folder to your liking.

### Proof of Concept 1 - 0.0.4 (3) (November 2023)

- **Recording Languages:** Japanese, English, Korean, Chinese, Tagalog, Latin, Spanish
- **Labels:** 7931
- **Dataset Length:** ~50 min
- **Vocal Modes:** 7 (Standard, Bone, Breath, Heart, Mouth, Lung, Teeth)

```Note that the Proof of Concept 1 distribution only has 5 vocal modes: Standard, Bone, Heart, Lung, and Teeth```

- Alice, Haru0l, PixPrucer, Airi, UtaUtaUtau, Mlo7, tigermeat (database preparation)

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

### Notes
- "Voicebank" states the entire content of this folder/repository. 
- "Model(s)" stands for the file(s) containing exported neural network weights in ONNX format.

### Attribution
- When publishing work using this database, you are required to state the name of this database.
- It is necessary to state the name of this database's author.
- When attributing the name or author of this database, you must write the names exactly as written above. 
- You cannot call the database by any other name, nor can you attribute the database to any other author.

### Usage Content

 - You are free to create sexual content. 
 - You are free to create violent content. 
 - Do not create political content.
 - Do not create religious content.

**The following types of content are unconditionally prohibited:**
 - Criminal or illegal content 
 - Explicit underage sexual content 
 - Bigotry and hateful content
 
**YOU MUST NOT USE THIS VOICE MODEL TO IMPERSONATE THE VOICE PROVIDER AND/OR CAUSE HARM TO THEM OR OTHERS IN ANY WAY.**

### Character and Artwork
- "Character" stands for the visual character design and standing illustration(s) accompanying the voicebank's files.
- Published work using the database may or may not include visual depictions of the database character.
- Artwork does not need to depict the database character. This database can be used in conjunction with artwork of other characters.
- Existing artwork of the database character cannot be used without prior permission from the individual artists.
- Derivatives and heavily-inspired characters are prohibited. (Inspired designs must be credited to julieraptor.)

### Commercial Use
- Contact the author for individual approval to use this database commercially.
- The training data used for the database cannot be sold or used for commercial purposes.
- You cannot sell a database that has used Diffsinger LIEE : Immortal Idol as a multispeaker source.
- Contact the author about selling a database that has used LIEE's training data for inferencing using an SVC. (This does not include free multi-user vocoders and datasets where the author has consented to contribute data)

### Editing
- You are free to edit the audio files output from this database.
- You must not use audio outputs to create a new database or singing synthesizer.
- You must ask permission to use the model's output audio as an input for further language coverage. *EXAMPLE: Please ask for permission to use LIEE's output audio to use for Singing Voice Conversion (SVC) which will be used for extending LIEE's or other voice synthesis database's language capabilities.*
- You cannot use this database in any other singing synthesizer. Please contact the author if you would like to port this database to another singing synthesizer program.
- Usage of the model's output audio for other Singing Voice algorithm or software, signal converter, automated voice service, sample pack or similar, is prohibited. This does not include using the model's output audio as a driving / reference input audio for inferencing SVC algorithms.

### Redistribution

- Do not redistribute any part of this database. Link to this page to show where to download Diffsinger LIEE : Immortal Idol.
- You are free to share rendered singing vocals created with this database.
- Copy, recycle, or redistribution of any parts of this voicebank in any form is prohibited.
- You are allowed to use **LIEE : Immortal Idol Proof of Concept** models for pretraining.
- If you used **LIEE : Immortal Idol Proof of Concept** models for pre-training, **please indicate that you used Diffsinger LIEE : Immortal Idol for pre-training** wherever you post samples of your database.
- You can use **LIEE : Immortal Idol Proof of Concept** as a multispeaker source for a Diffsinger database.
- Do not release a model for pre-training other models if it has already been pre-trained with LIEE.
- Do not release a model pre-trained with LIEE that is intended to recreate the voice of a celebrity, paid vocal synthesis voice, copyrighted fictional character, or otherwise public figure.
(Showcasing inferenced examples is OK.) Be sure to indicate you pre-trained with LIEE, and link to this GitHub page.
- Absolutely DO NOT sell models when you used LIEE for pre-training.
- If sharing a database of an existing vocal synthesis character that is distributed for free (e.g. Kasane Teto of UTAU, etc), please indicate that you used LIEE for pre-train in the credits, and link to this GitHub page.

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

**Developer**
 - **Twitter:** [@PixPrucer](https://twitter.com/PixPrucer)
 - **Discord:** PixPrucer
 - **Email:** [pixproduceer@gmail.com](mailto:pixproduceer@gmail.com)
