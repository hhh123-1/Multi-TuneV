# Multi-TuneV
Official repository for Multi-TuneV: Fine-tuning the Fusion of Multiple Modules for Video Action Recognition. Code will be released soon.
# Abstract
Recent research has used parametric efficient transfer learning(PETL) approaches to enable pre-trained models to transfer to the field of Video Action Recognition(VAR). While most of the current efficient fine-tuning methods have been investigated with respect to a single fine-tuning module, and a single fine-tuning approach for a complex task may not be able to achieve optimal results. We want to investigate the effect of joint fine-tuning with multiple modules, so we propose a method that merges multiple fine-tuning modules, namely Multi-TuneV. It combines five fine-tuning methods, including ST-Adapter, AdaptFormer, BitFit, VPT and LoRA. We designed a particular architecture for Multi-TuneV. Multi-TuneV allows the pre-trained model to learn both temporal and spatial information. We conducted extensive experiments with Multi-TuneV on three video datasets and showed that it surpasses both full fine-tuning and other single efficient fine-tuning methods. Multi-TuneV provides a new perspective to address the challenges in VAR. 
