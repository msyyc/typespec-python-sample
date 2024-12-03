# typespec-python-sample

This doc shows how to generate Python SDK with Typespec.

# Prerequisites

- Python 3.8 or later is required
  - [download for windows](https://www.python.org/downloads/windows/)
  - linux
    - sudo apt install python3
    - sudo apt install python3-pip
    - sudo apt install python3.{?}-venv explicitly if needed

- [Node.js 18.3 LTS](https://nodejs.org/en/download/) or later is required

# Install Dependencies

Run command:
```
npm install
```

# Generate SDK

Run command then you can find the generated SDK in folder `generated`. And you can change the output folder by change `emitter-output-dir` in `tspconfig.yaml`.
```
tsp compile main.tsp  --emit @azure-tools/typespec-python
```

