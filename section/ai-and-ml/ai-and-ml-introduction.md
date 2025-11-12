# AI and Machine Learning Overview

## What is AI?

- Broad field focused on developing intelligent systems capable of performing tasks that typically require human intelligence
- **Core Capabilities**:
  - Perception: Understanding visual/audio data
  - Reasoning: Drawing logical conclusions
  - Learning: Improving from experience
  - Problem solving: Finding solutions to complex problems
  - Decision making: Choosing optimal actions
- Umbrella term encompassing various techniques and approaches
- **Common Use Cases**:
  - Computer vision for self-driving cars
  - Facial recognition
  - Fraud detection
  - Intelligent Document Processing (IDP)

![AI Hierarchy](../../images/artificial-intelligence.png)

## AI Components

- **Data Layer**: Collection and preparation
  - Collect vast amounts of high-quality data
  - Critical foundation for model performance
  - Data quality determines model quality

- **ML Framework and Algorithm Layer**: Strategy and design
  - Data scientists and engineers collaborate to understand:
    - Use cases and business requirements
    - Available frameworks and algorithms
    - Best approaches to solve the problem

- **Model Layer**: Implementation and training
  - Implement the model structure
  - Set parameters and configurations
  - Train the model using optimization functions
  - Tune and validate performance

- **Application Layer**: Deployment and serving
  - Deploy trained model to production
  - Expose model capabilities to end users
  - Monitor performance in real-world scenarios
  - Maintain and update as needed

![AI Components](../../images/ai-components.png)

## What is Machine Learning (ML)?

- Type of AI that enables systems to learn and improve from data without explicit programming
- Machines learn patterns from data rather than following programmed rules
- Build methods that allow machines to make predictions and decisions based on learned patterns
- Data-driven: Improves performance by processing large datasets
- Pattern recognition: Identifies patterns and relationships in data
- Predictive capability: Makes predictions on new, unseen data
- Non-programmatic: Learns without explicit rule programming
- **AI ≠ ML**: AI is broader, ML is one approach within AI
- Most modern AI systems leverage ML techniques

## What is Deep Leaning(DL)?

- Subset of machine learning inspired by the structure and function of the human brain
- Uses neurons and synapses (like the brain) to train models
- Processes more complex patterns than traditional ML techniques
- **Deep** refers to multiple layers of learning/hidden layers
- Handles more intricate relationships than traditional regression/classification
- Automatically extracts features without manual feature engineering
- Leverages increasing data and computational resources effectively
- **Key Requirements:**
  - **Large Datasets**: Needs substantial amounts of training data for good performance
  - **Computational Resources**: Training is computationally intensive, typically using GPUs (Graphics Processing Units)
  - **Time**: Training deep models requires significant time investment
- **Applications**
  - Computer Vision
    - Image classification: Categorizing images into classes
    - Object detection: Locating and identifying objects in images
    - Image segmentation: Partitioning images into meaningful regions
    - Facial recognition: Identifying faces in images
  - Natural Language Processing (NLP)
    - Text classification: Categorizing text documents
    - Sentiment analysis: Determining emotional tone of text
    - Machine translation: Translating between languages
    - Language generation: Creating human-like text

### Neural Networks - how do they work?

- Computational models composed of interconnected layers of nodes (neurons) that process and transform input data
- Processes input data through multiple layers, extracting features and making predictions
- Nodes are organized in layers
- When the neural network sees a lot of data, it identifies patterns and changes the connections between the nodes
- Nodes are **talking** to each other, by passing on (or not) data to the next layer
- The math and parameters tuning behind it is beyond the level of this course
- Neural networks may have billions of nodes

#### Layers

- **Input Layer**:
  - Receives raw input data
  - Each neuron represents one feature of input data
  - No processing occurs here

- **Hidden Layers**:
  - Intermediate layers between input and output
  - Multiple hidden layers create "deep" networks
  - Perform computations and extract features from input data
  - Different layers learn different levels of abstraction

- **Output Layer**:
  - Final layer producing the prediction or classification
  - Structure depends on task:
    - Regression: Single neuron with continuous output
    - Classification: Multiple neurons with probability outputs

## What is Generative AI?

- Generative AI is a branch of Deep Learning
- The idea is simple: you train a model on existing data, and it learns to create new data that looks similar
- Think of it like teaching someone to paint by showing them thousands of paintings
- Once trained, it can create brand new content that follows the same patterns

## What is the Transformer Model? (LLM)

- Architecture that processes entire sequences at once rather than sequentially word-by-word
- Revolutionary approach enabling efficient, parallel text processing
- Faster training and better handling of long-range dependencies
- Reduces training time significantly
- It gives relative importance to specific words in a sentence
- Scales well to large datasets and models
- Transformer-Based LLMs
  - Powerful models that can understand and generate human-like text
  - Trained on vast amounts of text data from the internet, books, and other sources, and learn patterns and relationships between words and phrases
  - **Examples**:
    - **Google BERT**: Bidirectional Encoder Representations from Transformers
    - **OpenAI ChatGPT**: Chat Generative Pre-Trained Transformer
  - Modern transformers can have billions of parameters
  - Can be adapted to many NLP tasks through fine-tuning

## Diffusion Models

- Used in machine learning, particularly for generating complex data such as images, audio, and even text
- Key concepts:
  - Generative Modeling: learn the underlying distribution of a dataset and generate new data points that are similar to the training data
  - Forward Diffusion Process: the diffusion process begins by gradually adding noise to the data (e.g., an image) over a series of steps until the data is completely transformed into noise
  - Reverse Diffusion Process: generative part of the model, where the goal is to start from pure noise and iteratively remove the noise, effectively reversing the forward diffusion process, to generate new data that resembles the original training data

## Multi-Modal Models

- Models that can process and generate multiple types of data simultaneously
- Handle diverse input and output formats in single model
- Combines information from different modalities for richer understanding
- Examples:
  - **Image + Audio → Video**: Take image of cat and audio file, generate video of cat speaking the audio
  - **Image → Text**: Analyze image and generate descriptive caption
  - **Text + Image → Text**: Analyze both and generate combined interpretation

## ML Terms You Need to Know

- **GPT (Generative Pre-trained Transformer)** – generate human text or computer code
based on input prompts
- **BERT (Bidirectional Encoder Representations from Transformers)** – similar intent to GPT, but reads the text in two directions
- **RNN (Recurrent Neural Network)** – meant for sequential data such as time-series or text, useful in speech recognition, time-series prediction
- **ResNet (Residual Network)** – Deep Convolutional Neural Network (CNN) used for image recognition tasks, object detection, facial recognition
- **SVM (Support Vector Machine)** – ML algorithm for classification and regression
- **WaveNet** – model to generate raw audio waveform, used in Speech Synthesis
- **GAN (Generative Adversarial Network)** – models used to generate synthetic data such as images, videos or sounds that resemble the training data. Helpful for data augmentation
- **XGBoost (Extreme Gradient Boosting)** – an implementation of gradient boosting
