## Topic Modeling of McDonald’s Customer Reviews

This project aimed to extract meaningful insights from McDonald's customer reviews using Natural Language Processing (NLP) and topic modeling techniques. The primary goal was to observe common themes in customer feedback that can inform business decisions related to service quality, customer satisfaction, and operational improvements.

### Objectives
- Analyze textual reviews of McDonald’s locations to identify recurring topics.
- Compare different topic modeling approaches (LDA and NMF).
- Recommend the most interpretable and actionable model for real-world application.

### Methodology
- **Data Preparation**: Preprocessed reviews by removing noise, tokenizing, lemmatizing, and filtering stopwords.
- **Modeling**: Applied two topic modeling algorithms:
  - **Latent Dirichlet Allocation (LDA)** with 6 topics.
  - **Non-negative Matrix Factorization (NMF)** with 7 topics.
- **Evaluation**: Compared both models based on coherence, topic interpretability, and business relevance.

### Key Findings
- The **LDA model with 6 topics** provided the most coherent and distinguishable themes:
  1. **Drive-Thru Experience** (wait times, opening hours)
  2. **Positive Feedback** (good food, friendly staff)
  3. **Order Delays and Complaints** (slow service, miscommunication)
  4. **Food Items and Preferences** (fries, chicken, sandwiches)
  5. **Negative Experiences** (rude staff, bad service)
  6. **Brand and Family Environment** (mentions of McDonald’s brand, kids, area)

- The NMF model, while reasonably structured, showed more topic overlap and less distinct segmentation, making LDA a more practical choice.

### Conclusion
The LDA model successfully uncovered six dominant themes in customer reviews that can guide improvements in:
- Drive-thru operations
- Customer service training
- Product consistency and quality control

These insights offer actionable direction for enhancing customer experience and maintaining McDonald’s brand reputation.
