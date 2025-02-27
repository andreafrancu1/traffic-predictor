# traffic-predictor
### Final Project for DTSA 5511: Introduction to Deep Learning
#### University of Colorado, Boulder - Master of Science in Data Science

**By:** Andrea Francu  
**Version:** 1.0  
**Date:** February 26, 2025

This project was inspired by the Keras tutorial "Traffic Forecasting Using Graph Neural Networks and LSTM," which caught my attention for its approach to capturing traffic dependencies not only on individual roads but also across neighboring areas. This comprehensive view of traffic modeling highlighted the power of neural networks in handling such complex relationships.

However, my project took a different direction. Instead of using a Graph Neural Network with LSTM, I initially implemented a Transformer model for traffic prediction. This approach proved quite challenging, and I was unable to achieve the level of precision I aimed for. In the end, I transitioned to a simpler MLP model, but I still encountered difficulties with prediction accuracy, managing training times, and conserving GPU resources.

Although inspired by the Keras tutorial, I decided to build my model in PyTorch rather than Keras, incorporating both spatial and temporal data. This choice was driven by my desire to gain hands-on experience with PyTorch, a library I had yet to explore.
