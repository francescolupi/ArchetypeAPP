# Archetype_NoteBook

The `APP_Archetype.ipynb` file is a demo of the paper entitled "Toward Automatic Definition of Engineer Archetypes: A Text Mining Approach". Please cite the work as "xx".

The Notebook can be directly run using Google Colab at this link: [Open in Colab](https://colab.research.google.com/drive/1M9xje31CaP8-6-Ayzv1LjXY9wVt5xOuU?usp=drive_link). The `.ipynb` file is also shared in this repository.

## Main Steps

1. **Step 1: Import Libraries**: Import the necessary libraries when launching the runtime. This may take a few seconds.

2. **Step 2: Upload File and Select Model Parameters**: Upload an Excel file as input, which should contain course/job descriptions. The file should have a header row that is not considered in the code. Configure the model parameters using the provided widgets. Each course/job description should be on a separate row, and it is recommended to have at least 100 descriptions with a minimum of 100 words per row.

3. **Step 3: Display Archetype**: Display the archetype in the form of topics extracted as clusters.

4. **Step 4: Download Archetype**: Download the archetype in the form of 100 technical keywords (content) and Bloom Verbs (verbs) for each identified topic. The content can be retrieved, for example, from ChatGPT by querying "provide me a content of max 20 words for the topic which includes these technical keywords [...]" and listing the keywords.

## License

This project is licensed under the [Apache License 2.0](LICENSE).
