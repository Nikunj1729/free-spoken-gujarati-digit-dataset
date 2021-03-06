# Spoken Digits Dataset in Gujarati Language

  Free Spoken Gujarati Digits Dataset (FSGDD). Think MNIST for audio.

# Abstract : 

  We introduce a new database of isolated Gujarati digits recordings with the goal of supporting research on speech recognition systems. This proposed database contains genuine recordings of digits spoken by various users of 5 different regions of Gujarat. Specifically, the database contains recordings in a variety of environmental conditions with different forms of background noise. It's a simple audio/speech dataset consisting of recordings of spoken digits in wav files at 44kHz (Nyquist frequency). The recordings are trimmed so that they have near minimal silence at the beginnings and ends. To the best of our knowledge, this is the first free Gujarati digits database that has been present now.

# Current status :

  20 speakers
  
  1940 recordings
  
  Gujarati pronunciations
  
  5 Regions - Central Zone, North Zone, South Zone, Saurashtra, Kutch Region

# Naming Convention :
  
  Files are named in the following format: 

  {Region_Number}{Speaker_Number}{Trial_Number}{Digit_Number}.wav 

  Example: R1S1T1D1.wav. Here R1 suggests region 1, S1 suggests speaker 1 from that region, T1 suggests trial 1, and D1 suggests Digit 1.

# Contributions :

  Please contribute your homemade recordings. All recordings should be mono 44kHz wav files and be trimmed to have minimal    silence. Don't forget to update metadata.py with the speaker meta-data. To add your data, follow the recording instructions follow the details given above.

# Contributors :

  Nikunj Dalsaniya

  Software Systems (Data Science), Birla Institute of Technology (WILP), Vidya Vihar, Pilani, Rajasthan - 333031, India

  Sapan H Mankad (https://scholar.google.co.in/citations?user=hZ88OoYAAAAJ&hl=en)

# Release Note :

  FSGDD is an open dataset, which means it will grow over time as data is contributed. Thus in order to enable reproducibility and accurate citation in scientific journals the dataset is versioned using git tags.

  For more details, 

  Kindly refer the following paper which is under publication 

  https://link.springer.com/chapter/10.1007/978-981-15-4828-4_18

  If you use this dataset for any of your research work, kindly cite this paper as:

  Development of a Novel Database in Gujarati Language for Spoken Digits Classification (Dalsaniya N., Mankad S.H., Garg S., Shrivastava D. (2020)). In: Thampi S. et al. (eds) Advances in Signal Processing and Intelligent Recognition Systems. SIRS 2019. Communications in Computer and Information Science, vol 1209. Springer, Singapore
