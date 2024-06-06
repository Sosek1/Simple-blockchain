# 🪙 Simple Blockchain Project

This project is a simple blockchain implemented in object-oriented Python. It offers the following features:

- 🔑 **Key Generation**: Generate private and public keys to create a wallet.
- ⛏️ **Mining**: Mine blocks and add them to the blockchain.
- 📊 **Transaction Management**: Display approved and opened transactions
- 📄 **Data Storage**: Store the blockchain and keys in a text file.

Additionally, the project includes a user interface built with Vue.js that allows users to interact with the blockchain through a web page, using Flask for the API.

## Technologies Used

- 🐍 **Python**: The core blockchain functionality is implemented in Python.
- 🖼️ **Vue.js**: The front-end user interface is built with Vue.js.
- 🌐 **Flask**: Flask is used to create the API that connects the front-end with the blockchain backend.
- 📄 **Text Files**: Blockchain data and keys are stored in text files for simplicity.

## Installation

To set up this project on your local machine, follow these steps:

1. **Clone the repository**:

    ```bash
    git clone https://github.com/Sosek1/Simple-blockchain.git
    cd Simple-blockchain
    ```

2. **Create a Conda environment from the `environment.yml` file**:

    ```bash
    conda env create -f environment.yml
    conda activate your_environment_name
    ```

4. **Run the project**:

- After activating and running conda terminal navigate to `Simple-blockchain` directory
- Run 
  ```bash
  python node.py
  ```
- Click on first http address with control key. 
