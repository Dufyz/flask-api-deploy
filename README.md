# ⚡ Flask Api Deploy
A Flask API made with python's flask library

# ℹ️ About the project
This API is a Flask API that deploy a machine learning model to browser. The API receives a sentence across the url and alyzes it. This API was made as a test of api deploy ways. 
This API have two possible uses: 
- 1 - Measure the sentiments of a sentece (Polarity near 1: Good feelings; Polarity near 2: Bad feelings)
- 2 - Measure the price of a house based on size, house age and garage

# 📝 Technologies
- [Python](https://www.python.org/)
- [Jupyter Notebook](https://jupyter.org/)
- [SkLearn](https://scikit-learn.org/)
- [Flask](https://flask.palletsprojects.com/en/2.0.x/)
- [Google Cloud](https://cloud.google.com/?utm_source=google&utm_medium=cpc&utm_campaign=latam-BR-all-pt-dr-BKWS-all-all-trial-e-dr-1011454-LUAC0010101&utm_content=text-ad-none-any-DEV_c-CRE_512285710737-ADGP_Hybrid%20%7C%20BKWS%20-%20EXA%20%7C%20Txt%20~%20GCP_General-KWID_43700062788251521-kwd-301173107424&utm_term=KW_google%20cloud-ST_Google%20Cloud&gclid=CjwKCAiA24SPBhB0EiwAjBgkhgcmSLndof7yGjL435tse5Q-iOuMbgSSW7KPSOPKdlSvx0E4WxPMuxoC6fAQAvD_BwE&gclsrc=aw.ds)
- [Docker](https://www.docker.com/)

# 👨‍🏫 How to use
To use this API you will need to pay attention to some steps.

- 1 - When you run //main.py file on terminal you will get a url that is your api home page.
- 2 -  How to use the differents ways of the Api
  - 2.1 - First way to use the API: ip_url/polarity/sentece to be analysed
  - 2.2 - Second way to use the API: you will need to use postman app to send a jsdon data type to be analysed for the IA model
