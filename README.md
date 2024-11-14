# PandasAI-ML
This short project demonstrates a predictive model trained using PandasAI to forecast housing prices. Using prompt engineering and PandasAI, I can guide the model in generating code for training and result visualization.

Steps to Reproduce:

1. Load the housing dataset:
 
df = pd.read_csv('kc_house_data.csv')

3. Configure PandasAI with API key:
 
os.environ['PANDASAI_API_KEY'] = 'your_api_key_here'

5. Guide PandasAI to generate a model with a prompt:
 
response = pandas_ai.generate_code("Use prompt engineering to generate exactly what is needed")

7. Result Visualization
The model’s output includes a scatter plot comparing predicted prices to actual values, with a reference line to visualize accuracy, helping evaluate the model’s performance.

This project illustrates how PandasAI, combined with prompt engineering, can be a powerful tool for building machine learning models.
