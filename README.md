## Local access

Written with UV for package management. Activate the UV lock file with

```
uv init 

uv run --with jupyter jupyter lab

```

## Interactive data access tutorial

[Cosyne Data Access - Open with Colab](https://colab.research.google.com/github/AllenInstitute/connectomics_at_cosyne/blob/main/examples/Cosyne_Data_Access.ipynb)


In the repository for this data access tutorial, there is also

* Preprocessing used to colate the cell types information : `preprocessing_celltypes_v1718.ipynb`
* Setting up a persistent CAVE token for continued use in google colab : `Tutorial_Colab_Persistent_Token.ipynb`
* Downloading the synaptic cleft and mesh around the synapse for further analysis : `Tutorial_Download_Synapse_Mesh.ipynb`
* Programmatic generation and parsing of neuroglancer states : `Tutorial_NGLUI.ipynb`

<b>Furter documentation</b>
* MICrONS Tutorials : https://tutorial.microns-explorer.org/
* Connectome Annotation Versioning Engine CAVE : https://www.caveconnecto.me/CAVEclient/tutorials/
* Ossify : https://csdashm.com/ossify/