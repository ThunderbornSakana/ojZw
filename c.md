Skipping the Safe Pretraining step results in the inability to use the input-label pairs from recent conversions in the target domain data. This leads to a loss of information. To quantify this, we performed a statistical analysis to determine the percentage of total conversions that are wasted:
* Criteo dataset: Without Safe Pretraining, **11.4051%** of total conversions are not utilized.
* Taobao dataset: Without Safe Pretraining, **11.4898%** of total conversions are not utilized.
* Tencent dataset: Without Safe Pretraining, **10.9692%** of total conversions are not utilized.
