This bioinformatics tool was written within the scope of the project of a company I worked for. Because patient data are private, I can share the script and project tutorial and the packages I used in detail.

The find_peaks module from Python's scipy library was used to predict peaks in the patient data in the form of datapoints. To optimize the data with smoothing and reduce the contamination factor, the savgol_filter module of the same library was also applied to the data before peak prediction. 
Ridge regression model of Python's sklearn library was used for converting patient data from datapoint to size pair.

"Size ladder", the company's R&D product, promises a peak image with certain distances between expected peaks in size pairs. The pattern of expected distances was searched in the peaks obtained from the size ladder data run with the patient sample. For this, correlation was applied and the resulting datapoint sizepair information was used to train the regression model.

Python's dash library was used to integrate the code into the interface.

<!--
**esrabardakci/esrabardakci** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
