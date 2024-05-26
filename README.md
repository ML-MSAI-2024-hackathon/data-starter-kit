# Getting started with the data

There are three main data entities in this hackathon:
- modgen-data-anon $\to$ a folder storing all audio files to use across all tasks.
- dict_dataset.json $\to$ the noisy labels of the audio files.
- unknown.mod $\to$ the song you have to play using your newly generated sounds.

Depending on whether you will work on Google Colab or on your local machine, follow the appropriate subsection to get access to the data. 

## ☁️ Google Colab:
- Open [this notebook](https://github.com/ML-MSAI-2024-hackathon/data-starter-kit/blob/main/download_extract_data.ipynb), which shows how to load external data while on Google Colab

## 💻 Your local machine:
- download all three files from [this](https://drive.google.com/drive/folders/1dhHoabbem0fmw-V5BWuhD4AA3Llf1cJl?usp=drive_link) Google Drive folder.
- unzip the modgen-data-anon.zip file (it may take a while, since the unzipped data is approximatively 5 GB 🥵)
  - at the end of the unzipping process, you will have the modgen-data-anon folder described above
- the file dict_data.json and unknown.mod can be used as they come and do not need any kind of unzipping
- You now have all the required files on your disk, so you can access however you want during your coding sessions!
