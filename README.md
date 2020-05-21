# wget-googledrive

Simple tool for downloading public-shared files with Google Drive

It's common in Jupyter Notebooks and Google Colab to use files (checkpoints, trained models...) uploaded in Google Drive.

This is just a shorcut for simple usage of the commands in this article https://medium.com/@acpanjan/download-google-drive-files-using-wget-3c2c025a8b99

## Usage

In Notebook:

```
!git clone https://github.com/jaltez/wget-googledrive
```

Command:

```
!sh wget-googledrive/download FILEID FILENAME [--large]
```

- File ID: Shared identifier, extract from link "[...]/file/d/**1aeZAYEjBbThmBiuqDjd9W3CNETvu_ymv**/view"
- File name: Output
- --large: Optional mode for files with more than 100Mb