Python 3.10.12 (main, Nov 20 2023, 15:14:05) [GCC 11.4.0] on linux
Type "help", "copyright", "credits" or "license" for more information.

>>> from developers import DataScientist
>>> abhishek = DataScientist(name="Abhishek Mall")
>>>
>>> abhishek.get_background()
"PhD in Physics from Max Planck Institute. Specializing in AI/ML and ETL pipelines."
>>>
>>> abhishek.get_tech_stack()
{
...     "Languages": ["Python"],
...     "Deep Learning": ["PyTorch", "TensorFlow"],
...     "Data Analytics": ["NumPy", "Pandas", "Scikit-learn", "CuPy"],
...     "Visualization": ["Plotly", "Matplotlib", "Seaborn"],
...     "Infrastructure": ["HPC", "Slurm"],
...     "Tools": ["Git", "VS Code", "Jupyter", "Vim"]
... }
>>>
>>> abhishek.get_current_status()
"Developing machine learning based analysis pipelines to handle petabytes of data."
>>>
>>> abhishek.get_contact_info()
{"LinkedIn": "linkedin.com/in/abhishek-mall", "Email": "abhishekmall101iitb@gmail.com"}
>>>
