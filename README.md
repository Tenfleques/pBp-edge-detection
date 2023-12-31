# pBp-edge-detection
Detection image edges using pseudo-Boolean polynomials


## Getting started 

Create virtual environment and install dependences 

`python -m virtualenv .env`

`source .env/bin/activate`

`pip install -r requirements.txt`

Run image edge detection with example images in `examples/images` using the parameters defined in `args.json`.

The outputs are displayed in `examples/pbp-edges` with the same name of the input image.

In the output directory, a similar name without the -pbp-mask appended shows the processing steps.

Some examples have comparative edge masks in `examples/masks`

The program is not yet optimised, therefore some instances process longer.

The `args.json` contain varied arguments to show how the parameters affect the edge detection process.

`python edge_detection.py`

