---
created: 2025-06-17 05:31:26
author: Cong Le
version: "1.0"
license(s): MIT, CC BY-SA 4.0
copyright: Copyright (c) 2025 Cong Le. All Rights Reserved.
source: https://www.energy.gov/articles/war-currents-ac-vs-dc-power
---


> ⚠️🏗️🚧🦺🧱🪵🪨🪚🛠️👷
> 
> This is a working draft in progress
> 
> ![Loading...](https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExaHRtYThreWdkdnI1Z3hzY3h4eHI2cWU3cjVyMzA0ZDZrenBtN2YzNSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/dnoyd6rMvw29q/giphy.gif)
>
> gif image is provided by [Giphy](https://giphy.com)
> 
> ⚠️🏗️🚧🦺🧱🪵🪨🪚🛠️👷


----




# The War of the Currents: AC vs DC Power
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


## MAIN CONTENT - A Diagrammatic Guide 


```mermaid
---
title: "🔋🥊💡...The War of the Currents: AC vs DC Power...🔋🥊💡"
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
    'fontFamily': 'American TypeWriter',
    'themeVariables': {
      'primaryColor': '#fc82',
      'primaryTextColor': '#F8B229',
      'primaryBorderColor': '#27AE60',
      'secondaryColor': '#5229',
      'secondaryTextColor': '#6C3483',
      'lineColor': '#F8B229',
      'fontSize': '25px'
    }
  }
}%%
flowchart TD
  Nikola_Tesla@{ img: "https://raw.githubusercontent.com/CongLeSolutionX/Nikola_Tesla/refs/heads/main/ASSETS/Nikola_Tesla.jpg", label: "⚡...Nikola Tesla...🧲", pos: "b", w: 700, h: 500, constraint: "on" }

  Thomas_Alva_Edison@{ img: "https://raw.githubusercontent.com/CongLeSolutionX/Nikola_Tesla/refs/heads/main/ASSETS/Thomas_Alva_Edison.jpg", label: "💡...Thomas Alva Edison...🪫", pos: "b", w: 700, h: 500, constraint: "on" }
  
  VS["🔔🗽🔔🗽🔔"]

  TeslaImage("🖼️ Portrait of Nikola Tesla<br/><br/>Source:<br/> <em>Nikola Tesla, Pioneer in Experiments on High Frequency Oscillations. n.d. Wellcome Collection. <a href='https://jstor.org/stable/community.36635498'>https://jstor.org/stable/community.36635498</a></em>")

  EdisonImage("🖼️ Portrait of Thomas Alva Edison<br/><br/>Source:<br/> <em>Thomas Alva Edison. Photograph. n.d. 1 photograph. Wellcome Collection. <a href='https://jstor.org/stable/community.24859005'>https://jstor.org/stable/community.24859005</a></em>")

  Nikola_Tesla animatingEdge1@ ===VS
  Thomas_Alva_Edison animatingEdge2@ ===VS
  animatingEdge1@{ animate: true }
  animatingEdge2@{ animate: true }

  TeslaImage <===> Nikola_Tesla

  EdisonImage <===> Thomas_Alva_Edison

  %% subgraph The_Fight["The fight between the AD and DC Power"]
  %% direction LR
  %%   Nikola_Tesla animatingEdge1@ ----VS
  %%   Thomas_Alva_Edison animatingEdge2@ ----VS

  %%   animatingEdge1@{ animate: true }
  %%   animatingEdge2@{ animate: true }

     
    
  %%   TeslaImage --> Nikola_Tesla

  %%   Thomas_Alva_Edison --> EdisonImage

  %% end


```


----

```mermaid
---
title: "❓...CongLeSolutionX....❓"
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
      'secondaryColor': '#5229',
      'secondaryTextColor': '#6C3483',
      'lineColor': '#F8B229',
      'fontSize': '20px'
    }
  }
}%%
flowchart LR
    My_Meme@{ img: "https://raw.githubusercontent.com/CongLeSolutionX/CongLeSolutionX/refs/heads/main/assets/images/My-meme-and-question-marks-open-book-old-characters-background.png", label: "..🙉..👀..📖..", pos: "b", w: 200, h: 150, constraint: "off" }
   
    Link_to_my_profile{{"<a href='https://github.com/CongLeSolutionX' target='_blank'>Click here if you care about my profile</a>"}}

  Closing_quote@{ shape: braces, label: "..."}

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
