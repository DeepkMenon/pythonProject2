Extended Virtual screening tool - VISMAI

The development of our proposed virtual screening tool, represents a significant step towards streamlining the drug discovery process. By leveraging advanced machine learning techniques, particularly Graph Convolutional Neural Networks (GCNNs), this tool offers better prediction of drug-likeness, a crucial criterion in early drug development.The integration of RDKit and Mordred libraries enables robust calculation of molecular descriptors and fingerprint generation, providing valuable insights into the chemical properties and structural features of potential drug candidates. 

The system was built using the Django web framework, which provided a robust and scalable foundation for the application's backend. HTML and CSS were utilized for creating the user interface, enabling an intuitive and visually appealing front-end experience.

For the development and training of the Graph Convolutional Neural Network (GCNN) models, we utilized the powerful Kaggle platform. Kaggle offers good GPU availability , allowing for efficient model development, experimentation, and evaluation.

The drug-likeness prediction module was implemented using the PyTorch Geometric library, a state-of-the-art framework designed specifically for working with graph-structured data. This library facilitated the construction and training of our GCNN models, enabling us to leverage the power of graph convolutional networks for accurate drug-likeness predictions.


Handled by Achyut M Sharma and Deepak Menon
