# File formats used in AI projects

Sure, here is a list of some common file formats used in AI and their use cases:

1. **CSV (Comma-Separated Values):** CSV files are often used for storing tabular data. They are simple to read and write from both a programming and human perspective. In AI, CSV files are often used as input for machine learning models. For example, a dataset of housing prices might be stored in a CSV file with each row representing a house and columns representing attributes such as square footage, number of bedrooms, and location.

2. **JSON (JavaScript Object Notation):** JSON files are used to store structured data in a human-readable format. In AI, they are often used to store configuration settings for models, such as hyperparameters or architecture details. They can also be used to store data for machine learning models, particularly when the data is more complex than tabular data.

3. **Pickle (.pkl):** Pickle is a Python-specific format used to serialize and deserialize Python objects, including machine learning models. This allows you to save a model to disk after training and then load it again later to make predictions.

4. **HDF5 (.h5, .hdf5):** Hierarchical Data Format version 5 is a file format that can store large, complex datasets. It is used to store weights and model configuration in a single file for models in Keras, a popular deep learning library in Python.

5. **Protocol Buffers (.pb):** Protocol Buffers are Google's language-neutral, platform-neutral, extensible mechanism for serializing structured data. TensorFlow, a popular machine learning library, uses Protocol Buffers for model serialization.

6. **ONNX (Open Neural Network Exchange):** ONNX is an open format to represent deep learning models. It allows models to be trained in one framework (like PyTorch) and then transferred to another (like Caffe2) for inference.

7. **PT (PyTorch):** PyTorch has its own model serialization format, `.pt` or `.pth`, which can be used to save and load models, including both their architecture and trained parameters.

8. **Joblib (.joblib):** Joblib is a way to provide fast serialization of Python objects, especially NumPy arrays. This is particularly useful when dealing with large data that doesn't fit in memory, as well as for sharing Python objects between multiple processes. It is often used in combination with scikit-learn, a popular library for machine learning in Python.

9. **PMML (Predictive Model Markup Language):** PMML is an XML-based file format developed by the Data Mining Group to provide a way for applications to define statistical and data mining models and to share models between PMML compliant applications.

10. **PARQUET:** Apache Parquet is a columnar storage file format available to any project in the Hadoop ecosystem. It is designed for efficiency and performance, which is often used in big data processing pipelines, including machine learning use cases.

Please note that many of these formats serve different purposes: some are better suited for serializing models (e.g., `.pb`, `.h5`, `.pt`, `.pkl`, `.joblib`, `PMML`, `ONNX`), while others are more for data storage and exchange (e.g., `CSV`, `JSON`, `HDF5`, `PARQUET`). The choice of file format often depends on the specific requirements of the AI project, such as the machine learning framework being used, the complexity of the data, and the need for interoperability.

## Other file formats

* [Mini GPT4 dataset](mini-gpt4-dataset.md)
