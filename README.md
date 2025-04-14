# Biblical Dead Sea Scrolls in JSON

This repository provides all available **Biblical Dead Sea Scrolls** in a single JSON file. The data is encoded in **Unicode Hebrew**, organized by scroll and verse.

Source data comes from the [ETCBC/dss](https://github.com/ETCBC/dss) project, which provides a linguistically annotated corpus of the Dead Sea Scrolls. This JSON version is a simplified extract focused only on Biblical material.

Much of the transcription and morphological tagging is based on the work of **Martin Abegg**, and adapted into Text-Fabric format by the ETCBC team.

## Format

The JSON file is a list of objects. Each object represents a scroll and contains a list of verse references and their corresponding text.

Example:

```json
[
  {
    "scroll": "2Q29",
    "verses": [
      [
        "Num 23:5",
        "ב פי בלעמ ו יאומר שׁוב אל בלק ו כוה תדבר "
      ],
      ...
    ]
  },
  ...
]
```

## License

CC BY-NC 4.0
