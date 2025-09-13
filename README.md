# Data Science & API Integration Portfolio

This repository contains two Jupyter notebooks demonstrating my expertise in natural language processing, topic modeling, and API integration for social media analytics.

## Projects Overview

### 1. BERTopic Implementation for Healthcare Text Analysis
**File:** `simple_BERT_4Health.ipynb`

A comprehensive implementation of BERTopic for topic modeling specifically tailored for healthcare and medical text analysis.

#### Key Features:
- **Medical Domain Specialization**: Uses `abhinand/MedEmbed-large-v0.1` embedding model optimized for medical vocabulary
- **Advanced Topic Modeling**: Combines BERT embeddings with UMAP dimensionality reduction and HDBSCAN clustering
- **Flexible Configuration**: Tunable parameters for different dataset sizes and topic granularity
- **OpenAI Integration**: Optional GPT-powered topic naming and description generation
- **Scalable Architecture**: Memory-efficient processing with configurable batch sizes

#### Technical Stack:
- **Embeddings**: SentenceTransformers with medical domain model
- **Dimensionality Reduction**: UMAP with cosine similarity
- **Clustering**: HDBSCAN with configurable density parameters
- **Vectorization**: TF-IDF with n-gram support (1-3 grams)
- **Topic Representation**: ClassTfidfTransformer for keyword extraction

#### Use Cases:
- Medical literature analysis
- Patient feedback categorization
- Healthcare social media monitoring
- Clinical trial text mining

---

### 2. Brandwatch Consumer Research API Integration
**File:** `BW_API_DEMO.ipynb`

A complete demonstration of the Brandwatch Consumer Research API Python client library, showcasing enterprise-level social media analytics capabilities.

#### Key Features:
- **Comprehensive API Coverage**: Full implementation of Brandwatch's REST API endpoints
- **Resource Management**: Automated handling of queries, groups, categories, tags, and rules
- **Authentication**: Secure token-based authentication with credential management
- **Batch Operations**: Efficient bulk upload/download operations for large-scale data processing
- **Advanced Filtering**: 100+ filter options for precise mention targeting
- **Real-time Analytics**: Chart generation and sentiment analysis capabilities

#### Core Functionalities:

**Query Management:**
- Create, modify, and delete social media queries
- Batch query operations for efficiency
- Automated query validation

**Data Collection & Analysis:**
- Mention extraction with advanced filtering
- Sentiment analysis and impact scoring
- Geographic and demographic filtering
- Time-series data aggregation

**Classification Systems:**
- Hierarchical category management
- Custom tagging with rule-based automation
- Author and site list management
- Location-based filtering

**Automation & Rules:**
- Automated content classification
- Priority scoring systems
- Custom alert configurations
- Bulk mention processing

#### Technical Highlights:
- **Error Handling**: Robust error management with detailed logging
- **Rate Limiting**: Built-in API rate limit compliance
- **Data Validation**: Automatic parameter validation and sanitization
- **Scalable Architecture**: Designed for enterprise-level data volumes

---

## Technical Skills Demonstrated

### Machine Learning & NLP:
- Topic modeling with BERTopic
- Transformer-based embeddings
- Unsupervised clustering algorithms
- Text preprocessing and vectorization
- Medical domain NLP expertise

### API Development & Integration:
- RESTful API client development
- OAuth authentication implementation
- Batch processing optimization
- Error handling and logging
- Documentation and testing

### Data Engineering:
- Large-scale data processing
- Memory-efficient algorithms
- Real-time data streaming
- Data validation and cleaning
- Pipeline automation

### Software Engineering:
- Object-oriented programming
- Design patterns implementation
- Configuration management
- Logging and monitoring
- Code documentation

## Applications & Impact

These projects demonstrate capabilities relevant to:
- **Healthcare Analytics**: Medical text mining and patient feedback analysis
- **Social Media Intelligence**: Brand monitoring and sentiment tracking
- **Market Research**: Consumer behavior analysis and trend identification
- **Content Strategy**: Automated content categorization and insights
- **Risk Management**: Real-time monitoring and alert systems

## Getting Started

Each notebook includes:
- Detailed setup instructions
- Required dependencies
- Configuration examples
- Sample data and outputs
- Best practices documentation

## Contact

For questions about implementation details, potential collaborations, or discussing these projects further, please feel free to reach out : christian_said@outlook.fr

---

*These projects showcase practical applications of advanced NLP techniques and enterprise API integrations, demonstrating both technical depth and real-world applicability in data science and social media analytics.*
