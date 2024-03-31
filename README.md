## LearnHtml

Html web content extraction library using *mostly* DOM features as well as some textual features. [Achieves](https://www.researchgate.net/publication/329061153_Learning_Web_Content_Extraction_with_DOM_Features) a tag-level F1-score of `.96` on the Dragnet dataset.

### Requirements
First you will need to install the dependencies. For the binary dependencies:

- Linux
    ```bash
    sudo apt-get install recode libxml2-dev libxslt1-dev unzip
    ```

Set up environment variables:

Create a file named `.env` in the root of the project and copy the contents of the `.env.example` file into it.
Then replace environment variables with the corresponding values on your system.


Python dependencies:
```bash
pip install -r requirements.txt
```

Build the project and install it locally
```bash
pip install -e .
```
