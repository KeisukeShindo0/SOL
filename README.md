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

	https://keisukeshindo0.github.io/SOL_feedback_evaluation/

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


### SOLの目標：正確で信頼できるAI

　SOL(Self-Organizing Logic)は、新規に考案した機械学習のアルゴリズムであり、正確性、厳密性を最重視している。SOLの理論体系は厳密で包括的なものであり、今後の汎用人工知能AGIと呼ばれる機械学習システムはこのSOLの延長線上にあると確信している。

　生産性向上のために最も必要なAIは、自動車やロボットなどの自動制御を信頼して任せることができるAIである。信頼できるAIとは、不確定な状況を確実に判断して制御を確実に停止させることができるAIでもある。逆に、正確でない機械学習は常に人間などの確認が必要となり、放任が出来ないために生産性の向上が頭打ちになる。

### 現状の大規模言語モデルLLMの問題

　現在の大規模言語モデルLLMは目覚ましい実績を出しているが、それは近似的な手段による計算規模の爆発的な増大が成功理由と考えられる。だが、現状のNeuralNetworkはXORを含む単純な論理式すら正確に生成できない。そのためNeuralNetworkは厳密さに欠けており、自律的に正解にたどり着けない。それをおそらくは大量の学習による演繹で補っているのが現状で、それが理由で現在のTransformerは真偽の自律的判定、応用力に弱いと考えられる。そして現在のLLMのハルシネーションの問題は、単純に現在のLLMのアルゴリズムが不正確であることが原因である可能性が高い。

　現在のLLMで採用されているTransformer、Attentionはこれまでにない応用力を持ち、自然言語処理の圧倒的な性能向上に貢献した。だが、Attentionに相当する機構は、SOLを用いればより厳密かつ包括的に表現できる。このため、SOLを基本にLLMを構築すれば、Attentionよりも正確な自然言語処理エンジンを構築できる。

### SOLの優位点

- 論理演算と確率とを厳密に用いることで正確な学習ができる。
- 無駄のない学習が可能になり、ハードウェアや電力コストを最小にできる。
- 学習の結果を論理的に完全に説明できる。
- 抽象的な論理を理論体系に含んでいるため、メタ知識による学習内容の自律検証が可能になる。

### 現在の進捗

- 正確な機械学習を実現するための理論体系の構築。現在の機械学習のような発見的な手法ではなく、論理的で厳密な理論を構築した。
- 基本となる確率フィードバックアルゴリズムの正当性の確認。Pythonでモデルを記述して、基本的な論理演算の学習を実装して確認した。
- 既存のニューラルネットワークと比較して、SOLの確率フィードバックアルゴリズムの正確性を確認。

https://keisukeshindo0.github.io/SOL_feedback_evaluation/

### 現状での欠点

- 高速化が非常に難しい。アルゴリズムにオブジェクト参照が多く、データベースの並列化と似た難しさがある。巨大行列演算での実装を行っていないためにGPUやTPUなどによるSIMD並列化を利用できていない。
- 単純な実装では演算量が爆発的に増大するので、それを防止するための機構が未完成。

### 今後の計画
- SOLのテスト実装
	SOLの全機能を実装テスト。双方向伝搬、ステート、写像、代入、一般化複製まで実装したシステムを構築する。言語はとりあえずはPythonでも良い。
- 実用版実装開発
	Pythonからより高速な言語へ。C++やRustなどから開発が容易なものを選択。テスト方針を定めて信頼できる学習が行われることを確認する。
- 高速化、並列化
	最初の段階ではマルチスレッド並列を用いる。可能であればGPU、TPUなどのSIMD並列も利用したいが、今のところ適性が低いと考えられる。最終的には最適なコンピュータアーキテクチャを提案する。当方はコンピュータアーキテクチャ自体の知識や経験もある。
- 実用化
	適切な入出力関数の実装による実用アプリケーションへの応用テスト。現在は人間が操作しているアプリケーションソフトウェアを人間の代わりに正確に自律動作させること。そして、信頼できる自動運転や自動ロボット制御を実現する。

### 今後必要なもの

- SOLのテスト実装を完成させるには協力者はそれほど必要ないが、研究費は必要になる。GPU,TPUなどはとりあえずは必要性は低いが、大量のマルチプロセッサシステムは不可欠になる。
- 実用版実装開発からは大規模な計算装置が不可欠になる。テストや大量の用途に適合させるための人員も大量に必要になる。既存のTPUなどの利用も試みる。
- 最終的には専用ハードウェアの開発が必要になる。膨大な開発人員と予算が必要になる。
