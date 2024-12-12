# Paper to Podcast

## Overview
The **Paper to Podcast** project transforms academic research papers into engaging podcast scripts. This innovative solution leverages state-of-the-art AI technologies to simplify complex information and make it accessible to a broader audience. The project employs advanced multithreading, modular architecture, and tools such as LangGraph and GPT-4o-mini to deliver high-quality, ready-to-use podcast scripts.

## Key Features
- **Automated Workflow**: Extracts and processes research papers to generate podcast scripts seamlessly.
- **AI-Powered**: Utilizes GPT-4o-mini for text analysis and script generation.
- **Multithreaded Design**: Ensures optimal performance by handling concurrent tasks efficiently.
- **Flexible and Modular**: Supports customization for various podcast styles, languages, and research domains.

## How It Works
1. **Input**: Upload a research paper in PDF or other supported formats.
2. **Processing**:
   - Text extraction from the research paper.
   - Generation of a structured podcast plan.
   - Creation of an engaging introduction, detailed dialogues, and final script.
3. **Output**: A podcast-ready script that is easy to follow and share.

## Project Structure
- **`107_Paper_to_Podcast.ipynb`**: Main Jupyter Notebook containing the full implementation and workflow.
- **LangGraph Integration**: Facilitates the flow of data between processes.
- **Multithreading Module**: Ensures fast and scalable script generation.

## Usage Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/AaronSosaRamos/paper-to-podcast.git
   ```
2. Navigate to the project directory:
   ```bash
   cd paper-to-podcast
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook 107_Paper_to_Podcast.ipynb
   ```
4. Follow the steps outlined in the notebook to process your research paper and generate podcast scripts.

## Requirements
- Python 3.10 or higher
- Required Python libraries (listed in `requirements.txt`). Some of them are:
  - `langgraph`
  - `langchain`
  - `openai`
  - `chromadb`

## Key File
[107_Paper_to_Podcast.ipynb](https://github.com/AaronSosaRamos/paper-to-podcast/blob/main/107_Paper_to_Podcast.ipynb): The primary notebook demonstrating the end-to-end workflow.

## Example Output
After processing a research paper, the system generates:
- A structured podcast plan
- Section-wise dialogues with smooth transitions
- A cohesive conclusion with optional call-to-action elements

## Contributing
Contributions are welcome! If you have ideas for improvement or additional features, feel free to create a pull request or open an issue.

## Acknowledgments
Special thanks to the developers of LangGraph, GPT-4o-mini, and the open-source community for making this project possible.
