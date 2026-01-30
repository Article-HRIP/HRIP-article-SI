Here, we build nD(refractive index at D line) predictor based on experimental data.
1. library dependacy
   - To reproduce our result, create a new environment and then install libraries described in requreiments.txt.　<br>
     -- put !pip install -r requirements.txt on isolated clean environment <br>
   - There is version dependancy of numpy, statsmodels, and other libraries depolyed in FRATTVAE(https://github.com/slab-it/FRATTVAE)

2. How to obtain predicted values.
   * We provide pickle files to reproduce the prediction result.<br>
     - molecule polarizibility ($\mathsf{\alpha}$)<br>
     - molecule Volume ($\mathit{V}$)<br>
  
   * 
3. How to run the codes? <br>
   3.1 Prepare the environment following 1. (It is easy to create an environment on Google Colab or Anaconda.) <br>
   3.2 Run jupyter notebook from first cell () <br>
   3.3 See Outputs. <br>
   
4. Data preparation on FRATTVAE
  * Authors of FRATTVAE, molecule generative model applied in this work, provide standardized data.
    - The availablity is limitted (only academic purpose is available).
    - See https://github.com/slab-it/FRATTVAE/tree/main for more details.
