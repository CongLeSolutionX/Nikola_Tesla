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
> ![Loading...](https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExY2ZoMzBtcnh6b3dkOXJlMzhvN3gydW1mdDR2dDAwOGphMG92OWw5ZiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/QaMhVZVwOvDiw/giphy.gif)
>
> gif image is provided by [Giphy](https://giphy.com)
> 
> ⚠️🏗️🚧🦺🧱🪵🪨🪚🛠️👷


----




# Nikola Tesla's Non-USA Patents Timeline
<details open>
<summary>Click to show/hide the full disclaimer.</summary>
   
> <ins>📢 **Disclaimer** 🚨</ins>
>
> This document contains my personal notes on the topic,
> compiled from publicly available documentation and various cited sources.
> The materials are intended for educational purposes (<ins>sometimes, entertainment purposes</ins>), personal study, and reference.
> The content is dual-licensed:
> 1. **MIT License:** Applies to all code implementations (Swift, Mermaid, and other programming languages).
> 2. **Creative Commons Attribution-ShareAlike 4.0 International License (CC BY-SA 4.0):** Applies to all non-code content, including text, explanations, diagrams, and illustrations.

</details>


----

I've made the following consistent choices for clarity and handling data peculiarities:
*   Dates are converted to `YYYY-MM-DD` format.
*   The title for each patent on the chart is shortened and includes the country abbreviation and patent number, like: `Shortened Title (Country, Patent #)`.
*   Patents are sectioned by the decade in which they were granted.
*   **Data Anomalies Handled:** In cases where the provided Grant Date is *before* the Filing Date, or if a date is missing, I've set the Grant Date equal to the Filing Date for the purpose of visualization, making it a point event or ensuring chronological order for the bar. Specific instances are:
	*   Argentina (Serial #1, Pat. 9089): Grant date 1911-05-23, Filing date 1912-03-15. Grant set to 1912-03-15 for the timeline.
	*   France (Serial #77, Pat. 354,791): Grant date 1905-08-08, Filing date 1905-08-18. Grant set to 1905-08-18.
	*   Italy (Serial #153, Pat. 35837): Grant date 1894-03-22, Filing date 1896-09-22. Grant set to 1896-09-22.
	*   Sweden (Serial #188, Pat. 38545): Grant date 1912-05-17, Filing date 1915-03-04. Grant set to 1915-03-04.
	*   Sweden (Serial #190, Pat. 60428): No Filing Date provided. Filing date set to Grant date (1926-03-23).
	*   Transvaal (Serial #195, Pat. 593): No Grant Date provided. Grant date set to Filing date (1910-12-02).

-----

Here is the Mermaid Gantt chart for Nikola Tesla's non-USA patents: 🌍📜

```mermaid
---
title: "Nikola Tesla's Non-USA Patents Timeline"
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
    title Nikola Tesla's Non-USA Patents Timeline
    axisFormat %Y

    section Patents Granted in the 1880s
    Dynamo Machines (CAN, 24033)                       :active, p_int_48, 1886-04-27, 1886-05-10
    Electric Arc Lamp (CAN, 24348)                      :active, p_int_49, 1886-04-27, 1886-06-18
    
    %% For the patent below, Fixed Grant Date logic from thought process
    Regulirvorrichtung Bogenlampen (DEU, 37781)         :active, p_int_89, 1886-02-09, 1886-08-12

    Schaltung dynamos (DEU, 37103)                      :active, p_int_90, 1886-03-02, 1886-10-05
    Electric Lamps (GBR, 1877)                          :active, p_int_110, 1886-02-09, 1886-09-16
    Dynamo Machines (GBR, 2975)                         :active, p_int_111, 1886-03-02, 1887-02-01
    Transmission de la force (BEL, 81636)               :active, p_int_19, 1888-05-01, 1888-05-15
    Procédés et appareils (BEL, 81637)                  :active, p_int_20, 1888-05-01, 1888-05-15
    Electrical Transmission (CAN, 29537)                :active, p_int_50, 1888-05-01, 1888-07-17
    Converting/Distributing Currents (CAN, 30172)       :active, p_int_51, 1888-05-01, 1888-11-10
    Procédés et appareils (FRA, 190332)                 :active, p_int_59, 1888-05-01, 1888-07-05
    Transmission de la force (FRA, 190333)              :active, p_int_60, 1888-05-01, 1888-07-05
    Electrical Transmission (GBR, 6481)                 :active, p_int_112, 1888-05-01, 1888-06-01
    Generation/Distribution Currents (GBR, 6502)        :active, p_int_113, 1888-05-01, 1888-06-01
    Metodi ed apparati (ITA, 23400)                     :active, p_int_147, 1888-06-09, 1888-06-30
    Trasmissione elettrica (ITA, 23401)                 :active, p_int_148, 1888-06-09, 1888-06-30
    Elektrischen Kraftübertragung (AUT, 39/1026)        :active, p_int_3, 1888-05-01, 1889-04-16
    Verfahren und den Apparaten (AUT, 39/1070)          :active, p_int_4, 1888-05-01, 1889-04-24
    Fonctionnement des moteurs (BEL, 85866)             :active, p_int_21, 1889-04-16, 1889-04-30
    Conversion des courants (BEL, 88156)                :active, p_int_22, 1889-10-22, 1889-11-15
    Moteurs électro-magnétiques (BEL, 88701)            :active, p_int_23, 1889-10-03, 1889-10-16
    Construction des moteurs (BEL, 88702)               :active, p_int_24, 1889-10-03, 1889-10-16
    Fonctionnement des moteurs (FRA, 197532)            :active, p_int_61, 1889-04-16, 1889-06-17
    Schaltung Transformators (DEU, 47012)               :active, p_int_91, 1888-04-30, 1889-05-10
    Verbindung Drahtspulen (DEU, 47885)                 :active, p_int_92, 1888-04-30, 1889-07-17
    Electro-motors (GBR, 6527)                          :active, p_int_114, 1889-04-16, 1889-05-18
    Conversion Alternating/Direct (GBR, 16709)          :active, p_int_115, 1889-10-22, 1889-12-07
    Conversion des courants (ITA, 26334)                :active, p_int_149, 1889-09-11, 1889-10-31
    Electrical transmission (NSW, 1122)                 :active, p_int_168, 1888-12-14, 1889-04-09
    Methods of converting (NSW, 1123)                   :active, p_int_169, 1888-12-14, 1889-04-09
    Methods of converting (VIC, 6389)                   :active, p_int_196, 1888-12-10, 1889-01-04
    Electrical transmission (VIC, 6390)                 :active, p_int_197, 1888-12-10, 1889-01-04

    section Patents Granted in the 1890s
    Verfahrungsweisen umzuwandeln (AUT, 40/2564)        :active, p_int_5, 1889-10-22, 1890-09-24
    Wechselstrommotoren (AUT, 40/1043)                  :active, p_int_6, 1889-12-03, 1890-04-02
    Konstruktion Wechselstrommotoren (AUT, 40/2645)     :active, p_int_7, 1889-12-03, 1890-09-27
    Converting Alternating (CAN, 33317)                 :active, p_int_52, 1889-12-19, 1890-02-01
    Conversion des courants (FRA, 201486)               :active, p_int_62, 1889-10-22, 1890-01-03
    Moteurs électro-magnétiques (FRA, 202372)           :active, p_int_63, 1889-10-03, 1890-02-11
    Construction des moteurs (FRA, 202373)              :active, p_int_64, 1889-10-03, 1890-02-11
    Verfahren Wechselströme (DEU, 54797)                :active, p_int_93, 1889-10-21, 1890-12-20
    Alt. Current Motors (GBR, 19420)                     :active, p_int_116, 1889-12-03, 1890-01-11
    Construction Alt. Current Motors (GBR, 19426)       :active, p_int_117, 1889-12-03, 1890-01-11
    Motori dinamo-elettrici (ITA, 26620)                :active, p_int_150, 1889-10-31, 1890-04-25
    Construzione motori (ITA, 26621)                    :active, p_int_151, 1889-10-31, 1890-04-25
    Elektromagnetischen Motoren (AUT, 41/3095)          :active, p_int_8, 1891-07-09, 1891-10-21
    Procédé et appareil (BEL, 94940)                    :active, p_int_25, 1891-05-19, 1891-05-30
    Procédé et appareil (FRA, 213556)                   :active, p_int_65, 1891-05-19, 1891-09-12
    Moteurs electromagnetiques (FRA, 214718)            :active, p_int_66, 1891-07-07, 1891-08-30
    Feldmagnetanordnung (DEU, 58774)                    :active, p_int_94, 1889-12-02, 1891-09-15
    Generating/Utilizing Electric Energy (GBR, 8575)    :active, p_int_118, 1891-05-19, 1891-06-20
    Alt. Current Motors (GBR, 11473)                    :active, p_int_119, 1891-07-06, 1891-08-22
    Wechselstromtreibmascnine (DEU, 66802)              :active, p_int_95, 1889-12-02, 1893-01-26
    Vorrichtung zum Hervorbringen (AUT, 44/1865)        :active, p_int_9, 1893-08-31, 1894-03-07
    Treibmaschine (AUT, 44/3504)                        :active, p_int_10, 1893-08-31, 1894-04-26
    Machines á mouvement (BEL, 108594)                  :active, p_int_26, 1894-02-17, 1894-02-28
    Moyens et appareils (BEL, 108595)                   :active, p_int_27, 1894-02-17, 1894-02-28
    Machines á mouvement (FRA, 236356)                  :active, p_int_67, 1894-02-17, 1894-05-08
    Moyens et appareils (FRA, 236357)                   :active, p_int_68, 1894-02-17, 1894-05-08
    Erzeugung elektrischen Lichtes (DEU, 73080)         :active, p_int_96, 1891-05-19, 1894-01-22
    Generation of Electric Currents (GBR, 2812)         :active, p_int_120, 1894-02-08, 1894-03-10
    Reciprocating Engines (GBR, 2801)                   :active, p_int_121, 1894-02-08, 1894-04-14
    Machines á mouvement (ITA, 35836)                   :active, p_int_152, 1894-03-02, 1894-03-22
    Dampf oder Druckluft (DEU, 84335)                   :active, p_int_97, 1893-08-28, 1895-12-03
    Production, au réglage (BEL, 123665)                :active, p_int_28, 1896-09-22, 1896-10-15
    Erzeugung elektrischer Ströme (DEU, 87269)          :active, p_int_98, 1893-08-28, 1896-06-25
    Production, Regulation (GBR, 20981)                 :active, p_int_122, 1896-09-22, 1896-11-21
    
    %% Patent below is anomaly G<F, G set to F
    Moyens et appareils (ITA, 35837)                    :active, p_int_153_ano, 1896-09-22, 1896-09-22

    Production, au réglage (ITA, 42615)                 :active, p_int_154, 1896-09-22, 1896-10-21
    Erzeugung, Regelung (AUT, 47/1746)                  :active, p_int_11, 1896-09-22, 1897-05-14
    Systémes de transmission (BEL, 131524)              :active, p_int_29, 1897-10-26, 1897-11-15
    Production, au réglage (FRA, 259940)                :active, p_int_69, 1896-09-22, 1897-01-11
    Umwandlung von Strömen (DEU, 93255)                 :active, p_int_99, 1896-09-21, 1897-08-20
    Producing Currents (NSW, 6972)                      :active, p_int_170, 1896-10-16, 1897-07-02
    Producing Currents (VIC, 13596)                     :active, p_int_198, 1896-10-15, 1897-06-03
    Methods and systems (VIC, 14798)                    :active, p_int_199, 1897-11-25, 1897-12-09
    Übertragung elektrischer Kraft (AUT, 48/1618)       :active, p_int_12, 1897-10-28, 1898-03-18
    Côntroleurs de circuits (BEL, 136606)               :active, p_int_30, 1898-07-04, 1898-07-15
    Systémes de transmission (FRA, 271641)              :active, p_int_70, 1897-10-29, 1898-02-07
    Côntroleurs de circuits (FRA, 279362)               :active, p_int_71, 1898-07-01, 1898-10-18
    Erzielung von Strömen (DEU, 99173)                  :active, p_int_100, 1896-09-21, 1898-09-28
    Transmission of Electrical Energy (GBR, 24421)      :active, p_int_123, 1897-10-21, 1898-03-26
    Electrical Circuit Controllers (GBR, 12866)         :active, p_int_124, 1898-06-08, 1898-08-27
    Energia átvitelére (HUN, 11230)                     :active, p_int_139, 1897-10-27, 1898-04-01
    Sistemi di transmissione (ITA, 47334)               :active, p_int_155, 1898-02-28, 1898-04-18
    Regolatori del circuito (ITA, 48461)                :active, p_int_156, 1898-06-18, 1898-09-17
    Transmission of electrical energy (NSW, 8019)       :active, p_int_171, 1897-11-26, 1898-03-05
    Stromunterbrechern (AUT, 49/1150)                   :active, p_int_13, 1898-06-20, 1899-02-01
    Procédé et les appareils (BEL, 140489)              :active, p_int_31, 1899-01-30, 1899-02-15
    Procédé et les appareils (FRA, 284352)              :active, p_int_72, 1898-12-24, 1899-03-30
    Controlling Mechanism (GBR, 26371)                  :active, p_int_125, 1898-12-13, 1899-12-09
    Áramköröknek gyors (HUN, 15067)                      :active, p_int_140, 1898-06-27, 1899-05-30
    Procédé et les appareils (ITA, 50371)               :active, p_int_157, 1899-01-17, 1899-04-13
    Sistema de gobierno (ESP, 23742)                    :active, p_int_181, 1899-01-31, 1899-03-09

    section Patents Granted in the 1900s
    Einrichtung zur Beherrschung (AUT, 50/55)           :active, p_int_14, 1898-11-07, 1900-08-11
    Isolement des conducteurs (BEL, 151563)             :active, p_int_32, 1900-08-14, 1900-08-31
    Methodo e apparetho (BRA, 2882)                     :active, p_int_46, 1899-08-14, 1900-08-25
    Isolement des conducteurs (FRA, 303025)             :active, p_int_73, 1900-08-14, 1900-11-20
    Stromunterbrecher (DEU, 109865)                     :active, p_int_101, 1898-06-18, 1900-04-19
    Stromunterbrecher (DEU, 110049)                     :active, p_int_102, 1898-06-18, 1900-04-21
    Stromunterbrecher (DEU, 110050)                     :active, p_int_103, 1898-06-18, 1900-04-20
    Isolement des conducteurs (ITA, 56591)              :active, p_int_158, 1900-08-14, 1900-11-29
    Isolement des conducteurs (ITA, 56676)              :active, p_int_159, 1900-08-14, 1900-11-29
    Трансформаторъ (RUS, 4656)                          :active, p_int_177, 1897-10-18, 1900-12-30
    Aislamiento de conductores (ESP, 26430)             :active, p_int_182, 1900-08-14, 1900-12-07
    Transmission d'énergie (CHE, 15542)                 :active, p_int_191, 1897-10-26, 1900-09-22
    Transmission de l'énergie (BEL, 157668)             :active, p_int_33, 1901-07-17, 1901-07-31
    Transmission de l'énergie (BEL, 158088)             :active, p_int_34, 1901-08-08, 1901-08-31
    Hjaelp af Afkøling (DEN, 4094)                      :active, p_int_56, 1900-08-14, 1901-07-22
    Utilisation des variations (FRA, 311629)            :active, p_int_74, 1901-06-10, 1901-09-26
    Transmission de l'énergie (FRA, 312783)             :active, p_int_75, 1901-07-17, 1901-11-13
    Transmission de l'énergie (FRA, 313188)             :active, p_int_76, 1901-08-02, 1901-11-23
    Insulation of Electric Conductors (GBR, 14550)      :active, p_int_126, 1900-08-14, 1901-01-12
    Utilization of Electromagnetic (GBR, 11293)         :active, p_int_127, 1901-06-01, 1901-11-02
    Transmission of Electrical Energy (GBR, 13563)      :active, p_int_128, 1901-07-03, 1901-11-09
    Vezetékek szigetelésére (HUN, 20897)                 :active, p_int_142, 1900-08-14, 1901-02-20
    Isolement des conducteurs (ITA, 57312)              :active, p_int_160, 1900-10-18, 1901-01-29
    Transmission de l'énergie (ITA, 60679)              :active, p_int_161, 1901-08-08, 1901-12-12
    Isolation af elektriske ledere (NOR, 9847)          :active, p_int_173, 1900-08-14, 1901-08-26
    Aislamiento de conductores (ESP, 26801)             :active, p_int_183, 1900-08-14, 1901-02-08
    Isolera elektriska konduktorer (SWE, 12969)          :active, p_int_187, 1900-09-22, 1901-08-22
    Commander la marche (CHE, 18652)                    :active, p_int_192, 1899-01-20, 1901-12-19
    Isolation de conducteurs (CHE, 22213)               :active, p_int_193, 1900-08-14, 1901-12-31
    Verfahren zur Isolierung (AUT, 9098)                :active, p_int_15, 1900-08-14, 1902-08-01
    Erzeugung elektrischer Schwingungen (DEU, 136841)   :active, p_int_108, 1901-07-09, 1902-12-10
    Transmission of Electrical Energy (GBR, 14579)      :active, p_int_129, 1901-07-17, 1902-04-24
    Jármüveknek távolrol (HUN, 24842)                    :active, p_int_141, 1898-11-07, 1902-06-01
    Energia távközlésére (HUN, 24076)                    :active, p_int_143, 1901-07-13, 1902-03-12
    Villamos energia (HUN, 25869)                       :active, p_int_144, 1901-07-23, 1902-10-02
    Übertragung elektrischer Energie (AUT, 13115)       :active, p_int_16, 1901-07-11, 1903-07-02
    Fernsteurung von Wasserfahrzeugen (DEU, 142842)     :active, p_int_104, 1898-11-07, 1903-08-01
    Nutzbarmachung Impulsen (DEU, 139464)                :active, p_int_105, 1901-06-19, 1903-03-27
    Nutzbarmachung Impulsen (DEU, 139465)                :active, p_int_106, 1901-06-19, 1903-03-27
    Nutzbarmachung aus der ferne (DEU, 139466)           :active, p_int_107, 1901-06-19, 1903-03-27
    Sicheren Übertragung (DEU, 143453)                  :active, p_int_109, 1901-07-22, 1903-08-12
    Способъ приданія (RUS, 7692)                        :active, p_int_179, 1900-08-01, 1903-03-31
    Übertragung elektrischer Energie (AUT, 16480)       :active, p_int_17, 1901-07-26, 1904-04-21
    
    %% Anomaly G<F, G set to F
    Transmission de l'énergie (FRA, 354791)             :active, p_int_77_ano, 1905-08-18, 1905-08-18

    Transmission de l'énergie (ITA, 76685)              :active, p_int_162, 1905-04-18, 1905-05-24
    Приспособленія для управленія (RUS, 10188)           :active, p_int_178, 1898-10-26, 1905-06-30
    Transmission of Electrical Energy (GBR, 8200)       :active, p_int_130, 1905-04-17, 1906-04-17
    Способъ передачи (RUS, 11535)                       :active, p_int_180, 1901-07-16, 1907-01-30

    section Patents Granted in the 1910s
    Propulsion fluide (BEL, 229701)                     :active, p_int_35, 1910-10-19, 1910-10-31
    Production et l'utilisation (FRA, 421543)           :active, p_int_78, 1910-10-17, 1910-12-24
    Motores, actuados por fluido (ESP, 49122)           :active, p_int_184, 1910-10-21, 1910-11-15
    Maquina que puede ser empleada (MEX, 11079)         :active, p_int_167, 1910-10-18, 1910-10-25
    
    %% Patent below is no Grant, G set to F
    Fluid Propulsion (TRA, 593)                         :active, p_int_195_ano, 1910-12-02, 1910-12-02

    Fluid Propulsion (AUS, 20211)                       :active, p_int_2, 1910-12-15, 1911-02-20
    Propulsao por meio de fluido (BRA, 6435)            :active, p_int_47, 1910-10-20, 1911-03-08
    Fluid Propulsion (CAN, 135174)                      :active, p_int_54, 1910-11-24, 1911-04-22
    Propulsión por fluido (CUB, 1433)                   :active, p_int_55, 1910-11-30, 1911-11-24
    Imparting Energy to Fluid (GBR, 24001)              :active, p_int_131, 1910-10-17, 1911-07-06
    Energia folyadékokra (HUN, 54937)                   :active, p_int_145, 1910-10-20, 1911-10-31
    Fluid propulsion (IND, 640)                         :active, p_int_146, 1910-12-08, 1911-03-27
    Propulsione a fluido (ITA, 112767)                  :active, p_int_163, 1910-10-20, 1911-05-19
    Fluid propulsion (NZL, 28853)                       :active, p_int_172, 1910-12-08, 1911-05-23
    Fluid propulsion (RHO, 651)                         :active, p_int_176, 1910-12-15, 1911-08-28
    
    %% Patent below is anomaly G<F, G set to F
    Propulsión por fluido (ARG, 9089)                   :active, p_int_1_ano, 1912-03-15, 1912-03-15

    Electrical Energy Transmission (CAN, 142352)        :active, p_int_53, 1906-04-17, 1912-08-13
    Fluid Propulsion (JPN, 21883)                       :active, p_int_166, 1912-03-26, 1912-12-28
    Utvikling og overføring av energi (NOR, 22689)      :active, p_int_174, 1910-11-25, 1912-10-21

    %% Patent below is anomaly G<F, G set to F (Original Grant 1912-05-17)
    Rotationsmaskin (SWE, 38545)                        :active, p_int_188_ano, 1915-03-04, 1915-03-04
    
    Machine rotative (CHE, 54375)                       :active, p_int_194, 1910-11-15, 1912-05-17
    Kraftmaschine oder Pumpe (AUT, 60332)               :active, p_int_18, 1910-10-21, 1913-05-31

    section Patents Granted in the 1920s
    Fontaines (BEL, 286983)                             :active, p_int_36, 1920-05-22, 1920-06-16
    Fontaines (FRA, 515388)                             :active, p_int_79, 1920-05-11, 1920-11-25
    Paratonnerres (BEL, 298511)                         :active, p_int_37, 1921-09-03, 1921-12-30
    Conduit faisant fonction de valve (BEL, 298512)     :active, p_int_38, 1921-09-03, 1921-12-30
    Turbines (BEL, 302317)                              :active, p_int_39, 1922-03-23, 1922-04-15
    Production d'un vide éléve (BEL, 302318)            :active, p_int_40, 1922-03-23, 1922-04-15
    Utilisation de la vapeur (BEL, 302319)              :active, p_int_41, 1922-03-23, 1922-04-15
    Économique de l'énergie (BEL, 302320)               :active, p_int_42, 1922-03-23, 1922-04-15
    Procédés et machines (BEL, 302321)                  :active, p_int_43, 1922-03-31, 1922-04-15
    Transports aériens (BEL, 302824)                    :active, p_int_44, 1922-04-03, 1922-05-15
    Équilibrer les piéces (BEL, 305851)                 :active, p_int_45, 1922-09-02, 1922-10-16
    Conduite faisant fonction de valve (FRA, 540616)    :active, p_int_80, 1921-09-03, 1922-04-20
    Paratonnerres (FRA, 540617)                         :active, p_int_81, 1921-09-03, 1922-04-20
    Turbines (FRA, 541112)                              :active, p_int_82, 1921-09-15, 1922-04-27
    Équilibrer les piéces (FRA, 541113)                 :active, p_int_83, 1921-09-15, 1922-04-27
    Économique de l'énergie (FRA, 549259)               :active, p_int_84, 1922-03-23, 1922-11-14
    Utilisation de la vapeur (FRA, 549260)              :active, p_int_85, 1922-03-23, 1922-11-14
    Production d'un éléve (FRA, 549261)                 :active, p_int_86, 1922-03-23, 1922-11-14
    Procédés et machines (FRA, 549516)                  :active, p_int_87, 1922-03-30, 1922-11-22
    Transports aériens (FRA, 549628)                    :active, p_int_88, 1922-04-01, 1922-11-24
    Production of High Vacua (GBR, 179043)              :active, p_int_132, 1921-03-24, 1922-05-04
    Construction of Steam/Gas Turbines (GBR, 186082)    :active, p_int_133, 1921-03-24, 1922-09-25
    Economic Transformation of Steam (GBR, 186083)      :active, p_int_134, 1921-03-24, 1922-09-25
    Deriving Motive Power from Steam (GBR, 186084)      :active, p_int_135, 1921-03-24, 1922-09-25
    Generation of Power by Turbines (GBR, 174544)       :active, p_int_136, 1921-04-01, 1922-02-02
    Aerial Transportation (GBR, 185446)                 :active, p_int_137, 1921-04-04, 1922-09-04
    Balancing Rotating Machine Parts (GBR, 186799)      :active, p_int_138, 1921-09-02, 1922-10-12
    Procédé et machines obtention (ITA, 208594)         :active, p_int_164, 1922-03-31, 1922-03-31
    Procedimiento, con su aparato (ESP, 81244)          :active, p_int_185, 1922-03-31, 1922-05-27
    Método, con su aparato (ESP, 81253)                 :active, p_int_186, 1922-04-03, 1922-05-27
    Omdannelse af Varmeenergi (DEN, 31737)              :active, p_int_57, 1922-03-31, 1923-05-08
    Flyvemaskine (DEN, 31663)                           :active, p_int_58, 1922-04-03, 1923-04-24
    Frembringelse mekanisk ved hjælp (NOR, 38426)       :active, p_int_175, 1922-04-01, 1923-11-26
    Utbalansera roterande maskindelar (SWE, 60297)      :active, p_int_189, 1922-09-01, 1926-02-23

    %% Patent below is no Filing, F set to G
    Anordning vid turbinaggregat (SWE, 60428)           :active, p_int_190_ano, 1926-03-23, 1926-03-23 

    Sistema e apparecchio (ITA, 269409)                 :active, p_int_165, 1928-04-30, 1929-11-19
```

-----

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
