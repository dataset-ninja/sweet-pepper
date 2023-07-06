Dataset **Sweet Pepper** can be downloaded in Supervisely format:

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/1/N/pI/EqrSGHLjMYawkM7xHV7WBVeSm8oCXdJ4ZhIlmDtEhBMrMkOFAQ42kcsMqESt4Tg7RW8m4QYf5r7iJN5XdtiIWy3iY9yVPyFvDi78wVv1CjFpHVYGjkKZeanSTEGy.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Sweet Pepper', dst_path='~/dtools/datasets/Sweet Pepper.tar')
```
The data in original format can be 🔗[downloaded here](https://www.kaggle.com/datasets/lemontyc/sweet-pepper/download?datasetVersionNumber=1)