# Quality Assessment for Physiological Data 

## Input Data

The input data is too large to be hosted on github, so you can download them from this google drive link. Put the data files with these scripts and they should run together without issue, if you have any questions ask someone at the table, or look for Rithwik.

https://drive.google.com/drive/folders/1QZLxNATKjnH4BIdK2GHzXrNZ_lVZetUe?usp=drive_link

## Running the Notebooks

### Notebook 1: BH_10fold_card_model.ipynb

This file has a convolutional layers model that is trained on cardiological data, and validated using 10fold validation. This model can be used as a baseline to experiment with and see if its accuracy can be improved upon, by modifying parameters or testing different model architectures.

### Notebook 2: BH_10fold_resp_model.ipynb

This notebook has the same model as the previous cardiological model, but instead with respiratory data.

### Notebook 3: card_view_data.ipynb

This notebook can be used to view cardiological data. It currently displays the first 10 files, with blue being good data and red being bad data.

### Notebook 4: resp_view_data.ipynb

This notebook can be used to view the respiratory data.

## Built With

* [Keras](https://keras.io/)
* [Jupyter Notebook](https://jupyter.org/)
* [Python 3](https://www.python.org/)

## Contributing

Please read [CONTRIBUTING.md](https://github.com/neurdylab/physio_QA_dl/CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Authors

* **Rithwik Guntaka** - *Initial work* - @RickReddy
* **Roza Bayrak** - *Initial work* - @rgbayrak


## License

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/neurdylab/physio_QA_dl/LICENSE) file for details.
