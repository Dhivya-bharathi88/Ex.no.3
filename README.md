# Ex-no.3 Univariate Analysis

# AIM:

To perform Univariate Analysis for the given data set.

# EXPLANATION:

Univariate analysis is basically the simplest form to analyze data. Uni means one and this means that the data has only one kind of variable. The major reason for univariate analysis is to use the data to describe. The analysis will take data, summarise it, and then find some pattern in the data

# ALGORITHM:

# STEP-1:

Read the given data.

# STEP-2:

Get the information about the data.

# STEP-3:

Perform Univariate Analysis Techniques for the given dataset.

# STEP-4:

Save the data to the file.

# CODE:

# SUPERTSORE DATA:

# NON-GRAPHICAL:

import pandas as pd

import numpy as np

import seaborn as sns

from google.colab import files

uploaded = files.upload()

df = pd.read_csv("SuperStore.csv")

df.info()

import pandas as pd

import numpy as np

import seaborn as sns
from google.colab import files

uploaded = files.upload()

df = pd.read_csv("SuperStore.csv")

df.dtypes

import pandas as pd

import numpy as np

import seaborn as sns

from google.colab import files

uploaded = files.upload()

df = pd.read_csv("SuperStore.csv")

df['Row ID'].value_counts()

import pandas as pd

import numpy as np

import seaborn as sns

from google.colab import files

uploaded = files.upload()

df = pd.read_csv("SuperStore.csv")

df['Order ID'].value_counts()

import pandas as pd

import numpy as np

import seaborn as sns

from google.colab import files

uploaded = files.upload()

df = pd.read_csv("SuperStore.csv")

df.describe()

import pandas as pd

import numpy as np

import seaborn as sns

from google.colab import files

uploaded = files.upload()

df = pd.read_csv("SuperStore.csv")

df.skew()

import pandas as pd

import numpy as np

import seaborn as sns

from google.colab import files

uploaded = files.upload()

df = pd.read_csv("SuperStore.csv")

df.kurtosis()

# GRAPHICAL:

# BOX PLOT:

import pandas as pd

import numpy as np

import seaborn as sns

from google.colab import files

uploaded = files.upload()

df = pd.read_csv("SuperStore.csv")

sns.boxplot(x="Row ID",data=df)

# COUNT PLOT:

import pandas as pd

import numpy as np

import seaborn as sns

from google.colab import files

uploaded = files.upload()

df = pd.read_csv("SuperStore.csv")

sns.countplot(x="Row ID",data=df)

# DIST PLOT:

import pandas as pd

import numpy as np

import seaborn as sns

from google.colab import files

uploaded = files.upload()

df = pd.read_csv("SuperStore.csv")

sns.distplot(df["Row ID"])

# HIST PLOT:

import pandas as pd

import numpy as np

import seaborn as sns

from google.colab import files

uploaded = files.upload()

df = pd.read_csv("SuperStore.csv")

sns.histplot(x="Row ID",data=df)

# DIABETES DATA:

# NON-GRAPHICAL:

import pandas as pd

import seaborn as sns

from google.colab import files

uploaded = files.upload()

df = pd.read_csv("diabetes.csv")

df.info()

print("\n")

df.dtypes

import pandas as pd

import seaborn as sns

from google.colab import files

uploaded = files.upload()

df = pd.read_csv("diabetes.csv")

df['Glucose'].value_counts()

import pandas as pd

import seaborn as sns

from google.colab import files

uploaded = files.upload()

df = pd.read_csv("diabetes.csv")

df['BloodPressure'].value_counts()

import pandas as pd

import seaborn as sns

from google.colab import files

uploaded = files.upload()

df = pd.read_csv("diabetes.csv")

df.describe()

import pandas as pd

import seaborn as sns

from google.colab import files

uploaded = files.upload()

df = pd.read_csv("diabetes.csv")

df.skew()

import pandas as pd

import seaborn as sns

from google.colab import files

uploaded = files.upload()

df = pd.read_csv("diabetes.csv")

df.kurtosis()

# GRAPHICAL:

# BOX PLOT:

import pandas as pd

