# Project QUESC: Quantum Environmental Sound Classification using Quantum Transfer Learning

**Abstract**:<br> Environmental Sound classification (ESC) is crucial in various fields such as audio surveillance, wildlife conservation, and acoustic monitoring. However, traditional methods often struggle to handle the curse of dimensionality and the limitations of classical machine learning algorithms. In the paper, a novel approach is proposed for ESC using a Quantized Hybrid Quantum-Classical Neural Network (QQNN), which leverages the potential advantages of quantum computing. The Hybrid QQNN architecture aims to reduce the required parameters and achieve performance comparable to traditional methods. It uses a set of pre-trained layers to reduce the number of features for the parameterized quantum circuit (PQC). This approach was evaluated using the ESC-10 dataset in Pennylane's environment to train the hybrid quantum model. The results demonstrate that the proposed Hybrid QQNN approach achieves comparable accuracy with the classical machine learning methods. This opens up the possibility of performing additional transfer learning in the future.


**Research Paper Link**: [Procedia Computer Science Journal, Vol. 230](https://doi.org/10.1016/j.procs.2023.12.111)

**Dataset Used**:<br> [ESC - 10](https://github.com/karolpiczak/ESC-10/tree/553c8f1743b9dba6b282e1323c3ca8fa76923448)

**Dataset Description**:<br> ESC-10 consists of 400 environmental recordings categorized into 10 different classes. Each class comprises 40 audio clips (44.1 KHz, Mono), with each clip of duration 5 seconds.

**Repository Contents**:<br>
| S.No | Topic | Branch | Content |
|------|-------|--------|---------|
| 1    | Classical Models | classical | Contains all the Classical Models used for comparison and evaluation purposes |
| 2    | Quantum Model | quantum | Contains our proposed Quantum Transfer Learning Model |
