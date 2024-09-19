# Gemma-2-Finetuning
Welcome to the GEMMA Fine-Tuning project! This repository provides a comprehensive guide to fine-tuning a pre-trained GEMMA model for various tasks using PyTorch. By leveraging advanced techniques in deep learning, you can adapt the model to your specific needs, whether for text classification, sentiment analysis, or other NLP applications.

<a name="readme-top"></a>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
   <li><a href="#built-with">Built With</a></li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project
The GEMMA Fine-Tuning project aims to provide users with the tools necessary to customize and optimize a pre-trained Google's latest GEMMA model (as per September, 2024) for their unique datasets. By following the structured approach outlined in this repository, users can enhance model performance and achieve better results in their specific applications.

## Built With
This project is built using the following technologies:
### Programming Language: 
Python
### Libraries: 
PyTorch, Transformers, Datasets, bitsandbytes, peft, trl, torch, google.colab, AutoTokenizer, AutoModelForCausalLM, BitsAndBytesConfig, GemmaTokenizer.

<!-- GETTING STARTED -->
## Getting Started
This section will guide you through configuring this project on your local machine and running the fine-tuning process effectively.
### Prerequisites
To run this project, ensure that your PC/Laptop has the following prerequisites:
- Python (version 3.8 or later)
- An integrated GPU 
- Integrated Development Environment (IDE) such as PyCharm or Visual Studio Code.

### Project Setup
To initialize this project on your local machine, please follow these steps:
Create a new virtual environment using the command:
```sh
conda create -p venv python=3.10 -y
```

Activate the newly created virtual environment:
```sh
conda activate venv/
```

Install all required project dependencies by executing:
```sh
pip install -r requirements.txt
```

After successfully installing all essential dependencies, proceed to run the fine-tuning script:
```sh
python fine_tune.py
```
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->
## Contributing
Contributions are what make the open-source community such an amazing place to learn and create. Any contributions you make are greatly appreciated.
If you have suggestions that would improve this project, please fork the repo and create a pull request. You can also open an issue tagged "enhancement". Don’t forget to give the project a star!
### Contribution Steps
Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->
## License
Distributed under the MIT License. See `LICENSE.txt` for more information.


<!-- CONTACT -->
## Contact
- Twitter Handle: [@the_jashann](https://x.com/the_jashann)
- Linkedin Handle: [Jashan preet Singh](https://www.linkedin.com/in/jashan-preet-singh-badwal/)
- Mail: [686jashan@gmail.com](mailto:686jashan@gmail.com)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments
* [Hugging Face](https://huggingface.co/google/datagemma-rag-27b-it)
* [Google](https://ai.google.dev/gemma)
<p align="right">(<a href="#readme-top">back to top</a>)</p>

