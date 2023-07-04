# scRNA_analysis_developing
Ting lab's scRNA analysis of Human ureter

Branch summaries: 
- **main**: Basic version of the Seurat analysis pipeline. Uses log normalization and CCA batch correction for integration.
- **Surbhi-Dev**: Same as main branch but with Harmony option added for batch correction and integration.
- **Harmony-dev**: Implementation of Harmony for integration. Uses log normalization.
- **Matt-dev**: Matt's development copy of the pipeline. Uses SCTransform, and utilizes either CCA or RPCA for integration. Also implements doublet analysis. 
- **sctransform**: Stable version of pipeline that implements SCTransform for normalization. Otherwise identical to main. 
