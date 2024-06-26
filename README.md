# aib9_openmm

Working protocol for setting up solvated Aib9 system using Charmm36m forcefield and running long MD simulation (NPT) in OpenMM.
1. Create a conda environment from the requirements.txt by running the command below
```
conda create --name aib9 --file requirements.txt -c conda-forge
conda activate aib9
```
2. Open and run aib9.ipynb using jupyterlab. The following command should open jupyterlab in your browser.
   ```
   jupyter lab
   ```

If you are using this repository for running Aib9 simulations, please cite the following paper:
```
@article{mehdi2022accelerating,
  title={Accelerating all-atom simulations and gaining mechanistic understanding of biophysical systems through state predictive information bottleneck},
  author={Mehdi, Shams and Wang, Dedi and Pant, Shashank and Tiwary, Pratyush},
  journal={Journal of chemical theory and computation},
  volume={18},
  number={5},
  pages={3231--3238},
  year={2022},
  publisher={ACS Publications}
}
```
