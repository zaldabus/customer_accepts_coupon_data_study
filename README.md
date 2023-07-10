
![Accept The Coupon](https://www.aisleofshame.com/wp-content/uploads/2022/11/Walmart-Take-Coupons.jpg)


# Will a Customer Accept the Coupon?

This repo is a data analysis based on data collected by a UCI run survey. In this survey, people were presented with different driving scenarios and asked if they would accept a coupon in the given circumstances. This repo presents findings examining the Bar and Coffee House subset of coupons.


## Installation

### Dependencies:
```yml
- Python: 3.11.3
- Anaconda: 2.4.0
- Jupyter Notebook: 6.5.4
- Matplotlib: 3.7.1
- Seaborn: 0.12.2
- Pandas: 1.5.3
- Numpy: 1.24.3
```

The easiest way to install Anaconda is from the [online download source](https://www.anaconda.com/download). See the [installation page](https://docs.anaconda.com/free/anaconda/install/index.html) for more details on installation process. After downloading open Anaconda Navigator to download Jupyter Notebook

Additional dependencies can be installed from the command line using Conda:

```bash
  conda install -c matplotlib seaborn pandas numpy
```

After installing dependencies, run a new Jupyter Notebook instance from root of project:

```bash
  jupyter notebook
```

## Lessons Learned

See included [Jupyter Notebook](./prompt.ipynb) for details of analysis.

Findings can roughly be broken down into two sections:
### Bar Coupons
[Bar Coupon Observations](./prompt.ipynb#bar-coupon-observations)

Overall, about 41% of coupons were indicated as "would use" as part of the survey.

Certain groups, such as individuals indicating regular visits to bars, were shown to be more likely to accept a coupon.

Targeting individuals between 25-30 who regularly visit bars would likely lead to an increase in coupon use.


### Coffee House Coupons
[Coffee House Coupon Observations](./prompt.ipynb#coffee-house-coupons-observations)

An analysis of coffee house coupons examining behavior across different age groups was performed.

On average, most age groups indicated a "would use" ratio of about 50%.

The "Below 21" age group indicated a significantly higher ratio, around 70%.

Targetting the "Below 21" age group would likely lead to signicantly higher coupon use.


## Authors

[@zaldabus](https://github.com/zaldabus)


## Acknowledgements

[UCI In-Vehicle Coupon Recommendation](https://archive.ics.uci.edu/dataset/603/in+vehicle+coupon+recommendation)


## License

[MIT License](https://choosealicense.com/licenses/mit/)

