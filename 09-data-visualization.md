## Data Visualization Analysis Based on Explainable Artificial Intelligence: A Survey
*paper review*

### Research Question/Goal : 
How does AI enhance data visualization by automating data preprocessing, identifying hidden patterns, recommending appropriate visualizations, enabling natural language interaction, supporting real-time data visualization, and generating predictive visualizations? 


### AI Tools Researched
#### Data2Vis:
Data2Vis treats the data visualization recommendation task as a sequence-to-sequence translation task, providing insights into automated visualization generation based on bidirectional recurrent neural networks (BiRNN).

#### VizML:
VizML considers numerous data features relevant to visualization design, offering a broader perspective on how neural network models can learn automatic visualization recommendations from millions of real-world data.

#### Table2Charts:
Table2Charts supports rendering final results in various visual languages, making it a versatile tool for understanding data-to-visual template transformation through deep Q-learning.

#### SEQ2VIS:
SEQ2VIS uses a natural language query sequence as input, producing data visualization query language outputs, providing a practical application of deep learning for visual recommendation systems.

#### Dziban:
Dziban considers the properties of anchor visualization results when recommending current visualizations, helping in understanding continuous visual recommendation.



### Implementation & Testing
#### Data2Vis:

- **Successes**: Efficient in generating visualization sequences from data sequences. Demonstrated the potential of sequence-to-sequence models for visualization recommendations.
- **Challenges**: Limited interpretability and generalization, restricted to Vega-Lite visual syntax.

#### VizML: 
- **Successes**: Successfully recommended visualization spaces based on extensive data features. Demonstrated high scalability with millions of real-world visualization data.
- **Challenges**: Only considered two types of visualization tasks, lacking comprehensive recommendation capabilities.

#### Table2Charts: 
 - **Successes**: Versatile in rendering results across different visual languages. Utilized deep Q-learning effectively for template generation.
- **Challenges**: Complex learning curve for users unfamiliar with deep Q-learning mechanisms.

#### SEQ2VIS: 
- **Successes**: Provided an end-to-end deep learning-based visual recommendation system. Integrated user analysis intent seamlessly.
- **Challenges**: Required extensive computational resources for training and evaluation.

#### Dziban: 
- **Successes**: Effectively recommended visualizations considering anchor visualization properties. Improved user understanding by maintaining consistency in visual recommendations.
- **Challenges**: Computational complexity in processing similarity algorithms and partial data queries.



### Evaluation of Tools
#### Data2Vis: 
High efficiency in generating visualization sequences but limited by poor generalization and interpretability.
#### VizML: 
Excellent scalability and feature consideration but restricted in the diversity of visualization tasks.
#### Table2Charts: 
Versatile and effective in template rendering, yet challenging in user adoption due to deep learning complexity.
#### SEQ2VIS: 
Robust integration of user intent with high computational demands, making it less accessible for small-scale projects.
#### Dziban: 
Improved consistency in visual recommendations with significant computational overhead for similarity processing.




### Conclusion
AI significantly enhances data visualization by automating complex tasks, identifying patterns, and providing real-time and predictive visualizations. Tools like Data2Vis, VizML, Table2Charts, SEQ2VIS, and Dziban demonstrate the potential of AI to simplify and enrich data visualization processes. However, challenges such as computational complexity, limited interpretability, and user adoption barriers need to be addressed. The ethical implications of AI in data visualization, including data privacy and algorithmic bias, must also be considered. Overall, AI holds tremendous promise in making data visualization more accessible, efficient, and insightful.

Reference
Yin, S., Li, H., Sun, Y., Ibrar, M., & Teng, L. (2024). Data visualization analysis based on explainable artificial intelligence: A survey. *IJLAI Transactions on Science and Engineering, 2*(2), 13–20. Retrieved from https://ijlaitse.com/index.php/site/article/view/34