import seaborn as sns

from google.colab import files

uploaded = files.upload()

df = pd.read_csv("diabetes.csv")

sns.boxplot(x="Glucose",data=df)

# COUNT PLOT:

import pandas as pd

import seaborn as sns

from google.colab import files

uploaded = files.upload()

df = pd.read_csv("diabetes.csv")

sns.countplot(x="Glucose",data=df)

# DIST PLOT:

import pandas as pd

import seaborn as sns

from google.colab import files

uploaded = files.upload()

df = pd.read_csv("diabetes.csv")

sns.distplot(df["Glucose"])

# HIST PLOT:

import pandas as pd

import seaborn as sns

from google.colab import files

uploaded = files.upload()

df = pd.read_csv("diabetes.csv")

sns.histplot(x="Glucose",data=df)

# CODE:

# NON-GRAPHICAL:
![Screenshot (64)](https://user-images.githubusercontent.com/128019999/232207569-af1ad97f-edc7-4649-b55a-5545db319d25.png)
![Screenshot (65)](https://user-images.githubusercontent.com/128019999/232207585-224a98f4-410e-4d8e-a095-9d667797238c.png)
![Screenshot (66)](https://user-images.githubusercontent.com/128019999/232207598-05b4fb00-d675-4769-9e8b-a46036f69fa9.png)
![Screenshot (67)](https://user-images.githubusercontent.com/128019999/232207627-0110ec4b-a97e-41c8-82de-8719c54c80f0.png)
![Screenshot (68)](https://user-images.githubusercontent.com/128019999/232207635-5716caf2-3046-432f-9496-65f0332bb926.png)
![Screenshot (69)](https://user-images.githubusercontent.com/128019999/232207650-c5aff587-c437-47a5-ae78-efa789067f92.png)
# GRAPHICAL:
# BOX PLOT:
![Screenshot (76)](https://user-images.githubusercontent.com/128019999/232208506-4755dc8e-e4ec-45b5-8345-7eff37ad41eb.png)
# COUNT PLOT:
![Screenshot (77)](https://user-images.githubusercontent.com/128019999/232208519-8105eb94-90e5-4f12-9bcd-26260caabd21.png)
# DIST PLOT:
![Screenshot (78)](https://user-images.githubusercontent.com/128019999/232208529-b278537d-00eb-48f1-9517-ba439f6888bc.png)
# HIST PLOT:
![Screenshot (79)](https://user-images.githubusercontent.com/128019999/232208541-68a51fad-a823-42f0-8b4f-adc5691eec84.png)
# DIABETES DATA SET:
# NON-GRAPHICHAL:
![Screenshot (80)](https://user-images.githubusercontent.com/128019999/232208554-3e0d21f3-3225-4338-8f9d-db3821337ef8.png)
![Screenshot (81)](https://user-images.githubusercontent.com/128019999/232208569-7434a471-42af-4483-8478-f0bb00b9a97c.png)
![Screenshot (82)](https://user-images.githubusercontent.com/128019999/232208579-3a8b1b16-b889-4add-8176-aad37bb2c4db.png)
![Screenshot (83)](https://user-images.githubusercontent.com/128019999/232208591-61519249-632e-4bd2-8759-67172b32c374.png)
# GRAPHICAL:
# BOX PLOT:
![Screenshot (84)](https://user-images.githubusercontent.com/128019999/232208616-4c94e206-0adc-4b45-aa6f-478e6ca1370d.png)
# COUNT PLOT:
![Screenshot (85)](https://user-images.githubusercontent.com/128019999/232208626-15975a67-71b0-4663-9cc6-a0ae35152e9d.png)
# DIST PLOT:
![Screenshot (86)](https://user-images.githubusercontent.com/128019999/232208637-84c517ab-82f9-4153-8c18-bcbb19a88f5d.png)
# HIST PLOT:
![Screenshot (87)](https://user-images.githubusercontent.com/128019999/232208651-5cf7fab3-5e89-49f4-8ace-5a39c9047334.png)

# RESULTS:

Thus the Univariate Analysis for the given data set is executed and output was verified successfully.



