# Team S.A.M

## Members  
- Akash Cuntur Shrinivasmurthy  
- Swathi Chandrashekaraiah  
- Madhukar Devendrappa  
- Bekzod Nazarov  

---

## Project Overview  
This project involves training a custom GPT model using two tokenizer approaches:  

1. **Word-Based Tokenizer**: A tokenizer that segments text into individual words, allowing for a vocabulary tailored to the dataset.  
2. **GPT-2 BPE Tokenizer**: A byte-pair encoding (BPE) tokenizer used in GPT-2, designed to handle subword units and optimize tokenization for neural networks.  

The training process is recorded and visualized using TensorBoard, ensuring transparency and detailed monitoring of model performance. The following notebook includes:  

- **Data Processing**: Steps to preprocess and tokenize the dataset.  
- **Model Training**: Training the custom GPT model using the two tokenizer approaches.  
- **Model Inference Script**: A script to load and run the trained model for inference tasks.  

---

## Project Structure  

- **Notebook**: Contains the complete workflow for preprocessing, training, and inference.  
- **TensorBoard Logs**: Training logs are saved in the `./runs` directory and can be visualized using TensorBoard.  
- **Model Checkpoints**: Saved checkpoints are located in the `./checkpoint` directory for resuming training or inference.  

---

## Prerequisites  

We recommend using the Docker image available at:  
[Trends of AI Docker Image](https://hub.docker.com/r/fhdo4/trends-of-ai)  

This image includes:  
- Jupyter Notebook  
- Required libraries and dependencies for the project  

---

## Getting Started  

**Clone the Repository**:  
   ```bash
   git clone https://github.com/madhukar-d20/trends-of-ai.git
   cd project-name
 ```

 **Run the Docker Image**
Follow instructions in [Trends of AI Docker Image](https://hub.docker.com/r/fhdo4/trends-of-ai)  

**Alernatively**
Use google colab or local instance of Jupyter Notebook