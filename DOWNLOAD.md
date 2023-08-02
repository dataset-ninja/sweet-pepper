Dataset **Sweet Pepper** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/j/4/qn/K3Ln4n6ocXR5CdxaIMSNljgOBglHUBA1QJ8Zuk3UO5oIWN1oOjTd49XEukWraD42PUvlreQD2mkFULEXM86YSoW19JFlPoRONf3TkEZRv6BX8Gds6bh00ajbfdBc.tar)

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

The data in original format can be [downloaded here](https://www.kaggle.com/datasets/lemontyc/sweet-pepper/download?datasetVersionNumber=1)