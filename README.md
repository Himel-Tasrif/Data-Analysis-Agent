# Data Analysis Agent

An interactive, agentic data analysis application that leverages advanced LLM reasoning to help users explore, visualize, and understand their data using NVIDIA Llama-3.1-Nemotron-Ultra-253B-v1.

## Overview

This repository contains a Streamlit application that demonstrates a complete workflow for data analysis:
1. **Data Upload**: Upload CSV files for analysis
2. **Natural Language Queries**: Ask questions about your data in plain English
3. **Automated Visualization**: Generate relevant plots and charts
4. **Transparent Reasoning**: Get detailed explanations of the analysis process

The implementation leverages the powerful Llama-3.1-Nemotron-Ultra-253B-v1 model through NVIDIA's API, enabling sophisticated data analysis and reasoning.

## Features

- **Agentic Architecture**: Modular agents for data insight, code generation, execution, and reasoning
- **Natural Language Queries**: Ask questions about your data—no coding required
- **Automated Visualization**: Instantly generate and display relevant plots
- **Transparent Reasoning**: Get clear, LLM-generated explanations for every result
- **Powered by NVIDIA Llama-3.1-Nemotron-Ultra-253B-v1**: State-of-the-art reasoning and interpretability

![Workflow](./assets/workflow.png)

## Requirements

- Python 3.10+
- Streamlit
- NVIDIA API Key (see [Installation](#installation) section for setup instructions)
- Required Python packages:
  - pandas
  - matplotlib
  - streamlit
  - requests

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/Himel-Tasrif/Data-Analysis-Agent.git
   cd Data-Analysis-Agent
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up your NVIDIA API key:
   - Sign up or log in at [NVIDIA Build](https://build.nvidia.com/nvidia/llama-3_1-nemotron-ultra-253b-v1?integrate_nim=true&hosted_api=true&modal=integrate-nim)
   - Generate an API key
   - Set the API key in your environment:
     ```bash
     export NVIDIA_API_KEY=your_nvidia_api_key_here
     ```
   - Or add it to your `.env` file if you use one

## Usage

1. Run the Streamlit app:
   ```bash
   streamlit run agent.py
   ```

2. Download example dataset (optional):
   ```bash
   wget https://github.com/Himel-Tasrif/Machine-Learning/blob/main/scikit-learn%20Models/titanic.csv
   ```

3. Use the application:
   - Upload a CSV file (e.g., the Titanic dataset)
   - Ask questions in natural language
   - View results, visualizations, and detailed reasoning

## Example

![App Demo](./assets/himel.png)

## Model Details

The Llama-3.1-Nemotron-Ultra-253B-v1 model used in this project has the following specifications:
- **Parameters**: 253B
- **Features**: Advanced reasoning capabilities
- **Use Cases**: Complex data analysis, multi-agent systems
- **Enterprise Ready**: Optimized for production deployment

## Acknowledgments

- [NVIDIA Llama-3.1-Nemotron-Ultra-253B-v1](https://build.nvidia.com/nvidia/llama-3_1-nemotron-ultra-253b-v1)
- [Streamlit](https://streamlit.io/)
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)


## Contributing

Contributions are welcome! Please open an issue or submit a pull request.
