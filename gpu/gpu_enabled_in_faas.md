# GPU-enabled Function-as-a-Service for Machine Learning Inference
* [paper link](https://arxiv.org/abs/2303.05601)
* Outline
  * What is the research and why does it matter?
  * How does it work?
  * How is the research evaluated?
  * Conclusion
* Overview
  * The Five C's
     - [ ] **Category**: 
     This papers talked about potential uses of GPU in FasS environment and challenged with it. It also proposed a solution of the challenges

     - [ ] **Context**: 
     This paper is related to `Virtual GPU device plugin for inference workloads in Kubernetes.` This paper proses based on the custom scheduler and local caching mechanism to transfer the data from CPU to the GPU devices. Most improtant part is Localized Aware load babancing. 
     - [ ] **Correctness**: 
     The results show that it can substan- tially improve model inference performance. For example, the LALB scheduler reduces the baseline (LB) scheduler’s average latency and cache miss ratio by 79.43% and 65.21%, respectively, for a workload of working set size of 35. Ad- ditionally, the out-of-order (O3) dispatch can work with the LALB scheduler to further improve the locality performance and reduce the LB scheduler’s average latency and cache miss ratio by 96.93% and 81.16%, respectively
     - [ ] **Contributions**: 
     Implementing GPU enabled worklaod for the cloud environment like FaaS. 
     - [ ] **Clarity**: 
     Yes; it is very well written
   * Notes
   **What is the problems with GPU for multiple application?**
   GPU Problems for multiple applications
   GPUs have three limitations that make it difficult for multiple applications to share the same GPU.
   * First, the capacity of GPU memory is significantly lower than host memory. If the processing data size is larger than the available GPU memory capacity, GPU programmers are responsible for managing the active working set in GPU memory. 
   * Second, although GPU provides fast computations, it incurs extra overhead while transferring data, e.g., model parameters and inputs, from host memory to GPU memory. 
   * The data transfer overhead of the GPU arises in the PCIe interface as the maximum bandwidth of the current PCIe is much lower (in the order of 100GB/s) compared to the internal memory bandwidth of the GPU (in the order of 1TB/s).

   **What is inference?** 
   * In the context of deep learning, the term "inference" refers to the process of utilizing a trained machine learning model to make predictions or decisions based on new, unseen data. It is one of the two primary tasks associated with deep learning, with the other being "training."

   
* Questions
   * What is the motivation for the paper?
   * What are the paper's contributions?
   * How does the paper relate to existing solutions?
   * How does the paper evaluate it's solution?
*  Worklog
* Checklist
   - [ ] First pass <15 minutes>
      - [ ] Carefully read the title, abstract, and introduction
      - [ ] Read the section and sub-section headings, but ignore everything else
      - [ ] Read the conclusions
      - [ ] Glance over the references, mentally ticking off the ones you’ve already read
      - [ ] Answer The Five C's
   - [ ] Second pass <60 minutes>
      * Read the paper with greater care, but ignore details such as proofs
        - [ ] Look carefully at the figures, diagrams and other illustrations in the paper. Pay special attention to graphs. Are the axes properly labeled? Are results shown with error bars, so that conclusions are statistically significant? Common mistakes like these will separate rushed, shoddy work from the truly excellent
        - [ ] Remember to mark relevant unread references for further reading (this is a good way to learn more about the background of the paper).
  - [ ] Third pass - 4 hours
