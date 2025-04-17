# SOL

Documents of Self-organizing logic

[English paper PDF](https://KeisukeShindo0.github.io/SOL/SOL-EN.pdf)
[Japanese paper PDF](https://KeisukeShindo0.github.io/SOL/SOL.pdf)

- SOL-EN.pdf　SHA256 Hash: 4D0AB273FC6EFD3D4873D09DB960DB8A7FDF0D291262356C0BDD9749A62CBD79
- SOL.pdf SHA256 Hash: 8EF0C9209F7CEA4872682F66DFCA0DB6F4949F75D3D652ED7191CF22E7C8E67E


### SOL's goal: accurate and trustworthy AI

SOL (Self-Organizing Logic) is a newly invented machine learning algorithm that places the utmost importance on accuracy and rigor. The theoretical framework of SOL is rigorous and comprehensive, and we are convinced that future machine learning systems known as AGI (General Artificial Intelligence) will inevitably be an extension of SOL.

The AI​most needed to improve productivity is an AI that can be trusted to control the automatic operation of automobiles, robots, etc. A trustworthy AI is one that can judge uncertain situations and reliably stop control. Conversely, inaccurate machine learning constantly requires confirmation by humans and cannot be left to its own devices, which causes productivity improvements to plateau.

### Current issues with large-scale language models (LLM)

The current large-scale language model LLM has achieved remarkable results, but the reason for its success is thought to be the explosive increase in the scale of calculations through approximation. However, the current Neural Network cannot accurately generate even simple logical expressions including XOR. As a result, the Neural Network lacks precision and cannot reach the correct answer autonomously. This is probably compensated for by deduction through large amounts of learning, and for this reason, the current Transformer is thought to be weak in autonomously judging truth and falsehood and in its application capabilities. The hallucination problem of the current LLM is likely simply due to the inaccuracy of the current LLM algorithm.

The Transformer and Attention used in the current LLM have unprecedented application capabilities and have contributed to the overwhelming improvement of natural language processing performance. However, the mechanism equivalent to Attention can be expressed more precisely and comprehensively using SOL. Therefore, if an LLM is built based on SOL, it is possible to build a natural language processing engine that is more accurate than Attention.

### Advantages of SOL

- Accurate learning is possible through the rigorous use of logical operations and probability.
- Efficient learning is possible, minimizing hardware and power costs.
- The results of learning can be completely explained logically.
- Because the theoretical system contains abstract logic, it becomes possible to autonomously verify the learning content through meta-knowledge.

### Current progress

- Building a theoretical framework for achieving accurate machine learning. A logical and rigorous theory was constructed, rather than the heuristic methods used in current machine learning.

- Confirming the validity of the underlying probability feedback algorithm. A model was written in Python, and learning of basic logical operations was implemented and confirmed.

- Confirming the limits of accuracy of existing neural networks and the superiority of the SOL algorithm.

### Current shortcomings

- Very difficult to speed up. The algorithm has many object references, which is similar to the difficulty of parallelizing a database. Since it has not been implemented for large matrix operations, it is not possible to use SIMD parallelization using GPUs, TPUs, etc.
- A simple implementation would result in an explosive increase in the amount of calculations, so the mechanism to prevent this has not yet been completed.

### Future plan

- Test implementation of SOL
Implementation testing of all SOL functions. Build a system that implements bidirectional propagation, state, mapping, assignment, and generalized replication. Python can be used as a language for now.
- Practical implementation development
Move from Python to a faster language. Select an easy-to-develop language from C++ or Rust. Establish a test policy and confirm that reliable learning is performed.
- Speedup, parallelization
Use multi-threaded parallelism in the first stage. If possible, we would like to use SIMD parallelism such as GPU and TPU, but at the moment, we believe that it is not suitable. Ultimately, we will propose the optimal computer architecture. We also have knowledge and experience in computer architecture itself.
- Practical application
Testing practical applications by implementing appropriate input/output functions. Making application software that is currently operated by humans operate autonomously and accurately in place of humans. This will lead to the realization of reliable autonomous driving and autonomous robot control.

### What is needed in the future

- We won't need many collaborators to complete the test implementation of SOL, but we will need research funds. For the time being, GPUs, TPUs, etc. are not very necessary, but large-scale multi-processor systems will be essential.

- Large-scale computing equipment will be essential for the development of a practical implementation. A large number of personnel will also be needed to adapt it to testing and large-scale applications. We will also try to use existing TPUs, etc.

- Ultimately, we will need to develop dedicated hardware. A large number of development personnel and budgets will be required.

