## Datasets
> The main evaluation datasets are RealSR and DRealSR. Standard testing datasets such as Set5, Set14, B100, U100, Manga109 could be found [here](https://drive.google.com/file/d/1w-brbpprWHyT4tzCe_MoB2tqEcSOc5OW/view)

* RealSR: https://github.com/csjcai/RealSR?tab=readme-ov-file
* DRealSR: https://github.com/xiezw5/Component-Divide-and-Conquer-for-Real-World-Image-Super-Resolution

## Models

* My LESRCNN [fork](https://github.com/majauhar/LESRCNN)
* OMNI-SR [fork](https://github.com/majauhar/Omni-SR)
> I have used the original code as my work is mostly evaluating the method. However, given that the original codebase it from 2020, I have modified it from `python 2.7` to `python 3.x` standards. Furthermore, the evaluation pipeline has been adjusted, particularly the dataloader modules, to make it suitable for processing RealSR and DRealSR datasets.
>
> # Notebooks
> * Analysing processes at system level requires building local installations of some packages. Hence, notebooks should be run on local machines.
> * The GPU version of the notebook is used only for evaluating GPU inference latency.
