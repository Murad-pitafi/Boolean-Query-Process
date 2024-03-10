 

# Boolean Query Processing

This project implements a Boolean Query Processing system for Information Retrieval. It facilitates the creation of inverted indexes and positional indexes to support the Boolean Model of Information Retrieval. The system preprocesses documents, handles Boolean expressions, and processes queries to retrieve relevant documents.

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/Murad-pitafi/Boolean-Query-Process.git
    ```

2. Navigate to the project directory:

    ```bash
    cd Boolean-Query-Process
    ```

3. Run the main script to execute the Boolean Query Processing system:

    ```bash
    python main.py
    ```

## Features

### 1. Inverted Index Creation

- **Description**: Generates an inverted index for a collection of documents.
- **Functionality**: Preprocesses documents, tokenizes content, performs stemming, and constructs the inverted index based on the processed words.

### 2. Positional Index Creation

- **Description**: Creates a positional index to facilitate proximity queries.
- **Functionality**: Enhances the inverted index with positional information to support proximity-based document retrieval.

### 3. Boolean Query Processing

- **Description**: Handles Boolean expressions to retrieve relevant documents.
- **Functionality**: Processes Boolean queries using the inverted index, supporting operators such as AND, OR, and NOT.

### 4. Proximity Query Processing

- **Description**: Supports proximity queries, which require terms to occur within a specified proximity of each other.
- **Functionality**: Utilizes the positional index to determine document matches based on proximity constraints.

## Dependencies

- Python 3.x

## Contributing

Contributions are welcome! Please feel free to submit issues or pull requests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
 
