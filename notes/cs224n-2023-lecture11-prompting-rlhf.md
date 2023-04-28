**CS 224N (23') Lecture 11.Prompting, Reinforcement Learning from Human Feedback.**

*Jesse Mu.* **2023.** [[slides](../documents/cs224n-2023-lecture11-prompting-rlhf.pdf)] [[slides on-line](http://web.stanford.edu/class/cs224n/slides/cs224n-2023-lecture11-prompting-rlhf.pdf)]

+ zero-shot and few-shot prompting (in-context learning)

    + [√] no fine-tuning needed, prompting engineering (e.g. CoT) can improve performance

    + [×] limits to what you can fix in context

    + [×] complex tasks will probably need gradient steps (called *warm-up* in in-context learning survey)

+ instruction fine-tuning

    + [√] simple and straightforward, generalize to unseen tasks

    + [×] collecting demonstrations fore so many tasks is expensive

    + [×] mismatch between LM objective and human preferences

+ reinforcement learning from human feedback (RLHF)

    + [√] directly model and optimize for human preferences (cf. language modeling), generalize beyond labeld data

    + [×] requires human feedback, maybe could be automated (e.g., constitutional AI from Anthropic used RLAIF)