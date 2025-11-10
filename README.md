# Reimagining Anomalies: What if Anomalies Were Normal?

Here we provide the implementation for the paper *Reimagining Anomalies: What if Anomalies Were Normal?*.

The implementation is based on PyTorch 2.1.2 and Python 3.10. The code is tested on Linux only. 

<img src="data/main_figure.png?raw=true" height="525" width="738" > 

The figure illustrates the benefit of counterfactual explanation of anomaly detectors over traditional methods, using a dataset of handwritten digits in various colors. The normal data (top left) consist of red digits and instances of the digit one in any color. An example anomaly---a green seven---is shown on the right. Conventional explanation methods localize the anomaly in the image and highlight it on a heatmap (bottom left). In contrast, the proposed method transforms the anomaly into multiple counterfactuals, addressing the crucial question: ``How must the anomaly be altered to appear normal to the detector?"

**Abstract**
Deep learning-based methods have achieved a breakthrough in image anomaly detection, but their complexity introduces a considerable challenge to understanding why an instance is predicted to be anomalous. We introduce a novel explanation method that generates multiple alternative modifications for each anomaly, capturing diverse concepts of anomalousness. Each modification is trained to be perceived as normal by the anomaly detector. The method provides a semantic explanation of the mechanism that triggered the detector, allowing users to explore ``what-if scenarios.'' Qualitative and quantitative analyses across various image datasets demonstrate that applying this method to state-of-the-art detectors provides high-quality semantic explanations. 


## WORK IN PROGRESS
The code will be provided soon. Stay tuned.
