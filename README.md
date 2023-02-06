# Causal-inference-in-building-design
Open source code of paper: <br>
*Introducing causal inference in the energy-efficient building design process*<br>
Paper: 
- [https://www.sciencedirect.com/science/article/pii/S037877882200754X](https://www.sciencedirect.com/science/article/pii/S037877882200754X)
- [http://arxiv.org/abs/2203.10115](https://arxiv.org/abs/2203.10115)


<p align="center">
  <img width=400 src="https://user-images.githubusercontent.com/106488602/176478089-3f6e2bb8-3435-4c28-abce-56f04d69e51e.png" alt="">
</p>


For running the code, please run notebook `Causal Inference in Energy-efficient Building Design Scenario.ipynb`<br>

Additional python packages required:
- sklearn
- IPython
- lightgbm
- dowhy
- statsmodels
- pygraphviz
- cdt
- networkx

[R language](https://www.r-project.org/) is required to run `cdt` package.

For using the code or data, please cite:<br>

- *Chen, X., Abualdenien, J., Singh, M. M., Borrmann, A., & Geyer, P. (2022). Introducing causal inference in the energy-efficient building design process. Energy and Buildings, 277, 112583. https://doi.org/10.1016/j.enbuild.2022.112583*

---

<p align="center">
  <img src="https://user-images.githubusercontent.com/106488602/176448570-b6b547ea-5d05-4152-97c1-33e9cb216ca0.png" alt="">
</p>

*The four-step framework implementation of causal inference in the building design process*

---

<p align="center">
  <img src="https://user-images.githubusercontent.com/106488602/176448683-3a4fd905-7889-4050-aad7-99431bb876c7.png" alt="">
</p>

*Causality-informed assistance case in data-driven building energy demand estimation. The data-driven model stands for the ML/AI monolithic method, in which the causal structure helps to provide insights into input dependencies and, by controlling them accordingly, to generate unbiased outcomes.*

---

<p align="center">
  <img src="https://user-images.githubusercontent.com/106488602/176448893-df0afa7e-4545-49a2-91b0-acde3be27123.png" alt="">
</p>

*Causal structure finding: knowledge extraction from data in the building early design phase. Subfigure (a) describes the data generation process: Via knowledge-based simulations or real-world data collection, causal relationships have been implicitly encoded in the dataset. Subfigure (b): the mechanism of the causal structure finding algorithm is designed to extract casual relationships directly from data and can be further transferred into DAGs. In the skeleton, arrows in bold represent the atomic direct effects, which means removing one of these arrows from the diagram implies that there will no longer be any causal effect between the corresponding variables.*

---


<p align="center">
  <img src="https://user-images.githubusercontent.com/106488602/176449028-fc96e118-eb21-46da-b4ae-7cd9ec561ad6.png" alt="">
</p>

*Causal effect estimation result.*

---
