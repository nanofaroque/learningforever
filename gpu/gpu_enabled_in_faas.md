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
