

We utilized the Gaussian distribution function to generate KPIs for xApps, based on their respective Input Control Parameters (ICPs). 
The resulting dataset was then employed to train the prediction component of each intelligent xApp, enabling it to predict KPIs based on the ICPs. 
To model the xApps, we employed the polynomial regression block, with X representing the input and y representing the output. 
Regardless of the training dataset used, both X and y should follow these structures:
X structure: [[p11, p21], [p12, p22], [p13, p23], ....]
y structure: [y1, y2, y3]

Each xApp looks like -

            p1 ------>  |...........|
                        |  xApp_1   |-------> O_1
            p2 ------>  |...........|

