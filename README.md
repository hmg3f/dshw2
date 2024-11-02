# Instructions
All of the code is located in the `src` directory, in a jupyter notebook. Uses the R language, so the R jupyter kernel is needed. In the R interpreter:

```R
install.packages('IRkernel')
require(IRkernel)
IRkernel::installspec()
```

Then run a jupyter lab instance from the main directory in this repository:

```sh
git clone https://github.com/hmg3f/dshw2
cd dshw2
jupyter lab
```

Select the R kernel and open the notebook file in `src/analysis.ipynb`. The dataset is already provided in the repository under `data_raw`.
