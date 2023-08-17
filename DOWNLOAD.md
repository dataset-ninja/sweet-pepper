Dataset **Sweet Pepper** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/M/t/i9/ePsA7JzL5DqWUQaQuBIWS5hb057Nh1AC7ty4riQytLAG8iHattEqmXDCtjbcK7OKglA0BWdqAIZD2I16xmN2crOsgm6n8PZcuoOcqGMQJB0t7jhixJxRXNHR9Tmb.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Sweet Pepper', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://www.kaggle.com/datasets/lemontyc/sweet-pepper/download?datasetVersionNumber=1).