## LearnHtml

Html web content extraction library using *mostly* DOM features as well as some textual features. [Achieves](https://www.researchgate.net/publication/329061153_Learning_Web_Content_Extraction_with_DOM_Features) a tag-level F1-score of `.96` on the Dragnet dataset.

### Installation

Prerequisites:

- Python > 3.6; Python < 3.8
- pip 23.0.1


First you will need to install the dependencies. For the binary dependencies:

- Linux
    ```bash
    sudo apt-get install recode libxml2-dev libxslt1-dev unzip
    ```

Python dependencies:
```bash
pip install -r requirements.txt
```

Build the project and install it locally
```bash
LIBXML2_PATH=<PATH_TO_LIBXML2> pip install -e .
```
