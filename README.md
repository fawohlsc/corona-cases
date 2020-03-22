# Corona cases
This repository contains a Jupyter notebook to visualize the corona cases (COVID-19) either per country of worldwide. The underlying dataset is provided by the [Johns Hopkins University](https://github.com/CSSEGISandData/COVID-19/). 

![Bar Chart](assets/10_notebook_ready.png)

## Launch as Azure Notebook
1. Click this button to launch this Jupyter notebook within an Azure Notebook<br/>
[![Azure Notebooks](https://notebooks.azure.com/launch.png)](https://notebooks.azure.com/import/gh/fawohlsc/corona-cases)

2. Sign in with your Microsoft account, but other accounts like Google work as well<br/>
![Azure Notebook Import](assets/01_notebook_signin.png)

3. Click ```Import``` to configure the import from the GitHub repository into Azure Notebooks<br/>
![Azure Notebook Import](assets/02_notebook_welcome.png)

4. Select the options according to belows screenshot and start the import by clicking ```Import```<br/>
![Azure Notebook Import](assets/03_notebook_import.png)

5. Configure the project setttings to install the required packages into your Jupyter notebook<br/>
![Azure Notebook Settings](assets/04_notebook_settings.png)

6. Configure the environment setup steps (```Requirements.txt```, ```requirements.txt```, ```Python Version 3.6```)<br/>
![Azure Notebook Environment](assets/05_notebook_enviroment.png)

7. Launch the Jupyter notebook by clicking on ```corona_cases.ipynb``` - it will open in another browser tab<br/>
![Azure Notebook Open](assets/06_notebook_open.png)

8. Set the Kernel for the Jupyter notebook to be ```Python 3.6``` or higher - confirm by clicking ```Set Kernel```<br/>
![Azure Notebook Kernel](assets/07_notebook_kernel.png)

9. Run the Jupyter Notebook by selecting ```Cell -> Run All ```<br/>
![Azure Notebook Run](assets/08_notebook_run.png)

10. Wait a few seconds for the run to complete as indicated by the ```[*]``` next to each cell<br/>
![Azure Notebook Wait](assets/09_notebook_wait.png)

11. Scroll down to see the visualization of the Corona cases either per country or worldwide<br/>
![Azure Notebook Ready](assets/10_notebook_ready.png)

12. Repeat step 9 in order to refresh the underlying dataset - the dataset is currently updated once a day by [Johns Hopkins University](https://github.com/CSSEGISandData/COVID-19/)
![Azure Notebook Run](assets/08_notebook_run.png)

## Launch on your local computer
1. You need Python 3 to be installed on your system - see [https://www.python.org/](https://www.python.org/)
2. Furthermore you require pip, which is the python package installer - see [https://pypi.org/project/pip/](https://pypi.org/project/pip/)
3. After that, follow these steps to launch this Jupyter notebook on your machine
```bash
# Install Jupyter notebook
pip3 install jupyter

# Install package dependencies
pip3 install -r requirements.txt

# Enable widget extension in Jupyter notebook
jupyter nbextension enable --py widgetsnbextension

# Run Jupyter notebook
jupyter notebook
```
4. If you are running on Windows, replace aboves ```pip3``` commands with just ```pip```
5. Any code editor will do, e.g. [Visual Studio Code](https://code.visualstudio.com/) with the [Python extension](https://code.visualstudio.com/docs/languages/python)

## Launch in a virtual environment
1. You need Python 3 to be installed on your system - see [https://www.python.org/](https://www.python.org/)
2. Furthermore you require pip, which is the python package installer - see [https://pypi.org/project/pip/](https://pypi.org/project/pip/)
3. Follow these steps to launch this Jupyter notebook within a virtual environment

```bash
# Install Jupyter notebook
pip3 install jupyter

# Install virtual environment
pip3 install virtualenv

# Create virtual environment
python3 -m venv .venv

# Activate virtual environment
source .venv/bin/activate

# Install package dependencies
pip install -r requirements.txt

# Install virtual environment as Jupyter notebook kernel
ipython kernel install --user --name=.venv

# Enable widget extension in Jupyter notebook
jupyter nbextension enable --py widgetsnbextension

# Run Jupyter notebook
jupyter notebook
```
4. If you are running on Windows, replace aboves ```pip3``` commands with just ```pip```
5. Any code editor will do, e.g. [Visual Studio Code](https://code.visualstudio.com/) with the [Python extension](https://code.visualstudio.com/docs/languages/python)