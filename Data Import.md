# Data Import
The notebook can be run locally or Colab. If the latter method of execution is chosen, the data can be imported directly from one's own Google Drive, removing the need to have a local copy of the data. Below is an explaination on how to do it.

## Colab and Google Drive
Although the data is publicly available inside a GD folder, Colab needs it to reside inside your own Google Drive. The file can be copied directly from the source to your GD folder, without having to download it locally and then upload it.

The first cell will prompt you with an URL. Click on it to obtain an authorization token, then copy and paste it in the text box below the URL in the ouput cell in the notebook.

> Safety Note: at the time of writing, it isn't possible to mount only a subfolder of you GD. The notebook will therefore have access to all of your GD data! It is set up in such a way that it only read data, throwing at most an error if it doesn't find the expected file structure, so no privacy violation or file removal should happen. Still, the developer takes no responsability of eventual issues that may happen when executing the notebook with your DB attached.

## Running Locally with Local Data
To execute locally, you can comment out or remove lines 3 and 4 of the first cell.

## Data Path
Irrespectively of where you run the notebook and whether your data resides, you may need to set the variable containing the path to the datasets folder. You can find it in the second cell.
