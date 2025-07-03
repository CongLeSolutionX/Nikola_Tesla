---
created: 2025-06-19 05:31:26
author: Cong Le
version: "1.0"
license(s): MIT, CC BY-SA 4.0
copyright: Copyright (c) 2025 Cong Le. All Rights Reserved.
source: https://tesla-museum.org/wp-content/uploads/2023/05/lista_patenata_eng.pdf
---


> ⚠️🏗️🚧🦺🧱🪵🪨🪚🛠️👷
> 
> This is a working draft in progress
> 
> ![Loading...](https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExZmRtY3NmMWZ0czl2cnQydjVmbHYzeWd2M2FiZXAyNmY3ejBzMGUzbiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/4gK3Z6gJqdcCVpK794/giphy.gif)
>
> gif image is provided by [Giphy](https://giphy.com)
> 
> ⚠️🏗️🚧🦺🧱🪵🪨🪚🛠️👷


----


# Nikola Tesla's Comprehensive Patents (both US and non-US) Timeline
<details open>
<summary>Click to show/hide the full disclaimer.</summary>

> <ins>📢 **Disclaimer** 🚨</ins>
>
> This project is born from my fascination with blending digital art and artificial intelligence.</br>
> It's where I document my academic explorations,</br>
> share my findings with anyone interested,</br>
> and maintain a personal vault of my creative and technical journey.</br>
> I'm not sure the link for this repo being shared in the back by others,</br>
> since I havent plan for any analytics for this project yet.</br>
> ...and I'm actively looking for a job...</br>

> This document contains my personal notes on the topic,</br>
> compiled from publicly available documentation and various cited sources.
> 
> The materials are intended for educational purposes (<ins>sometimes, entertainment purposes</ins>), personal study, and technical reference.
> The content is dual-licensed:
> 1. **MIT License:** Applies to all code implementations (Swift, Mermaid, and other programming languages).
> 2. **Creative Commons Attribution-ShareAlike 4.0 International License (CC BY-SA 4.0):** Applies to all non-code content, including text, explanations, diagrams, and illustrations.


</details>


----

**Important Considerations for this Chart:**

*   **Size:** This chart will be very long. Some Markdown renderers or platforms might struggle to display it perfectly or might be slow.
*   **Clarity:** To maintain some readability:
	*   Patents are sectioned by the decade in which they were granted.
	*   Titles are shortened to `First Few Words… (Country Code, Patent #)`. US patents will use `(USA, Patent #)`.
*   **Date Anomalies:** For non-US patents where the Grant Date was listed *before* the Filing Date, or if a date was missing, the Grant Date for visualization purposes has been set equal to the Filing Date. This makes the bar a point event or ensures non-negative duration. (Specific anomalies handled are listed in the thought process for the previous non-US timeline).
*   **Mermaid IDs:** Each patent has a unique ID (`p_us_X` for US patents, `p_int_X` for non-US patents, where X is its serial number from the respective lists).

----

Here is the combined timeline:

```mermaid
---
title: "Nikola Tesla's Comprehensive Patents (both US and non-US) Timeline"
author: "Cong Le"
version: "1.0"
license(s): "MIT, CC BY-SA 4.0"
copyright: "Copyright (c) 2025 Cong Le. All Rights Reserved."
config:
  layout: elk
  theme: base
---
%%%%%%%% Mermaid version v11.4.1-b.14
%%{
  init: {
	'fontFamily': 'Bradley Hand',
    'gantt': {
      'titleTopMargin': 25,
      'barHeight': 15,
      'barGap': 10,
      'topPadding': 65,
      'rightPadding': 10,
      'leftPadding': 200,
      'gridLineStartPadding': 25,
      'sectionFontSize': 15,
      'numberSectionStyles': 4,
      'axisFormat': '%Y',
      'topAxis': true,
      'weekday': 'sunday'
    },
    'themeVariables': {
      'primaryColor': '#C004',
      'primaryTextColor': '#F8B229',
      'primaryBorderColor': '#27AE60',
      'fontSize': '20px'
    }
  }
}%%
gantt
    dateFormat  YYYY-MM-DD
    title Comprehensive Nikola Tesla Patent Timeline 📜🌍🇺🇸
    axisFormat %Y

    section Patents Granted in the 1880s
    %% --- 1886 ---
    Commutator for Dynamo-Electric Machines (USA, 334,823)           :active, p_us_2, 1885-05-06, 1886-01-26
    Electric-Arc Lamp (USA, 335,786)                                 :active, p_us_1, 1885-03-30, 1886-02-09
    Electric-Arc Lamp (USA, 335,787)                                 :active, p_us_5, 1885-07-13, 1886-02-09
    Regulator for Dynamo-Electric Machines (USA, 336,961)            :active, p_us_3, 1885-05-18, 1886-03-02
    Regulator for Dynamo-Electric Machines (USA, 336,962)            :active, p_us_4, 1885-06-01, 1886-03-02
    Dynamo Electric Machines (CAN, 24033)                            :active, p_int_48, 1886-04-27, 1886-05-10
    Electric Arc Lamp (CAN, 24348)                                   :active, p_int_49, 1886-04-27, 1886-06-18
    Regulirvorrichtung Bogenlampen (DEU, 37781)                      :active, p_int_89, 1886-02-09, 1886-08-12
    Improvements in Electric Lamps (GBR, 1,877)                      :active, p_int_110, 1886-02-09, 1886-09-16
    Schaltung von dynamoelektrischen Maschinen (DEU, 37103)          :active, p_int_90, 1886-03-02, 1886-10-05
    Regulator for Dynamo-Electric Machines (USA, 350,954)            :active, p_us_7, 1886-01-14, 1886-10-19
    %% --- 1887 ---
    Improvements in Dynamo Electric Machines (GBR, 2,975)            :active, p_int_111, 1886-03-02, 1887-02-01
    Dynamo-Electric Machine (USA, 359,748)                           :active, p_us_6, 1886-01-14, 1887-03-22
    %% --- 1888 ---
    Electro-Magnetic Motor (USA, 381,968)                            :active, p_us_11, 1887-10-12, 1888-05-01
    Electrical Transmission of Power (USA, 382,280)                  :active, p_us_12, 1887-10-12, 1888-05-01
    Electro-Magnetic Motor (USA, 382,279)                            :active, p_us_13, 1887-11-30, 1888-05-01
    Electro-Magnetic Motor (USA, 381,969)                            :active, p_us_14, 1887-11-30, 1888-05-01
    Electrical Transmission of Power (USA, 382,281)                  :active, p_us_15, 1887-11-30, 1888-05-01
    System of Electrical Distribution (USA, 382,282)                 :active, p_us_16, 1887-12-23, 1888-05-01
    Method of Converting and Distributing... (USA, 381,970)          :active, p_us_17, 1887-12-23, 1888-05-01
    Commutator for Dynamo-Electric Machines (USA, 382,845)           :active, p_us_9, 1887-04-30, 1888-05-15
    Perfectionnements transmission force (BEL, 81636)                :active, p_int_19, 1888-05-01, 1888-05-15
    Perfectionnements procédés et appareils (BEL, 81637)             :active, p_int_20, 1888-05-01, 1888-05-15
    Improvements Electrical Transmission Power (GBR, 6,481)          :active, p_int_112, 1888-05-01, 1888-06-01
    Improvements Generation Distribution Currents (GBR, 6,502)       :active, p_int_113, 1888-05-01, 1888-06-01
    Perfezionamenti nei metodi ed apparati (ITA, 23400)              :active, p_int_147, 1888-06-09, 1888-06-30
    Perfezionamenti trasmissione elettrica (ITA, 23401)              :active, p_int_148, 1888-06-09, 1888-06-30
    Perfectionnements procédés et appareils (FRA, 190,332)           :active, p_int_59, 1888-05-01, 1888-07-05
    Perfectionnements transmission de la force (FRA, 190,333)        :active, p_int_60, 1888-05-01, 1888-07-05
    Method of and Apparatus for Electrical Transmission... (CAN, 29537) :active, p_int_50, 1888-05-01, 1888-07-17
    System of Electrical Distribution (USA, 390,413)                 :active, p_us_18, 1888-04-10, 1888-10-02
    Dynamo-Electric Machine (USA, 390,414)                           :active, p_us_19, 1888-04-23, 1888-10-02
    Dynamo-Electric Machine or Motor (USA, 390,415)                  :active, p_us_25, 1888-05-15, 1888-10-02
    Regulator for Alternate-Current Motors (USA, 390,820)            :active, p_us_20, 1888-04-24, 1888-10-09
    Dynamo-Electric Machine (USA, 390,721)                           :active, p_us_21, 1888-04-28, 1888-10-09
    Method of and Apparatus for Converting and Distributing... (CAN, 30172) :active, p_int_51, 1888-05-01, 1888-11-10
    %% --- 1889 ---
    Thermo-Magnetic Motor (USA, 396,121)                             :active, p_us_8, 1886-03-30, 1889-01-15
    An improvement in methods of, and apparatus for... (VIC, 6389)   :active, p_int_196, 1888-12-10, 1889-01-04
    Improvements in electrical transmission of power (VIC, 6390)     :active, p_int_197, 1888-12-10, 1889-01-04
    Neuerungen in der elektrischen Kraftübertragung (AUT, 39/1026)   :active, p_int_3, 1888-05-01, 1889-04-16
    Method of Electrical Power Transmission (USA, 401,520)           :active, p_us_31, 1889-03-14, 1889-04-16
    Neuerung in dem Verfahren und den Apparaten... (AUT, 39/1070)    :active, p_int_4, 1888-05-01, 1889-04-24
    Perfectionnements dans le mode de fonctionnement... (BEL, 85866) :active, p_int_21, 1889-04-16, 1889-04-30
    Improvements in electrical transmission of power (NSW, 1122)     :active, p_int_168, 1888-12-14, 1889-04-09
    An improvement in methods of, and apparatus for... (NSW, 1123)   :active, p_int_169, 1888-12-14, 1889-04-09
    Schaltung eines Transformators... (DEU, 47012)                   :active, p_int_91, 1888-04-30, 1889-05-10
    Improvements relating to Electro-motors (GBR, 6,527)             :active, p_int_114, 1889-04-16, 1889-05-18
    Perfectionnements du mode de fonctionnement... (FRA, 197,532)    :active, p_int_61, 1889-04-16, 1889-06-17
    Method of Operating Electro-Magnetic Motors (USA, 405,858)       :active, p_us_30, 1889-02-18, 1889-06-25
    Dynamo-Electric Machine (USA, 405,859)                           :active, p_us_32, 1889-03-23, 1889-06-25
    Electro-Magnetic Motor (USA, 406,968)                            :active, p_us_33, 1889-04-06, 1889-07-16
    Verbindung der Drahtspulen... (DEU, 47885)                       :active, p_int_92, 1888-04-30, 1889-07-17
    Method of Obtaining Direct from Alternating... (USA, 413,353)    :active, p_us_42, 1889-06-12, 1889-10-22
    Procédé de conversion des courants électriques... (ITA, 26334)   :active, p_int_149, 1889-09-11, 1889-10-31
    Perfectionnements dans les moteurs électro-... (BEL, 88701)      :active, p_int_23, 1889-10-03, 1889-10-16
    Perfectionnements á la construction... (BEL, 88702)              :active, p_int_24, 1889-10-03, 1889-10-16
    Procédé de conversion des courants électriques (BEL, 88156)      :active, p_int_22, 1889-10-22, 1889-11-15
    Electro-Magnetic Motor (USA, 416,191)                            :active, p_us_36, 1889-05-20, 1889-12-03
    Electro-Magnetic Motor (USA, 416,192)                            :active, p_us_37, 1889-05-20, 1889-12-03
    Electro-Magnetic Motor (USA, 416,193)                            :active, p_us_38, 1889-05-20, 1889-12-03
    Electro-Magnetic Motor (USA, 416,194)                            :active, p_us_40, 1889-05-20, 1889-12-03
    Electro-Magnetic Motor (USA, 416,195)                            :active, p_us_41, 1889-05-20, 1889-12-03
    Improvements relating to the Conversion of Alternating... (GBR, 16,709) :active, p_int_115, 1889-10-22, 1889-12-07
    Armature for Electric Machines (USA, 417,794)                    :active, p_us_43, 1889-06-28, 1889-12-24
    Electric Motor (USA, 418,248)                                    :active, p_us_39, 1889-05-20, 1889-12-31

    section Patents Granted in the 1890s
    %% --- 1890 ---
    Procédé de conversion des courants électriques... (FRA, 201,486) :active, p_int_62, 1889-10-22, 1890-01-03
    Improvements in Alternating Current Electro-magnetic... (GBR, 19,420) :active, p_int_116, 1889-12-03, 1890-01-11
    Improvements in Construction and Mode of Operating... (GBR, 19,426) :active, p_int_117, 1889-12-03, 1890-01-11
    Perfectionnements aux moteurs électro-magnétiques... (FRA, 202,372) :active, p_int_63, 1889-10-03, 1890-02-11
    Perfectionnements á la construction et au mode... (FRA, 202,373) :active, p_int_64, 1889-10-03, 1890-02-11
    Method of and Apparatus for Converting Alternating... (CAN, 33317) :active, p_int_52, 1889-12-19, 1890-02-01
    Electric Motor (USA, 424,036)                                    :active, p_us_39_variant, 1889-05-20, 1890-03-25
    Neuerungen an Wechselstrommotoren (AUT, 40/1043)                 :active, p_int_6, 1889-12-03, 1890-04-02
    Perfezionamenti nei motori dinamo-elettrici... (ITA, 26620)      :active, p_int_150, 1889-10-31, 1890-04-25
    Perfezionamenti nella construzione e funzionamento... (ITA, 26621) :active, p_int_151, 1889-10-31, 1890-04-25
    Alternating-Current Electro-Magnetic Motor (USA, 433,700)        :active, p_us_44, 1890-03-26, 1890-08-05
    Alternating-Current Motor (USA, 433,701)                         :active, p_us_45, 1890-03-26, 1890-08-05
    Electrical Transformer or Induction Device (USA, 433,702)        :active, p_us_46, 1890-03-26, 1890-08-05
    Electro-Magnetic Motor (USA, 433,703)                            :active, p_us_47, 1890-04-04, 1890-08-05
    Neuerungen in den Verfahrungsweisen, um... (AUT, 40/2564)        :active, p_int_5, 1889-10-22, 1890-09-24
    Neuerungen in der Konstruktion und im Betrieb... (AUT, 40/2645)  :active, p_int_7, 1889-12-03, 1890-09-27
    Pyromagneto-Electric Generator (USA, 428,057)                    :active, p_us_10, 1887-05-26, 1890-05-13
    Verfahren, Wechselströme in gleichrichtete... (DEU, 54797)       :active, p_int_93, 1889-10-21, 1890-12-20
    %% --- 1891 ---
    Electro-Magnetic Motor (USA, 445,207)                            :active, p_us_40_variant, 1889-05-20, 1891-01-27
    Method of Operating Arc Lamps (USA, 447,920)                     :active, p_us_48, 1890-10-01, 1891-03-10
    Alternating-Electric-Current Generator (USA, 447,921)            :active, p_us_49, 1890-11-15, 1891-03-10
    Procédé et appareil perfectionnés pour produire... (BEL, 94940)  :active, p_int_25, 1891-05-19, 1891-05-30
    Improved Methods of and Apparatus for Generating... (GBR, 8,575) :active, p_int_118, 1891-05-19, 1891-06-20
    System of Electric Lightning (USA, 454,622)                      :active, p_us_53, 1891-04-26, 1891-06-23
    Electro-Magnetic Motor (USA, 455,067)                            :active, p_us_50, 1891-01-27, 1891-06-30
    Electrical Meter (USA, 455,068)                                  :active, p_us_52, 1891-03-27, 1891-06-30
    Electric Incandescent Lamp (USA, 455,069)                        :active, p_us_54, 1891-05-14, 1891-06-30
    Improvements in Alternating Current Electro-magnetic... (GBR, 11,473) :active, p_int_119, 1891-07-06, 1891-08-22
    Perfectionnements dans les moteurs electromagnetiques... (FRA, 214,718) :active, p_int_66, 1891-07-07, 1891-08-30
    Feldmagnetanordnung für Wechselstromkraftmaschine (DEU, 58774)  :active, p_int_94, 1889-12-02, 1891-09-15
    Method of Operating Electro-Magnetic Motors (USA, 459,772)       :active, p_us_35, 1889-05-20, 1891-09-22
    Procédé et appareil perfectionnés pour produire... (FRA, 213,556) :active, p_int_65, 1891-05-19, 1891-09-12
    Neuerungen an elektromagnetischen Wechselstrommotoren (AUT, 41/3095) :active, p_int_8, 1891-07-09, 1891-10-21
    Method of and Apparatus for Electrical Conversion... (USA, 462,418) :active, p_us_51, 1891-02-04, 1891-11-03
    Electro-Magnetic Motor (USA, 464,666)                            :active, p_us_55, 1891-07-13, 1891-12-08
    Electrical Condenser (USA, 464,667)                              :active, p_us_56, 1891-08-01, 1891-12-08
    %% --- 1892 ---
    System of Electrical Transmission of Power (USA, 487,796)        :active, p_us_22, 1888-05-15, 1892-12-13
    %% --- 1893 ---
    Wechselstromtreibmascnine mit auf eine in sich... (DEU, 66802)  :active, p_int_95, 1889-12-02, 1893-01-26
    System of Electrical Power Transmission (USA, 511,559)           :active, p_us_28, 1888-12-08, 1893-12-26
    Electro-Magnetic Motor (USA, 511,560)                            :active, p_us_29, 1888-12-08, 1893-12-26
    %% --- 1894 ---
    Steam Engine (USA, 512,340)                                      :active, p_us_65, 1893-12-29, 1894-01-09
    Means for Generating Electric Currents (USA, 511,916)            :active, p_us_61, 1893-08-02, 1894-01-02
    Electro-Magnetic Motor (USA, 511,915)                            :active, p_us_26, 1888-10-20, 1894-01-02
    Verfahren zur Erzeugung elektrischen Lichtes (DEU, 73080)        :active, p_int_96, 1891-05-19, 1894-01-22
    Incandescent Electric Light (USA, 514,170)                       :active, p_us_57, 1892-01-02, 1894-02-06
    Electrical Conductor (USA, 514,167)                              :active, p_us_58, 1892-01-02, 1894-02-06
    Coil for Electro-Magnets (USA, 514,168)                          :active, p_us_60, 1893-07-07, 1894-02-06
    Electric Generator (USA, 514,169)                                :active, p_us_62, 1893-08-19, 1894-02-06
    Electric Railway Systems (USA, 514,972)                          :active, p_us_59, 1892-01-02, 1894-02-20
    Reciprocating Engine (USA, 514,973)                              :active, p_us_63, 1893-08-19, 1894-02-20
    Perfectionnements dans les machines á mouvement... (BEL, 108594) :active, p_int_26, 1894-02-17, 1894-02-28
    Perfectionnements dans les moyens et appareils... (BEL, 108595)  :active, p_int_27, 1894-02-17, 1894-02-28
    Vorrichtung zum Hervorbringen elektrischer Ströme... (AUT, 44/1865) :active, p_int_9, 1893-08-31, 1894-03-07
    Improvements in Methods of and Apparatus for the Generation... (GBR, 2,812) :active, p_int_120, 1894-02-08, 1894-03-10
    
    %% The patent below using Italian title for ITA patent
    Perfezionamenti dans les machines á mouvement... (ITA, 35836)    :active, p_int_152, 1894-03-02, 1894-03-22 
    
    
    Improvements in Reciprocating Engines and Means... (GBR, 2,801)  :active, p_int_121, 1894-02-08, 1894-04-14
    Electrical Meter (USA, 517,900)                                  :active, p_us_64, 1893-12-15, 1894-04-10
    Treibmaschine (AUT, 44/3504)                                     :active, p_int_10, 1893-08-31, 1894-04-26
    Perfectionnements dans les machines á mouvement... (FRA, 236,356) :active, p_int_67, 1894-02-17, 1894-05-08
    Perfectionnements dans les moyens et appareils... (FRA, 236,357) :active, p_int_68, 1894-02-17, 1894-05-08
    Electrical Transmission of Power (USA, 524,426)                  :active, p_us_24, 1888-05-15, 1894-08-14
    %% --- 1895 ---
    Durch Dampf oder Druckluft betriebenes... (DEU, 84335)           :active, p_int_97, 1893-08-28, 1895-12-03
    %% --- 1896 ---
    Alternating Motor (USA, 555,190)                                 :active, p_us_23, 1888-05-15, 1896-02-25
    Vorrcihtung zur Erzeugung elektrischer Ströme... (DEU, 87269)    :active, p_int_98, 1893-08-28, 1896-06-25
    Electrical Condenser (USA, 567,818)                              :active, p_us_68, 1896-06-17, 1896-09-15
    Apparatus for Producing Electric Currents of High... (USA, 568,176) :active, p_us_66, 1896-04-22, 1896-09-22
    Apparatus for Producing Ozone (USA, 568,177)                     :active, p_us_67, 1896-06-17, 1896-09-22
    Method of Regulating Apparatus for Producing... (USA, 568,178)   :active, p_us_69, 1896-06-20, 1896-09-22
    Method of and Apparatus for Producing Currents... (USA, 568,179) :active, p_us_70, 1896-07-06, 1896-09-22
    Apparatus for Producing Electrical Currents of High... (USA, 568,180) :active, p_us_71, 1896-07-09, 1896-09-22
    Perfectionnements relatifs á la production, au réglage... (BEL, 123665) :active, p_int_28, 1896-09-22, 1896-10-15
    Perfectionnements relatifs á la production, au réglage... (ITA, 42615) :active, p_int_154, 1896-09-22, 1896-10-21
    
    %% The patent below is anomaly Grant<Filing, G set to F
    Perfectionnements dans les moyens et appareils... (ITA, 35837)    :active, p_int_153_ano, 1896-09-22, 1896-09-22 
    
    
    Improvements Relating to the Production, Regulation... (GBR, 20,981) :active, p_int_122, 1896-09-22, 1896-11-21
    %% --- 1897 ---
    Perfectionnements relatifs á la production, au réglage... (FRA, 259,940) :active, p_int_69, 1896-09-22, 1897-01-11
    Apparatus for Producing Electric Currents of High... (USA, 577,670) :active, p_us_72, 1896-09-03, 1897-02-23
    Manufacture of Electrical Condensers, Coils... (USA, 577,671)    :active, p_us_74, 1896-11-05, 1897-02-23
    Neuerungen in der Erzeugung, Regelung und... (AUT, 47/1746)      :active, p_int_11, 1896-09-22, 1897-05-14
    Apparatus for Producing Currents of High... (USA, 583,953)       :active, p_us_73, 1896-10-19, 1897-06-08
    An improved method of and apparatus for producing... (VIC, 13596) :active, p_int_198, 1896-10-15, 1897-06-03
    Improvements in Methods of and Apparatus for Producing... (NSW, 6972) :active, p_int_170, 1896-10-16, 1897-07-02
    Stromkreisregler für die Umwandlung von Strömen... (DEU, 93255) :active, p_int_99, 1896-09-21, 1897-08-20
    Electric-Circuit Controller (USA, 593,138)                       :active, p_us_77, 1897-06-03, 1897-11-02
    Perfectionnements dans les systémes de transmission... (BEL, 131524) :active, p_int_29, 1897-10-26, 1897-11-15
    Improvements in methods and systems for the transmision... (VIC, 14798) :active, p_int_199, 1897-11-25, 1897-12-09
    %% --- 1898 ---
    Perfectionnements dans les systémes de transmission... (FRA, 271,641) :active, p_int_70, 1897-10-29, 1898-02-07
    Verfahren und Vorrichtung zur Übertragung... (AUT, 48/1618)      :active, p_int_12, 1897-10-28, 1898-03-18
    Improvements in Systems for the Transmission... (GBR, 24,421)    :active, p_int_123, 1897-10-21, 1898-03-26
    Improvements in systems for the transmission... (NSW, 8019)      :active, p_int_171, 1897-11-26, 1898-03-05
    Eljarás és berendezés elektromos energia átvitelére (HUN, 11230) :active, p_int_139, 1897-10-27, 1898-04-01
    Perfezionamenti nei sistemi di transmissione... (ITA, 47334)     :active, p_int_155, 1898-02-28, 1898-04-18
    Perfectionnements aux côntroleurs de circuits... (BEL, 136606)   :active, p_int_30, 1898-07-04, 1898-07-15
    Electrical Igniter for Gas-Engines (USA, 609,250)                :active, p_us_75, 1897-02-17, 1898-08-16
    Electrical Transformer (USA, 609,251)                            :active, p_us_76, 1897-03-20, 1898-08-16
    Electrical-Circuit Controller (USA, 609,245)                     :active, p_us_80, 1897-12-02, 1898-08-16
    Electrical-Circuit Controller (USA, 609,246)                     :active, p_us_82, 1898-02-28, 1898-08-16
    Electric-Circuit Controller (USA, 609,247)                       :active, p_us_83, 1898-03-12, 1898-08-16
    Electric-Circuit Controller (USA, 609,248)                       :active, p_us_84, 1898-03-12, 1898-08-16
    Electric-Circuit Controller (USA, 609,249)                       :active, p_us_85, 1898-03-12, 1898-08-16
    Improvements in Electrical Circuit Controllers (GBR, 12,866)     :active, p_int_124, 1898-06-08, 1898-08-27
    Perfezionamenti nei regolatori del circuito... (ITA, 48461)      :active, p_int_156, 1898-06-18, 1898-09-17
    Einrichtung zur Erzielung von Strömen hoher Frequenz... (DEU, 99173) :active, p_int_100, 1896-09-21, 1898-09-28
    Electrical-Circuit Controller (USA, 611,719)                     :active, p_us_81, 1897-12-10, 1898-10-04
    Perfectionnements aux côntroleurs de circuits... (FRA, 279,362)  :active, p_int_71, 1898-07-01, 1898-10-18
    Electric-Circuit Controller (USA, 613,735)                       :active, p_us_86, 1898-04-19, 1898-11-08
    Method of and Apparatus for Controlling the Mechanism... (USA, 613,809) :active, p_us_87, 1898-07-01, 1898-11-08
    %% --- 1899 ---
    Neuerungen an Stromunterbrechern (AUT, 49/1150)                  :active, p_int_13, 1898-06-20, 1899-02-01
    Perfectionnements dans le procédé et les appareils... (BEL, 140489) :active, p_int_31, 1899-01-30, 1899-02-15
    Mejoras en el sistema de gobierno del mecanismo... (ESP, 23742)  :active, p_int_181, 1899-01-31, 1899-03-09
    Perfectionnements dans le procédé et les appareils... (FRA, 284,352) :active, p_int_72, 1898-12-24, 1899-03-30
    Perfectionnements dans le procédé et les appareils... (ITA, 50371) :active, p_int_157, 1899-01-17, 1899-04-13
    Berendezés áramköröknek gyors egymasutánbán való... (HUN, 15067)  :active, p_int_140, 1898-06-27, 1899-05-30
    Improvements in the Method of and Apparatus for Controlling... (GBR, 26,371) :active, p_int_125, 1898-12-13, 1899-12-09

    section Patents Granted in the 1900s
    %% --- 1900 ---
    System of Transmission of Electrical Energy (USA, 645,576)       :active, p_us_78, 1897-09-02, 1900-03-20
    Stromunterbrecher mit flüssigem Leiter (DEU, 109865)             :active, p_int_101, 1898-06-18, 1900-04-19
    Stromunterbrecher mit flüssigem Leiter (DEU, 110050)             :active, p_int_103, 1898-06-18, 1900-04-20
    Stromunterbrecher mit flüssigem Leiter (DEU, 110049)             :active, p_int_102, 1898-06-18, 1900-04-21
    Apparatus for Transmission of Electrical Energy (USA, 649,621)   :active, p_us_79, 1897-09-02, 1900-05-15
    Einrichtung zur Beherrschung der Treib- und... (AUT, 50/55)      :active, p_int_14, 1898-11-07, 1900-08-11
    Methods of Insulating Electric Conductors (USA, 655,838)         :active, p_us_94, 1900-06-15, 1900-08-14
    Methodo e apparetho para mechanismos de regular... (BRA, 2882)   :active, p_int_46, 1899-08-14, 1900-08-25
    Perfectionnements á l'isolement des conducteurs... (BEL, 151563) :active, p_int_32, 1900-08-14, 1900-08-31
    Method of Insulating Electric Conductors (Reissued) (USA, 11,865) :active, p_us_97, 1900-09-21, 1900-10-23
    Perfectionnements á l'isolement des conducteurs... (FRA, 303,025) :active, p_int_73, 1900-08-14, 1900-11-20
    Perfezionamenti á l'isolement des conducteurs... (ITA, 56591)    :active, p_int_158, 1900-08-14, 1900-11-29
    Perfezionamenti á l'isolement des conducteurs... (ITA, 56676)    :active, p_int_159, 1900-08-14, 1900-11-29
    Mejoras en el aislamiento de conductores eléctricos (ESP, 26430) :active, p_int_182, 1900-08-14, 1900-12-07
    Трансформаторъ, служщаго для передачи... (RUS, 4656)             :active, p_int_177, 1897-10-18, 1900-12-30
    Installation pour la transmission d'énergie électrique (CHE, 15542) :active, p_int_191, 1897-10-26, 1900-09-22
    %% --- 1901 ---
    Improvements Relating to the Insulation of Electric... (GBR, 14,550) :active, p_int_126, 1900-08-14, 1901-01-12
    Perfectionnements á l'isolement des conducteurs... (ITA, 57312)  :active, p_int_160, 1900-10-18, 1901-01-29
    Eljarás elektromos vezetékek szigetelésére (HUN, 20897)          :active, p_int_142, 1900-08-14, 1901-02-20
    Mejoras en el aislamiento de conductores eléctricos (ESP, 26801) :active, p_int_183, 1900-08-14, 1901-02-08
    Fremgangsmaade til ved Hjaelp af Afkøling at isolere... (DNK, 4094) :active, p_int_56, 1900-08-14, 1901-07-22
    Perfectionnements á la transmission de l'énergie... (BEL, 157668) :active, p_int_33, 1901-07-17, 1901-07-31
    Perfectionnements á la transmission de l'énergie... (BEL, 158088) :active, p_int_34, 1901-08-08, 1901-08-31
    Isolation af elektriske ledere (NOR, 9847)                       :active, p_int_173, 1900-08-14, 1901-08-26
    Sätt att isolera elektriska konduktorer (SWE, 12969)              :active, p_int_187, 1900-09-22, 1901-08-22
    Perfectionnments á l'utilisation des variations... (FRA, 311,629) :active, p_int_74, 1901-06-10, 1901-09-26
    Means for Increasing the Intensity of Electrical... (USA, 685,012) :active, p_us_92, 1900-03-21, 1901-10-22
    Improvements Relating to the Utilization of Electromagnetic... (GBR, 11,293) :active, p_int_127, 1901-06-01, 1901-11-02
    Method of Intensifying and Utilizing Effects... (USA, 685,953)    :active, p_us_88, 1899-06-24, 1901-11-05
    Apparatus for Utilizing Effects Transmitted from a Distance... (USA, 685,955) :active, p_us_89, 1899-06-24, 1901-11-05
    Method of Utilizing Effects Transmitted through... (USA, 685,954) :active, p_us_90, 1899-08-01, 1901-11-05
    Apparatus for Utilizing Effects Transmitted through... (USA, 685,956) :active, p_us_91, 1899-08-01, 1901-11-05
    Apparatus for Utilization of Radiant Energy (USA, 685,957)       :active, p_us_98, 1901-03-21, 1901-11-05
    Method of Utilizing Radiant Energy (USA, 685,958)                :active, p_us_99, 1901-03-21, 1901-11-05
    Improvements in, and relating to, the Transmission... (GBR, 13,563) :active, p_int_128, 1901-07-03, 1901-11-09
    Perfectionnements á la transmission de l'énergie... (FRA, 312,783) :active, p_int_75, 1901-07-17, 1901-11-13
    Perfectionnements á la transmission de l'énergie... (FRA, 313,188) :active, p_int_76, 1901-08-02, 1901-11-23
    Perfectionnement á la transmission de l'énergie... (ITA, 60679)  :active, p_int_161, 1901-08-08, 1901-12-12
    Installation pour commander la marche des machines... (CHE, 18652) :active, p_int_192, 1899-01-20, 1901-12-19
    Installation d'isolation de conducteurs électriques (CHE, 22213) :active, p_int_193, 1900-08-14, 1901-12-31
    %% --- 1902 ---
    Űjitás az elektromos energia távközlésére... (HUN, 24076)        :active, p_int_143, 1901-07-13, 1902-03-12
    Improvements in, and relating to, the Transmission... (GBR, 14,579) :active, p_int_129, 1901-07-17, 1902-04-24
    Eljarás és berendezés jármüveknek távolrol való... (HUN, 24842)   :active, p_int_141, 1898-11-07, 1902-06-01
    Verfahren zur Isolierung elektrischer Leiter (AUT, 9098)         :active, p_int_15, 1900-08-14, 1902-08-01
    Űjitások villamos energia távközlésében (HUN, 25869)             :active, p_int_144, 1901-07-23, 1902-10-02
    Verfahren zur Erzeugung elektrischer Schwingungen (DEU, 136841)  :active, p_int_108, 1901-07-09, 1902-12-10
    %% --- 1903 ---
    System of Signaling (USA, 723,188)                               :active, p_us_95, 1900-07-16, 1903-03-17
    Verfahren und Vorrichtung zur Nutzbarmachung... (DEU, 139464)    :active, p_int_105, 1901-06-19, 1903-03-27
    Verfahren und Vorrichtung zur Nutzbarmachung... (DEU, 139465)    :active, p_int_106, 1901-06-19, 1903-03-27
    Verfahren zur Nutzbarmachung von aus der ferne... (DEU, 139466)  :active, p_int_107, 1901-06-19, 1903-03-27
    Способъ приданія изолирующихъ свойствъ... (RUS, 7692)            :active, p_int_179, 1900-08-01, 1903-03-31
    Method of Signaling (USA, 725,605)                               :active, p_us_96, 1900-07-16, 1903-04-14
    Einrichtung zur Übertragung elektrischer Energie (AUT, 13115)    :active, p_int_16, 1901-07-11, 1903-07-02
    Verfahren und Vorrichtung zur sicheren Übertragung... (DEU, 143453) :active, p_int_109, 1901-07-22, 1903-08-12
    Vorrichtung zur Fernsteurung von Wasserfahrzeugen... (DEU, 142842) :active, p_int_104, 1898-11-07, 1903-08-01
    %% --- 1904 ---
    Einrichtung zur Übertragung elektrischer Energie (AUT, 16480)    :active, p_int_17, 1901-07-26, 1904-04-21
    %% --- 1905 ---
    Art of Transmitting Electrical Energy through... (USA, 787,412)  :active, p_us_93, 1900-05-16, 1905-04-18
    Perfectionnement á la transmission de l'énergie... (ITA, 76685)  :active, p_int_162, 1905-04-18, 1905-05-24
    Приспособленія для управленія дъйствіемъ... (RUS, 10188)          :active, p_int_178, 1898-10-26, 1905-06-30
    
    %% The patent below is anomaly Grant<Filing, Grant set to Filing
    Procédé et appareils pour la production et l'utilisation... (FRA, 354,791) :active, p_int_77_ano, 1905-08-18, 1905-08-18 
    
    
    %% --- 1906 ---
    Improvements relating to the Transmission of Electrical... (GBR, 8,200) :active, p_int_130, 1905-04-17, 1906-04-17
    %% --- 1907 ---
    Способъ передачи электической энергий безъ... (RUS, 11535)        :active, p_int_180, 1901-07-16, 1907-01-30

    section Patents Granted in the 1910s
    %% --- 1910 ---
    Perfectionnements concernant la propulsion fluide (BEL, 229701)  :active, p_int_35, 1910-10-19, 1910-10-31
    Una maquina que puede ser empleada como bomba... (MEX, 11079)   :active, p_int_167, 1910-10-18, 1910-10-25
    Mejoras introducidas en los motores, actuados por fluido (ESP, 49122) :active, p_int_184, 1910-10-21, 1910-11-15
    Procédé et appareils pour la production et l'utilisation... (FRA, 421,543) :active, p_int_78, 1910-10-17, 1910-12-24
    
    %% The patent below is no Grant Date, G set to F
    Improvements in Fluid Propulsion (TRA, 593)                     :active, p_int_195_ano, 1910-12-02, 1910-12-02 
    
    
    %% --- 1911 ---
    Improvement in Fluid Propulsion and Fluid Propelled... (AUS, 20211):active, p_int_2, 1910-12-15, 1911-02-20
    Method of and Apparatus for Imparting Energy to or Deriving... (GBR, 24,001) :active, p_int_131, 1910-10-17, 1911-07-06
    Eljarás és gép energiának folyadékokra való... (HUN, 54937)      :active, p_int_145, 1910-10-20, 1911-10-31
    Improvements in fluid propulsion (IND, 640)                     :active, p_int_146, 1910-12-08, 1911-03-27
    Aperfeiçoamentos em propulsao por meio de fluido (BRA, 6435)     :active, p_int_47, 1910-10-20, 1911-03-08
    Fluid Propulsion (CAN, 135174)                                   :active, p_int_54, 1910-11-24, 1911-04-22
    Improvements in fluid propulsion (NZL, 28853)                    :active, p_int_172, 1910-12-08, 1911-05-23
    Perfezionamenti nella propulsione a fluido (ITA, 112767)         :active, p_int_163, 1910-10-20, 1911-05-19
    Improvements in fluid propulsion (RHO, 651)                     :active, p_int_176, 1910-12-15, 1911-08-28
    Mejoras en medios de propulsión por fluido (CUB, 1433)           :active, p_int_55, 1910-11-30, 1911-11-24
    %% --- 1912 ---
    %% The patent below is anomaly Grant<Filing, G set to F
    Mejoras en medios de propulsión por fluido (ARG, 9089)           :active, p_int_1_ano, 1912-03-15, 1912-03-15 
    
    Electrical Energy Transmission (CAN, 142352)                     :active, p_int_53, 1906-04-17, 1912-08-13
    Fremgangsmaate og apparat til utvikling og overføring... (NOR, 22689):active, p_int_174, 1910-11-25, 1912-10-21
    Fluid Propulsion (JPN, 21883)                                    :active, p_int_166, 1912-03-26, 1912-12-28
    Machine rotative pouvant travailler comme pompe... (CHE, 54375)  :active, p_int_194, 1910-11-15, 1912-05-17
    
    %% The patent below is anomaly Grant (1912-05-17) < Filing (1915-03-04), G set to F for timeline
    Rotationsmaskin (SWE, 38545)                                     :active, p_int_188_ano, 1915-03-04, 1915-03-04 
    
    %% --- 1913 ---
    Fluid Propulsion (USA, 1,061,206)                                :active, p_us_101, 1909-10-21, 1913-05-06
    Turbine (USA, 1,061,142)                                         :active, p_us_102, 1909-10-21, 1913-05-06
    Kraftmaschine oder Pumpe mit mehreren... (AUT, 60332)            :active, p_int_18, 1910-10-21, 1913-05-31
    %% --- 1914 ---
    Apparatus for Transmitting Electrical Energy (USA, 1,119,732)    :active, p_us_100, 1902-01-18, 1914-12-01
    Fountain (USA, 1,113,716)                                        :active, p_us_103, 1913-10-28, 1914-10-13
    %% --- 1916 ---
    Speed-Indicator (USA, 1,209,359)                                 :active, p_us_104, 1914-05-29, 1916-12-19
    %% --- 1918 ---
    Lightning Protector (USA, 1,266,175)                             :active, p_us_106, 1916-05-06, 1918-05-14
    Speed-Indicator (USA, 1,274,816)                                 :active, p_us_110, 1916-12-18, 1918-08-06
    %% --- 1919 ---
    Ship's Log (USA, 1,314,718)                                      :active, p_us_109, 1916-12-18, 1919-09-02

    section Patents Granted in the 1920s
    %% --- 1920 ---
    Valvular Conduit (USA, 1,329,559)                                :active, p_us_105, 1916-02-21, 1920-02-03
    Perfectionnements aux fontaines (BEL, 286983)                    :active, p_int_36, 1920-05-22, 1920-06-16
    Perfectionnements aux fontaines (FRA, 515,388)                   :active, p_int_79, 1920-05-11, 1920-11-25
    %% --- 1921 ---
    Flow Meter (USA, 1,365,547)                                      :active, p_us_107, 1916-12-18, 1921-01-11
    Perfectionnements aux paratonnerres (BEL, 298511)                :active, p_int_37, 1921-09-03, 1921-12-30
    Conduit faisant fonction de valve (BEL, 298512)                  :active, p_int_38, 1921-09-03, 1921-12-30
    %% --- 1922 ---
    Frequency Meter (USA, 1,402,025)                                 :active, p_us_108, 1916-12-18, 1922-01-03
    Improved Method of and Apparatus for the Generation of Power... (GBR, 174,544) :active, p_int_136, 1921-04-01, 1922-02-02
    Perfectionnements aux turbines actionées par la vapeur... (BEL, 302317) :active, p_int_39, 1922-03-23, 1922-04-15
    Procédé et appareil pour la production d'un vide éléve (BEL, 302318) :active, p_int_40, 1922-03-23, 1922-04-15
    Procédé et appareil pour l'utilisation de la vapeur... (BEL, 302319) :active, p_int_41, 1922-03-23, 1922-04-15
    Procédé et appareil pour économique de l'énergie... (BEL, 302320) :active, p_int_42, 1922-03-23, 1922-04-15
    Perfectionnements aux procédés et machines pour obtention... (BEL, 302321) :active, p_int_43, 1922-03-31, 1922-04-15
    Conduite faisant fonction de valve (FRA, 540,616)                :active, p_int_80, 1921-09-03, 1922-04-20
    Perfectionnements aux paratonnerres (FRA, 540,617)               :active, p_int_81, 1921-09-03, 1922-04-20
    Perfectionnements aux turbines actionées par la vapeur... (FRA, 541,112) :active, p_int_82, 1921-09-15, 1922-04-27
    Procédé et appareil pour équilibrer les piéces... (FRA, 541,113) :active, p_int_83, 1921-09-15, 1922-04-27
    Procédé et appareil pour transports aériens (BEL, 302824)        :active, p_int_44, 1922-04-03, 1922-05-15
    Improved Process of and Apparatus for Production of High Vacua (GBR, 179,043) :active, p_int_132, 1921-03-24, 1922-05-04
    Un procedimiento, con su aparato correspondiente... (ESP, 81244) :active, p_int_185, 1922-03-31, 1922-05-27
    Un método, con su aparato correspondiente para... (ESP, 81253)   :active, p_int_186, 1922-04-03, 1922-05-27
    Method of and Apparatus for Aerial Transportation (GBR, 185,446) :active, p_int_137, 1921-04-04, 1922-09-04
    Improvements in the Construction of Steam and Gas Turbines (GBR, 186,082) :active, p_int_133, 1921-03-24, 1922-09-25
    Improved Method of and Apparatus for the Economic... (GBR, 186,083) :active, p_int_134, 1921-03-24, 1922-09-25
    Improved Method of and Apparatus for Deriving Motive... (GBR, 186,084) :active, p_int_135, 1921-03-24, 1922-09-25
    Procédé et appareil pour équilibrer les piéces... (BEL, 305851) :active, p_int_45, 1922-09-02, 1922-10-16
    Process of, and Apparatus for Balancing Rotating Machine... (GBR, 186,799) :active, p_int_138, 1921-09-02, 1922-10-12
    Procédé et appareil pour économique de l'énergie... (FRA, 549,259) :active, p_int_84, 1922-03-23, 1922-11-14
    Procédé et appareil pour l'utilisation de la vapeur... (FRA, 549,260) :active, p_int_85, 1922-03-23, 1922-11-14
    Procédé et appareil pour la production d'un éléve (FRA, 549,261) :active, p_int_86, 1922-03-23, 1922-11-14
    Perfectionnements aux procédés et machines pour obtention... (FRA, 549,516) :active, p_int_87, 1922-03-30, 1922-11-22
    Procédé et appareil pour transports aériens (FRA, 549,628)      :active, p_int_88, 1922-04-01, 1922-11-24
    
    %% The patent below has typo in original, using date as is
    Sistema e apparecchio per trasporti aerei (ITA, 208594)         :active, p_int_164, 1922-03-31, 1922-03-31 
    
    %% --- 1923 ---
    Fremgangsmaade og Apparat til Omdannelse af Varmeenergi... (DNK, 31737) :active, p_int_57, 1922-03-31, 1923-05-08
    Flyvemaskine (DNK, 31663)                                        :active, p_int_58, 1922-04-03, 1923-04-24
    Fremgangsmaate og apparat til frembringelse av mekanisk... (NOR, 38426) :active, p_int_175, 1922-04-01, 1923-11-26
    %% --- 1926 ---
    Sätt och apparat för att utbalansera roterande... (SWE, 60297)   :active, p_int_189, 1922-09-01, 1926-02-23
    
    %% The patent below is no Filing, F set to G
    Anordning vid turbinaggregat med anordning för... (SWE, 60428)   :active, p_int_190_ano, 1926-03-23, 1926-03-23 
    
    %% --- 1928 ---
    Method of Aerial Transportation (USA, 1,655,113)                 :active, p_us_111, 1921-09-09, 1928-01-03
    Apparatus for Aerial Transportation (USA, 1,655,114)             :active, p_us_112, 1921-09-09, 1928-01-03
    %% --- 1929 ---
    Sistema e apparecchio per trasporti aerei (ITA, 269409)          :active, p_int_165, 1928-04-30, 1929-11-19
```

----

<!-- 
```mermaid
%% Current Mermaid version
info
```  -->


```mermaid
---
title: "CongLeSolutionX"
author: "Cong Le"
version: "1.0"
license(s): "MIT, CC BY-SA 4.0"
copyright: "Copyright (c) 2025 Cong Le. All Rights Reserved."
config:
  theme: base
---
%%%%%%%% Mermaid version v11.4.1-b.14
%%{
  init: {
    'flowchart': { 'htmlLabels': false },
    'fontFamily': 'Bradley Hand',
    'themeVariables': {
      'primaryColor': '#fc82',
      'primaryTextColor': '#F8B229',
      'primaryBorderColor': '#27AE60',
      'secondaryColor': '#81c784',
      'secondaryTextColor': '#6C3483',
      'lineColor': '#F8B229',
      'fontSize': '20px'
    }
  }
}%%
flowchart LR
  My_Meme@{ img: "https://raw.githubusercontent.com/CongLeSolutionX/CongLeSolutionX/refs/heads/main/assets/images/My-meme-question-marks-light-bulb-brain.png", label: "Ăn uống gì chưa ngừi đẹp?", pos: "b", w: 200, h: 150, constraint: "off" }

  Closing_quote@{ shape: braces, label: "...❓curiosity❓<br/> led me to <br/> 🧠 consciousness 🤯..." }

  Closing_quote  ~~~ My_Meme
    
  Link_to_my_profile{{"<a href='https://github.com/CongLeSolutionX/CongLeSolutionX' target='_blank'>Click here if you care about my profile</a>"}}

  Closing_quote ~~~ My_Meme
  My_Meme animatingEdge@--> Link_to_my_profile
  
  animatingEdge@{ animate: true }

```

---
><b>Licenses</b>:
>
>- <b>MIT License</b>:  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) - Full text in [LICENSE](LICENSE) file.
>- <b>Creative Commons Attribution-ShareAlike 4.0 International</b>: [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) [![CC BY-SA 4.0](https://licensebuttons.net/l/by-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-sa/4.0/) - Legal details in [LICENSE-CC-BY-SA-4.0](THE_PAST/LICENSE-CC-BY-SA-4.0) and at [Creative Commons official site](https://creativecommons.org/licenses/by-sa/4.0/).
>
---
