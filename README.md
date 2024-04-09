# OracleCoder: Enhancing Text-to-SQL Generation with QLoRA+ Ensemble

![OracleCoder Project Overview](https://arxiv.org/html/2402.05120v1/x1.png)


> **NOTE:** This project is on-going. The results here are not complete. Stay tuned for future updates on the evaluation of OracleCoder.

OracleCoder is a cutting-edge project aimed at advancing text-to-SQL generation capabilities. It leverages a novel approach, combining schema linking and SQL generation tasks, to fine-tune open-source language models efficiently. This project introduces an innovative ensemble method using QLoRA+ to achieve high performance while addressing data privacy and cost concerns, democratizing access to state-of-the-art text-to-SQL technologies.

## Key Features

- **Efficient Fine-Tuning**: Utilizes LoRA+ for efficient adaptation of smaller models, enabling performance on par with larger models without significant computational resources.
- **Ensemble Approach**: Employs a novel ensemble strategy with QLoRA+ to enhance model performance and reliability, showcasing a path forward for achieving high accuracy in text-to-SQL generation.
- **Schema Linking and SQL Generation**: Decomposes the complex text-to-SQL task into schema linking and SQL generation sub-tasks, allowing for more focused model training and improved accuracy.
- **Community-Driven and Open-Source**: Emphasizes the importance of community-driven, open-source innovation in advancing natural language processing and database interaction technologies.

## Project Structure

1. **Schema Linking**: The first phase involves identifying relevant tables and columns from a database schema based on a given natural language question. This step is crucial for understanding the context and narrowing down the focus for SQL generation.

2. **SQL Generation**: In the second phase, the model generates SQL queries based on the identified schema elements and the user's question. This step involves fine-tuning language models to accurately translate natural language questions into SQL queries.

3. **Ensemble Model**: Multiple models with varying learning rates for the LoRA adapters are trained and then merged into a single ensemble model. This approach enhances model performance and reliability, demonstrating a novel way to leverage ensemble methods in LLMs.

4. **Evaluation**: The project includes a comprehensive evaluation process, utilizing the Spider dataset and the BIRD benchmark to assess the performance of the developed models in schema linking and SQL generation tasks.

See my [website](https://jordandeklerk.github.io/project/oraclecoder/) for the full project.
