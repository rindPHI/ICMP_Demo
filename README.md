# ICMP Constraints Demo

This demonstration showcases the problem of learning semantic constraints of IP/ICMP network packets.
It comes as a Jupyter notebook explaining the basics of the ICMP format, specifying its grammar, showing the desired necessary semantic constraints on top of the grammar, and establishing some foundations to build a learning approach upon.

To run the notebook in a Python virtual environment, perform the following steps (this requires Python v3.10 on your system, available in your PATH):

```bash
python3.10 -m venv venv
source venv/bin/activate  # in the bash shell; there's also activate.fish etc.
pip install -r requirements.txt
python -m ipykernel install --user --name=ICMP_Demo
jupyter lab .
```

Then, Jupyter Lab should open in your default browser and you should be able to select and you should be able to open the file `ISLa_ICMP_Demo.ipynb`.
It might be necessary to change the kernel (Kernel -> Change Kernel) to the kernel named "ICMP_Demo."
