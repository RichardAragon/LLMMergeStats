# LLMMergeStats

LLM Merge Stats is an open-source Python application designed to help you compare and analyze two language models (LLMs) to determine if they should be merged. This tool provides a comprehensive set of metrics and visualizations to give you insights into the similarities and differences between the models.

Features
Compare model architectures, activation functions, and hidden sizes
Analyze vocabulary sizes and overlap between the models
Compare parameter counts and model sizes
Benchmark inference speed for each model
Visualize layer-wise hidden sizes
Installation
Clone the repository:

Copy code
git clone https://github.com/RichardAragon/llm-merge-stats.git
Install the required dependencies:

Copy code
pip install -r requirements.txt
Usage
Run the llm_merge_stats.py script and follow the prompts to enter the names of the two models you want to compare:


Copy code
python llm_merge_stats.py
The script will output various metrics and visualizations to help you assess the compatibility and potential benefits of merging the two models.

Requirements
Python 3.7 or higher
PyTorch
Transformers
Matplotlib
Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

License
This project is licensed under the MIT License.

Acknowledgements
This project utilizes the Transformers library by Hugging Face.
We would like to thank the open-source community for their valuable contributions and inspiration.
