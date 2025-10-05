# modern-corsetry
Trial of a personnal idea: why not combine 3D printing and AI with the historical corstetry knowledge, to make back braces more comfortable for teenagers having scoliosis ? 
*Disclaimer* This work has absolutely no intention to help generate custom corset pattern for fashion purposes. Corsetry, in a fashion context, has an essential element of artistry in it, which cannot (and should not) be emulated by means of artificial intelligence.

## Introduction
As it is, back braces are made using a 3D scan of the body, and medical input from the specialist, tellng where there should be force applied in which direction. A resin brace is then made, with more foam applied inside where there should be pressure, and a hole in the resin where the body should move. These are quite uncomfortable, as well as not sustainable at all. The goal here would be to use the same inputs, but to produce a back brace inspired by historical corsetry. Corsets are comfortable if made to measure, and offer more body movement than a resin brace. Using steel boning in strategic points could possibly help achieve the desired pressure points. This method would have the huge drawback of needing sewing, making it time-consuming and expensive. Additive fabrication could be a direction to explore to solve the issue of sewing.
<img width="973" height="286" alt="image" src="https://github.com/user-attachments/assets/1ddfef75-f848-4540-bd51-62cc3f1a9f94" />

From the body measurements and a defined corset pattern, we can theoretically compute the displacement of the bones through finite elements simulation. Then, our problem becomes an inverse problem, where we want to compute the pattern based on the body displacement we want to achieve.
<img width="1344" height="401" alt="image" src="https://github.com/user-attachments/assets/8188bc15-5801-4303-9b7a-2e4e947df659" />

We can also see the problem from an optimization point of view, where the challenge then lies in defining the cost function.
<img width="1282" height="482" alt="image" src="https://github.com/user-attachments/assets/deebc1f9-d08f-4688-94a2-f1e4618740cd" />


## Simulation
The first step is thus to work out how to implement such a finite elements analysis. We shall then take a look at fabric simulations techniques, as well as human body simulation techniques.
### Fabric simulation

### Human body simulation

