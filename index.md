## Life Expectancy Causal Analysis Project

In this project, we aim to establish causality between various socioeconomic variables and life expectancy outcomes in  roughly 166 different countries, noting the strongest connections between economic and political factors with the length of life expectancy. 

Below you will find background information on our data, our reasoning, our methods, and how to gather information for real world questions you can have. 

To find out more about us, click [here.](About.md)


### How to Use

In order to use the algorithm yourself, and add in more variables, we have organized a demo showing how we got our [main results.](Main-Results.md)
**LAST THING THAT NEEDS DONE!!!! EXPLANATION OF HOW TO READ GRAPHS - EXPLANATION OF RUNNING ALGORITHM - EXPLANATION OF SPECIFIC GRAPHS**

### Our Methods

In this project, we utilize Independence-based causal discovery, leading us to use the popular **PC algorithm**, created and named after Spirtes and Glymour, that utilizes the idea that two statistically independent variables are not causally linked.

To read our explanation on the PC Algorithm, see our [Explanation of The PC Algorithm.](PC-Algorithm-Explanation.md)

### Our Data
We combined several different datasets in order to gather enough data to properly examine our question of choice. To begin, we utilized the World Happiness Report (WHR) (https://worldhappiness.report/faq/) which details, based on surveys, various factors that contribute to  a country’s overall happiness and wellbeing.

Our second dataset comes from the Comparative Political Data Set (CPDS) which includes a collection of political and institutional data from 1960 to 2019. Because the dataset is fairly large, we will not go into detail about each variable and instead encourage you to visit https://www.cpds-data.org/images/Update2021/Codebook_CPDS_1960-2019_Update_2021.pdf to read more about the specific variables used. In summary, the dataset includes detailed information on party composition, reshuffles, duration, types of government, and additional economic, socioeconomic, and demographic variables to add to the World Happiness Report and our examination of the connections between these variables and Life Expectancy. 

Lastly, our project is built as a pipeline, ready for any additional data to be added and utilized by  the algorithm. This means that as more reliable and detailed data is made publicly available, we can easily update our algorithm and output to accommodate this new knowledge, and change the conclusions of the report accordingly. 

To see the data cleaning and pipelining process, check out [Data Cleaning!](data-cleaning.md)

If you would like to read more about our data, see [this report,](https://docs.google.com/document/d/1cvPz98_5bFYzUca4mlcvndjPvenBJzs4ya1jSkPVNS0/edit?usp=sharing) or view the data directly on [our repo.](https://github.com/mglevitt/Medical-Disparity-Causal-Analysis)

### Support or Contact

Want to see more behind the scenes or need additional help? Check out our [documentation](https://github.com/mglevitt/Medical-Disparity-Causal-Analysis) or send us an email at eramond@ucsd.edu, mglevitt@ucsd.edu, and akreitzman@ucsd.edu. 
