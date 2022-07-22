---
marp: true
theme: cuni                
_class:   
    - lead     
footer: "21.07.2022 | GKR: Journey to NIZK, Final Presentation | Ilia Zavidnyi & Svetlana Ivanova"   
_footer: ""                   
paginate: true            
_paginate: false    
math: katex    
---
<style>
    em {
        color: #FF55A3;
        }

    section h1,
    section a,
    section footer,
    section::after {
        color: #FF55A3;
    }
</style>

# GKR: Journey to NIZK Final presentation

<br>

*Ilia Zavidnyi* & *Svetlana Ivanova*
mentored by *Marshall Ball*
<br>
This presentation is part of a project that has received funding from the European Union’s Horizon 2020 research and innovation programme under the Marie Sklodowska-Curie grant agreement No. 823748.


![bg cover right:47%](../intro/eu-flag.jpeg)


---
# Proof system

![center 90p](prover-verifier.png)

---

# Non-interactivity via Fiat-Shamir

![center 85p](non-interactivity.png)

---

# Classical <br>Zero-knowledge

Verifier learns no information he can't *efficiently* compute himself.

This is formalised by showing that verifier has a *simulator* which can simulate prover-verifier interaction **in polynomial time**.



![bg right contain 70%](simulator.png)

---

![bg contain top](zkinp.png)

---


# GKR

*G*oldwasser, *K*alai, and *R*othblum described a interactive proof protocol which allows verifier to solve most problems in $\mathsf{P}$ **much** faster than it would be possible without prover.

Specifically, in **quasi-linear** time doing little more than reading the input.

![center w:800px](boolean.png)


---

# Precise <br>Zero-knowledge

Verifier learns no information he can't *efficiently* compute himself.

This is formalised by showing that verifier has a *simulator* which can simulate prover-verifier interaction **in time proportional to verifier's runtime**.



![bg right contain 70%](simulator.png)

---

# How to construct precise NIZK from GKR?

![center 60p](step1.png)

---

# How to construct precise NIZK from GKR?

![center 60p](step2.png)

---

# How to construct precise NIZK from GKR?


![center 60p](step3.png)

---

# How to construct precise NIZK from GKR?


![center 60p](step4.png)

---

# Thank you for attention!

![bg contain](sticker.webp)