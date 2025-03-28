# Blood Cancer Detection Using AI

## Project Description
This project aims to detect blood cancer using AI techniques. It leverages deep learning models to analyze blood sample images and predict the presence of cancerous cells.

## Installation
To set up the project, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/Enosha01/Blood-Cancer-Detection-Using-AI.git
    cd blood-cancer-detection
    ```

2. Create a virtual environment:
    ```sh
    python -m venv env
    ```

3. Activate the virtual environment:
    - On Windows:
        ```sh
        .\env\Scripts\activate
        ```
    - On macOS/Linux:
        ```sh
        source env/bin/activate
        ```

4. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage
To run the application, use the following command:
```sh
python app.py
```

## Project Structure
```
BLOOD CANCER DETECTION USING AI/
│
├── app.py
├── CODE.ipynb
├── dataset.txt
├── model.ipynb
├── sql.sql
├── vs blood cancer.ipynb
├── env/
│   ├── pyvenv.cfg
│   ├── Include/
│   ├── Lib/
│   └── Scripts/
├── images/
│   ├── Snap_057.jpg
│   ├── Snap_091.jpg
│   └── ...
├── models/
│   ├── CNN.h5
│   ├── FinalModel.h5
│   └── mobilenet.h5
├── static/
│   ├── css/
│   ├── fonts/
│   ├── img/
│   └── js/
├── templates/
│   ├── about.html
│   ├── blog-post.html
│   ├── index.html
│   ├── login.html
│   ├── loginhomepage.html
│   ├── README.md
│   └── Register.html
└── README.md
```

## Dataset
The dataset used for this project consists of blood sample images. The images are stored in the `images/` directory.

## Model Training
To train the model, use the `model.ipynb` notebook. It contains the code for data preprocessing, model architecture, training, and evaluation.

## Model Evaluation
The trained models are saved in the `models/` directory. You can evaluate the models using the `model.ipynb` notebook.

## Deployment
To deploy the application, use the `app.py` script. It sets up a web server to serve the model predictions.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request.

## License
This project is licensed under the MIT License..

## Contact
For any questions or inquiries, please contact [yourname@example.com](mailto:yourname@example.com).
