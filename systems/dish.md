
* DiSh: Dynamic Shell-Script Distribution [paper](https://www.usenix.org/system/files/nsdi23-mustafa.pdf)
* Outline
  * What is the research and why does it matter?
  * How does it work?
  * How is the research evaluated?
  * Conclusion
* Overview
  * The Five C's
     - [ ] **Category**: Proposed a new tools for running shell in distributed system
     - [ ] **Context**: This paper is for automation world where shell script are promiment
     - [ ] **Correctness**: Do the assumptions appear to be valid?
     - [ ] **Contributions**: What are the paper’s main contributions
     - [ ] **Clarity**: Is the paper well written?
   * Notes
     * Shell is still very promiment tools for automation because it is very dynamic and work with third party commands implemented in any language
     * Shell works very well in a single computer environment. Author proposed a tools to make the shell capability distributed. It will work as shim[what is shim?]. 
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
 
* Keywords:
  * **shim**:
  A shim is a library that transparently intercepts API calls and changes the arguments passed, handles the operation itself or redirects the operation elsewhere.[1][2] Shims can be used to support an old API in a newer environment, or a new API in an older environment. Shims can also be used for running programs on different software platforms than they were developed for.       
