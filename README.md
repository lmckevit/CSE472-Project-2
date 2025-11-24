# WildfireSpreadTS - Dataset creation

To create the dataset, you will need access to Google Cloud Storage and Google Earth Engine. 

1. Install all necessary requirements from the requirements.txt file via 
```
pip install -r requirements.txt
```
2. Set up the [Google Cloud SDK](https://cloud.google.com/sdk/docs/how-to) and authenticate with your Google account.
3. Set up the [Google Earth Engine Python API](https://developers.google.com/earth-engine/guides/python_install) and authenticate with your Google account.
4. Enter your [Google Service Account](https://cloud.google.com/iam/docs/service-account-overview) credentials and the path to your key file in `main.py`.
5. Set the yaml file in `main.py` that you want to use to download corresponding data and change the Google cloud storage bucket name in the respective yaml file to yours.
6. Run `python main.py` to let GEE compute the dataset and upload it into your Google cloud storage bucket.
