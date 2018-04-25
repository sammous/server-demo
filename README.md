# Visualisation demo for a text classifier.
This repository is the front app to demo a model trained via [allenNLP](allennlp.org). Examples can be previewed on their [demo website](demo.allennlp.org/).
## Requirements

allenNLP server must be running with a classification model (allenNLP simple server) on port `8000`.
Check instructions directly in the model repo (https://github.com/sammous/allenNLP_papers).

Example command :

```
python -m allennlp.service.server_simple \
    --archive-path model/model.tar.gz \
    --predictor paper-classifier \
    --include-package papers \
```

## Credits

- https://github.com/allenai/allennlp-simple-server-visualization
