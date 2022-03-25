# 112

Data story​ or data ​storytelling​ is the practice of building a narrative around a set of ​data​ and its accompanying visualizations to help convey the meaning of that ​data​ in a powerful and compelling fashion.


import plotly.figure_factory as ff
fig = ff.create_distplot([df["quant_saved "].tolist()], ["Savings"], show_hist=False)
fig.show()
