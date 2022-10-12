# Hierarchical semantic segmentation neural network 

Supervisor: [Renè Schuster (DFKI)](https://av.dfki.de/members/schuster/)

As part of this master thesis, I am investigating following problems for semantic segmentation : 

### Objectives:

  1. Does cross-domain datasets training improves the performance on specific dataset?
  2. Does hierarchical network architecture with current state of art perform better than the SOTA.
  3. Human picked hierarchy Vs Automated class hierarchy for the hierarchical network. 
  4. Automated unified flat classes for cross-domain datasets
 
 ### Approaches:
 
   ```TODO will be published after the thesis submission.```
   
  
  
 ### Results: [In-progress]
 
  1. Cross-domain datasets training Vs single dataset training
  
  
| Dataset | Single Dataset  | Cross-domain Dataset |
| ------------- | ------------- | ------------- |
| Cityscapes  | 0.687  | 0.7469  |
| Vistas  | -  | 0.3934  |
| Viper  | 0.5289  | 0.5872  |
| Wilddash  | 0.4878  | 0.5825  |
| Ade  | 0.2267  | 0.3389  |
| Scannet  | 0.4346  | 0.5228  |
  
  2. State of art (DeepLabv3+) Vs Hierarchical network approach 
  
 | Dataset | DeepLab v3+  | Hierarchical Network |
| ------------- | ------------- | ------------- |
| Cityscapes| 0.7469  | - |
| Vistas | 0.3934  | - |
| Viper | 0.5872  | - |
| Wilddash | 0.5825  | - |
| Ade | 0.3389  | - |
| Scannet | 0.5228  | -|

3. Human Picked class hierarchy vs automated class hierarchy

| Dataset | Manual Hierarchy  | Auto Hierarchy |
| ------------- | ------------- | ------------- |
| Cityscapes| 0.7469  | 0.7471 |
| Vistas | 0.3934  | 0.417 |
| Viper | 0.5872  | 0.6071|
| Wilddash | 0.5825  | 0.5807 |
| Ade | 0.3389  | 0.2889 |
| Scannet | 0.5228  | 0.5102|

4. Automated unified flat classes for Multiple dataset 
  - Inprogress
  
### Comparison 

  - ![Cityscapes][unified_cityscapes]
  - ![viper][unified_viper]
  - ![vistas][unified_vistas]
  - ![ade][unified_ade]
  - ![wilddash][unified_wilddash]
  - ![scannet][unified_scannet]
  
[unified_cityscapes]: docs/unified_cityscapes.png
[unified_viper]: docs/unified_viper.png
[unified_vistas]: docs/unified_vistas.png
[unified_ade]: docs/unified_ade.png
[unified_wilddash]: docs/unified_wilddash.png
[unified_scannet]: docs/unified_scannet.png
