# LSBMP
Files for the visual planning problem in Robot Motion Planning in Learned Latent Spaces by Brian Ichter and Marco Pavone. This includes the network architecture for that problem and an implementation of L2RRT. 

To use first unzip model.tar.qz (this includes the pretrained network parameters. The rest can be done through the LSBMP_geometric.ipynb notebook.

Note, currently training data or scripts are not included due to their size. We expect to support this soon to show an example of the required data.

# Install

1. Clone repository
   - (https) `git clone https://github.com/cmower/LSBMP.git`
   - (ssh) `git clone git@github.com:cmower/LSBMP.git`
2. Change directory: `cd LSBMP`
3. Create conda environment: `conda env create -f environment.yml`
4. Activate conda environment: `conda activate lsbmp`
