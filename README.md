# MCM Mathematical Contest in Modeling

***2024 MCM/ICM Contest Link:** [2024 MCM/ICM problems](https://www.comap-math.com/mcm/index.html)*

**Our paper:** [ICM-paper.pdf](https://github.com/unicorn-yh/MCM-Mathematical-Contest-in-Modeling/blob/main/paper/paper.pdf)

**Problem A Selected:**  [2024 ICM Problem E.pdf](https://github.com/unicorn-yh/MCM-Mathematical-Contest-in-Modeling/blob/main/problem/2024_ICM_Problem_E_FINAL.pdf)

**Topic:** Problem E - Sustainability of Property Insurance

<br>

### **Index:**

1. [Overview](https://github.com/unicorn-yh/MCM-Mathematical-Contest-in-Modeling/tree/main#overview)
2. [Develop a Property Insurance Model](https://github.com/unicorn-yh/MCM-Mathematical-Contest-in-Modeling/tree/main#develop-a-property-insurance-model)
3. [Application of the Insurance Model](https://github.com/unicorn-yh/MCM-Mathematical-Contest-in-Modeling/tree/main#application-of-the-insurance-model)
4. [Assess Real-Estate Building Decisions](https://github.com/unicorn-yh/MCM-Mathematical-Contest-in-Modeling/tree/main#assess-real-estate-building-decisions)
5. [Develop a Presevation Model](https://github.com/unicorn-yh/MCM-Mathematical-Contest-in-Modeling/tree/main#develop-a-preservation-model)
6. [Select a Historic Landmark](https://github.com/unicorn-yh/MCM-Mathematical-Contest-in-Modeling/tree/main#select-a-historic-landmark)
7. [Apply Insurance and Preservation Models](https://github.com/unicorn-yh/MCM-Mathematical-Contest-in-Modeling/tree/main#apply-insurance-and-preservation-models)
8. [Compose a Recommendation Letter](https://github.com/unicorn-yh/MCM-Mathematical-Contest-in-Modeling/tree/main#compose-a-recommendation-letter)

<br>

## Overview

   #### **1. Main task**

1. **Develop a Property Insurance Model**: Create a model for insurance companies to determine if they should underwrite policies in areas with rising numbers of extreme weather events. This model should help decide when and under what conditions to take the risk of underwriting.

2. **Application of the Insurance Model**: Demonstrate the developed insurance model using two geographical areas on different continents that experience extreme weather events.

3. **Assess Real-Estate Building Decisions**: Adapt the insurance model to evaluate where, how, and whether to build on certain sites, ensuring that future real estate decisions make properties more resilient.

4. **Develop a Preservation Model**: Create a model for community leaders to use in determining the extent of measures necessary to preserve buildings in their community, especially those with cultural, historical, economic, or community significance.

5. **Select a Historic Landmark**: Choose a historic landmark (other than Cape Hatteras Lighthouse) located in a place prone to extreme weather events.

6. **Apply Insurance and Preservation Models**: Use the developed models to assess the value and risk associated with the selected historic landmark.

7. **Compose a Recommendation Letter**: Write a one-page letter to the community outlining a plan, timeline, and cost proposal for the future of their treasured landmark, based on insights from the insurance and preservation models.

<br>

## Develop a Property Insurance Model

The objective of this model was to design an easy-to-use index that is capable of grading a city’s property insurance development based on basic principles of sustainability. The model incorporates the four principles of sustainable insurance, which include the ESG of sustainability (environmental sustainability, governance regulations, and social equity), into seven unique metrics based on the intersectionality of core ideas. Five metrics and two indicators analyze a city’s financial and pricing, policy support, customer risk engagement metric, geographic climate risk, renters’ preference, investor intention, and natural disaster risk. These metrics, derived from widely available data, are combined into the Sustainable Property Insurance Index (SPII), which provides a comprehensive assessment for any developed city.

#### Principles for Sustainable Insurance

The United Nations Environment Programme Finance Initiative's Principles for Sustainable Insurance offer a worldwide blueprint for the insurance sector to effectively manage and leverage risks and opportunities associated with environmental, social, and governance issues.

The four basic principles founded by this UNEP FI (Principles for Sustainable Insurance, 2012) are as follow:

1. Embedding Environmental, Social and Governance (ESG) issues into Decision-making.
2. Working with clients and business partners to raise awareness of ESG issues, manage risks, and develop solutions.
3. Working with governments, regulators, and other key stakeholders to promote widespread action across society on ESG issues in insurance.
4. Demonstrating accountability and transparency in regularly disclosing the progress in implementing the Principles.



## **Application of the Insurance Model**

New York (United States) and Athens (Greece) were analyzed with the insurance model to serve as regional benchmarks. These cities were chosen because they currently incorporate sustainable insurance principles into their city property insurance plans. The proposed initiatives in the model were specifically aimed at improving each city’s overall SPII score. Initially, both cities scored well, with SPII scores of 352.18 for New York and 312.17 for Athens, indicating strong foundations in sustainable property insurance development.

<div style="text-align: center;">
    <img src="./assets/Sustainable Insurance Index Model.png" alt="Sustainable Insurance Index Model" width="600px">
    <p><em>Fig 1. Sustainable Insurance Index Model</em></p>
</div>



This model generates a total score for the **Sustainable Property Insurance Index (SPII)**, which is evaluated on a scale from 0 to 700, with less than 700 representing the optimal standard of sustainable insurance practices. This comprehensive SPII** score compiles the individual scores from the previously outlined seven metrics.


$$
\begin{split}
\text{SPII} =\ & \text{Financial and Pricing + Policy Support + Customer Engagement Risk } -
\\ & \text{Geographic Climate Resilience + Renters' Preference +  Investor Intention}  
\\ & +  \text{Natural Disasters}    
\end{split}
$$


## **Assess Real-Estate Building Decisions**

Our model aids in assessing real estate building decisions by providing a comprehensive analysis of potential risks and opportunities within the property market. It examines key factors such as market trends, regulatory environments, and economic conditions, offering investors and developers insights into making informed decisions. By evaluating the impact of various scenarios on property values and investment returns, this model serves as a crucial tool in strategic planning and risk management in the real estate sector.



## Develop a Preservation Model

We propose a Historical Preservation Index (HPI) model that aims to evaluate and enhance the conservation efforts of urban historic buildings. The model considers various dimensions, including value assessment, risk evaluation, prioritization, cost-benefit analysis, and multi-objective optimization. It provides a systematic framework to support community leaders and stakeholders in making informed decisions about preserving cultural heritage while considering economic and social impacts.

<div style="text-align: center;">
    <img src="./assets/Historical Preservation Index Model.png" alt="Historical Preservation Index Model" width="600px">
    <p><em>Fig 2. Historical Preservation Index Model</em></p>
</div>

By grouping **Principles for Sustainable Insurance** together, **four metrics can be created**: cultural value, economic contribution, vulnerability assessment, and protection cost. For the remainder of this report these metrics will be referred to as: ***Cultural Value, Economic Value, Vulnerability Cost, Protection Cost***. The four principles of Sustainable Insurance were categorized into four metrics which were used to determine how urgent a city is needed for historic preservation (Fig 2).

This model outputs a cumulative Historic Preservation Index (HPI) value that ranges across a traditional grading system of 0-100 (where 100 is the highest possible level of urgency in historic preservation). This HPI value is the sum of scores from the four metrics mentioned previously:

$$
\text{HPI = Cultural Value }+ \text{Economic Value} - \text{Vulnerability Cost }- \text{Protection Cost}
$$


## **Select a Historic Landmark**

Through the analysis of historic sites like the Acropolis and the Ancient Agora in Athens (Greece), the HPI model demonstrates how conservation planning can be guided by the cultural and economic value of historic buildings. The model provides a practical and flexible tool for protecting urban historic buildings, ensuring that the preservation efforts are sustainable and contribute to the overall cultural heritage of the city.



## **Apply Insurance and Preservation Models**

The combination of the Sustainable Property Insurance Index (SPII) and the Historical Preservation Index (HPI) offers a comprehensive approach to both property insurance development and historic preservation. By integrating these models, cities can enhance their resilience against risks while preserving their cultural heritage. This dual approach ensures that urban development is both sustainable and respectful of historical landmarks.



## **Compose a Recommendation Letter**

In recommending the adoption of these models, the focus would be on their practical application and proven effectiveness in real-world scenarios. The SPII and HPI models provide clear, actionable insights that can guide policymakers and community leaders in making informed decisions. By adopting these models, cities can improve their property insurance systems and heritage preservation strategies, leading to more resilient and culturally rich urban environments.



