# Free Spoken Gujarati Digits Dataset (FSGDD)

A free audio dataset of Gujarati spoken digits. Think MNIST for audio.

# Abstract : 

We introduce a new database of isolated Gujarati digits recordings with the goal of supporting research on speech recognition systems. This proposed database contains genuine recordings of digits spoken by various users of 5 different regions of Gujarat. Specifically, the database contains recordings in a variety of environmental conditions with different forms of background noise. It's a simple audio/speech dataset consisting of recordings of spoken digits in wav files at 44kHz (Nyquist frequency). The recordings are trimmed so that they have near minimal silence at the beginnings and ends. To the best of our knowledge, this is the first free Gujarati digits database that has been present now.

# Current status :

  20 speakers
  
  2,000 recordings (10 of each digit per speaker)
  
  Gujarati pronunciations
  
  5 Regions - Central Zone, North Zone, South Zone, Saurashtra, Kutch Region

# Naming Convention :
  
Files are named in the following format: 

{Region_Number}{Speaker_Number}{Trial_Number}{Digit_Number}.wav 

Example: R1S1T1D1.wav. Here R1 suggests region 1, S1 suggests speaker 1 from that region, T1 suggests trial 1, and D1 suggests Digit 1.

# Contributions :

Please contribute your homemade recordings. All recordings should be mono 44kHz wav files and be trimmed to have minimal silence. Don't forget to update metadata.py with the speaker meta-data. To add your data, follow the recording instructions follow the details given above.

# Contributors :

Nikunj Dalsaniya

Software Systems (Data Science), Birla Institute of Technology (WILP), Vidya Vihar, Pilani, Rajasthan - 333031, India

Sapan H Mankad (https://scholar.google.co.in/citations?user=hZ88OoYAAAAJ&hl=en)

# Release Note :

FSGDD is an open dataset, which means it will grow over time as data is contributed. Thus in order to enable reproducibility and accurate citation in scientific journals the dataset is versioned using git tags.

For more details, 

Kindly refer the following paper which is under publication.
