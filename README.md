# Privacy Leakage in O-RAN: Remote CSI-Based Respiration Eavesdropping Using 5G Signals


This repository contains the source code, example data,
and demonstration materials for our submission.

## Demo Video

We provide a demo video showcasing the **office experiment setup** and the performance of **CellRespi**.

- 🌐 **Watch the demo online:** [CellRespi Demo Website](https://saml758.github.io/CellRespi/)
- 🎥 **Download the demo video:** If the embedded video does not play on Anonymous GitHub, please check [CellRespi Demo Website](https://saml758.github.io/CellRespi/).

The video presents the experimental setup and representative respiration sensing results obtained with CellRespi.

## Quick Start
We provide a lightweight example dataset for reproducing the core functionality of our system.

1. Download the source code and the example dataset.
2. Open `respiration_extraction_from_csi.py` and add the path to the example dataset to `DATA_DIRS`, e.g., "../example data".
3. Run:
   ```bash
   pip install numpy scipy matplotlib
   python respiration_extraction_from_csi.py
