# Archetype_NoteBook

This Notebook is a demo generated for the paper "Lupi F., Mabkhot M.M., Boffa E., Ferreira P., Antonelli D., Maffei A., Lohse N., and Lanzetta M.,. Toward Automatic Definition of Engineer Archetypes: A Text Mining Approach, 2023". The Notebook can be directly run using Google Colab at this link: [Open in Colab](https://colab.research.google.com/drive/1M9xje31CaP8-6-Ayzv1LjXY9wVt5xOuU?usp=drive_link). The `.ipynb` file is also shared in this repository. 

## Main steps

1. **Step 1: Import Libraries**: Run the code to install and import the necessary libraries when launching the runtime. This may take a few seconds.

2. **Step 2: Upload File and Select Model Parameters**: Run the code to upload an Excel file as input, which should contain course/job descriptions. The file should have a header row that is not considered in the code. Configure the model parameters using the provided widgets. For more information on the parameters' meaning refer to the paper. Default parameters are set on the specific input file adopted in the paper. Each textual course/job description should be on a separate row of the Excel file, and it is recommended to have at least 100 descriptions with a minimum of 100 words per row.

3. **Step 3: Display Archetype**: Run the code to display the archetype in the form of topics extracted as clusters.

4. **Step 4: Download Archetype**: Run the code to download the archetype in the form of 100 technical keywords (content) and Bloom Verbs (verbs) for each identified topic. The content can be retrieved, for example, from ChatGPT by querying "provide me a content of max 20 words for the topic which includes these technical keywords [...]" and listing the keywords.

## Paper Reference

Cite as "Lupi F., Mabkhot M.M., Boffa E., Ferreira P., Antonelli D., Maffei A., Lohse N., and Lanzetta M.,. Toward Automatic Definition of Engineer Archetypes: A Text Mining Approach, 2023" 

Abstract: With the rapid and continuous advancements in technology, as well as the constantly evolving competencies 
required in the field of engineering, there is a critical need for the harmonization and unification of engineering professional 
figures or archetypes. The current limitations in defining and updating engineers' archetypes are attributed to the absence of a 
structured and automated approach for processing educational and occupational data sources that evolve over time. This study 
aims to enhance the definition of professional figures in engineering by automating archetype definitions through text mining
and adopting a more objective and structured methodology based on topic modeling. This will expand the use of archetypes 
as a common language, bridging the gap between educational and occupational frameworks by providing a unified and up-to-date engineering professional figure tailored to a specific period, specialization type, and level. We validate the automatically 
defined industrial engineer archetype against our previously manually defined profile. The prototype software for archetype 
generation that we have developed is publicly available online at

## License

This project is licensed under the [Apache License 2.0](LICENSE).
