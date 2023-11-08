Dataset **Google Recaptcha Image** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/H/8/vV/7kYh4VF03tUXoJNP0TanCBTp0oxP0DpaTGP4a6NQaCKEFLeoq4shApEEn9SoG7JgrKmktRY0TxKmDVdNNMhFPLZX9BjgRrURWwLdG7om0p87a5t4NzR2lvdiJDsz.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Google Recaptcha Image', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://www.kaggle.com/datasets/mikhailma/test-dataset).