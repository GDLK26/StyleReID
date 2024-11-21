# StyleReID

## Dataset
![multi_style](./imgs/multi_style.png)
![wordcloud_en](./imgs/wordcloud_en.png)
![wordcloud_zh](./imgs/wordcloud_zh.png)

### Statistics
![the_child_style](./imgs/the_child_style.png)
![the_elderly_style](./imgs/the_elderly_style.png)
![top_adj_percentages](./imgs/top_adj_percentages.png)
![top_n_percentages](./imgs/top_n_percentages.png)
![top_v_percentages](./imgs/top_v_percentages.png)

### Access
Our dataset samples are available in the dataset directory. The samples are in JSON format and can be accessed as follows:

```javascript
import json
samples = json.load(open('dataset/en-samples-10.json', encoding='utf-8'))
