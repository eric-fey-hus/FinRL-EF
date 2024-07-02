**NOTES:**

Used WSL2 Ubuntu on EFThinkPad. Conda env: FinRL.

Environment specs: packages etc, see:

 - conda-spec-file.txt
 - conda-environment.yml

To recreate from the yml file:

`conda env create -f conda-environment.yml`

To recreate form the spec-file:

`conda create --name FinRL --file conda-spec-file.txt`

To install into current environment from spec-file:

`conda install --name FinRL --file conda-spec-file.txt`

----

**NOTICE:**
Here, we provide several home-grown examples. For more tutorials with different topics, please check the repo at https://github.com/AI4Finance-Foundation/FinRL-Tutorials.

For example, in the [link](https://github.com/AI4Finance-Foundation/FinRL-Tutorials/tree/master/1-Introduction/Stock_NeurIPS2018), you can find not only the notebooks, but also the csv files and a trained agent we provide.

<div align="center">
<img align="center" src=https://github.com/AI4Finance-Foundation/FinRL/blob/master/figs/FinRL_Tutorials.png>
</div>
